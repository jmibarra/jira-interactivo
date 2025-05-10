# 2.4. Administradores

<span class="badge badge-organization">Organization</span>

Ya conocemos la estructura de Jira Cloud y como las cuentas interactuan con este, ahora vamos a enfocarnos en un actor especial, las cuentas de Administración. Jira Cloud tiene distintos niveles de administración, cada uno con permisos y alcances específicos. Esta jerarquía permite distribuir la gestión del sistema de forma segura y eficiente, desde la gobernanza global hasta la administración de proyectos puntuales.

A continuación, te presentamos los roles administrativos más comunes dentro del ecosistema de Atlassian Cloud.

---

## 🏢 Organization Administrator

| Características | Detalles |
|------------------|----------|
| **Nivel**        | Máximo (global, sobre toda la organización) |
| **Acceso**       | admin.atlassian.com |
| **Responsabilidades** | - Gestión de usuarios a nivel de toda la organización<br>- Verificación de dominios<br>- Configuración de políticas globales (SSO, 2FA)<br>- Administración de facturación<br>- Integración con Atlassian Access |
| **Permisos**     | Totales sobre todos los sitios, productos y usuarios registrados bajo la organización. |
| **Requiere Atlassian Access** | Para algunas funciones avanzadas, sí. |

---

## 🌐 Site Administrator

| Características | Detalles |
|------------------|----------|
| **Nivel**        | Administrador de sitio (por ejemplo: `miempresa.atlassian.net`) |
| **Acceso**       | admin.atlassian.com (nivel sitio) |
| **Responsabilidades** | - Invitar usuarios al sitio<br>- Asignar productos (Jira, Confluence, etc.)<br>- Gestionar grupos y roles<br>- Configurar apps del sitio |
| **Permisos**     | Control total sobre los usuarios y productos **de ese sitio** únicamente. No puede ver configuraciones de otras instancias/sitios. |

---

## 🛠️ Product Administrator (Jira Admin)

| Características | Detalles |
|------------------|----------|
| **Nivel**        | Producto (Jira Software, JSM, Confluence, etc.) |
| **Acceso**       | A través del propio producto (`Configuración del sistema`) |
| **Responsabilidades** | - Crear y administrar proyectos<br>- Configurar esquemas (workflows, permisos, pantallas, etc.)<br>- Instalar y configurar apps específicas del producto |
| **Permisos**     | Control total sobre la configuración funcional del producto, pero **no sobre los usuarios del sitio** (a menos que también sea Site Admin). |

---

## 📁 Project Administrator

| Características | Detalles |
|------------------|----------|
| **Nivel**        | Proyecto |
| **Acceso**       | Dentro del proyecto (si tiene permisos de admin) |
| **Responsabilidades** | - Administrar componentes, versiones, tableros y automatizaciones<br>- Gestionar roles dentro del proyecto<br>- Configurar permisos (si usa esquema delegable) |
| **Permisos**     | Limitados al ámbito del proyecto. No puede alterar la configuración global del producto. |

---

## 👤 User Administrator

| Características | Detalles |
|------------------|----------|
| **Nivel**        | Gestión de usuarios |
| **Acceso**       | Desde admin.atlassian.com |
| **Responsabilidades** | - Invitar y eliminar usuarios<br>- Asignar y revocar accesos a productos<br>- Ver grupos y dominios verificados |
| **Permisos**     | Gestión exclusiva de usuarios, sin acceso a configuraciones de producto o proyecto. |

---

## 🧠 Resumen comparativo

| Rol                    | Alcance                | Gestión de usuarios | Configura productos | Administra proyectos |
|------------------------|------------------------|----------------------|---------------------|----------------------|
| Organization Admin     | Toda la organización   | ✅ Sí                | ✅ Sí               | ✅ Sí                |
| Site Admin             | Un sitio específico    | ✅ Sí                | ✅ Sí               | ✅ Sí                |
| Product Admin          | Un producto (Jira, etc)| ❌ No                | ✅ Sí               | ✅ Sí                |
| Project Admin          | Un proyecto            | ❌ No                | ⚠️ Parcial          | ✅ Sí                |
| User Admin             | Usuarios globales      | ✅ Sí                | ❌ No               | ❌ No                |

```{admonition} Importante
:class: warning
Los Organization Admins y los Site Admins, al estar por encima de un producto en particular, consume licencias de todas las apps instaladas en ese site o esa organization. 
```

---

## 📝 Notas adicionales

- Un mismo usuario puede tener **varios de estos roles simultáneamente**.
- La correcta asignación de estos niveles es clave para mantener **seguridad, control y delegación efectiva**.
- Para administrar estos roles, se accede generalmente desde **admin.atlassian.com** o desde la sección de configuración del producto.