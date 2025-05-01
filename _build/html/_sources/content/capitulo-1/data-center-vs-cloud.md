# Atlassian Cloud vs Data Center

Al comenzar a trabajar con los productos de Atlassian, una de las primeras decisiones estratégicas es elegir entre el despliegue en la nube (**Cloud**) o una instalación autogestionada en tus propios servidores (**Data Center**).

Cada enfoque tiene ventajas y limitaciones según las necesidades de tu organización.

---

## ☁️ Atlassian Cloud

La opción **Cloud** es un servicio totalmente gestionado por Atlassian. No requiere infraestructura propia ni mantenimiento técnico por parte del usuario.

### Ventajas:

- **Sin mantenimiento**: Atlassian se encarga de actualizaciones, parches de seguridad y disponibilidad.
- **Escalabilidad automática**: Ideal para equipos en crecimiento.
- **Acceso inmediato** desde cualquier lugar y dispositivo.
- **Integraciones simples** con otras herramientas en la nube (Confluence, Slack, GitHub, etc.).
- **Facturación por usuario activo** y modelos de licenciamiento simples.

### Consideraciones:

- Menor control sobre la infraestructura subyacente.
- Limitaciones en personalización avanzada del backend.
- Algunos plugins o apps del Marketplace solo están disponibles para Server/Data Center.
- Así como es una ventaja no preocuparnos por las actualizaciones, muchas veces nos encontramos con cambios en la herramienta que no son convenientes para la organización y que no pueden ser omitidos en nuestra instancia.
- En caso de que haya cambios en políticas de Atlassian nos afectaran directamente.

---

## 🏢 Atlassian Data Center

La opción **Data Center** está pensada para grandes organizaciones con requerimientos específicos de control, privacidad o compliance. Permite instalar y operar Jira (u otros productos Atlassian) en infraestructura propia o en proveedores como AWS o Azure.

### Ventajas:

- **Control total** sobre el entorno, base de datos, red y configuraciones del sistema.
- **Alta disponibilidad** y balanceo de carga con clústeres de nodos.
- **Integración profunda** con sistemas internos (LDAP, SSO, proxies, etc.).
- Posibilidad de mantener datos **on-premise**, útil para industrias reguladas.

### Consideraciones:

- Requiere **equipo técnico especializado** para instalar, mantener y escalar la plataforma.
- Licenciamiento más complejo y costoso.
- Menor agilidad para actualizar (aunque se controla cuándo y cómo hacerlo).

---

## 📊 Comparativa general

| Característica           | Atlassian Cloud             | Atlassian Data Center        |
| ------------------------ | --------------------------- | ---------------------------- |
| Hosting                  | Gestionado por Atlassian    | Autogestionado               |
| Mantenimiento            | Automático                  | Requiere administración      |
| Escalabilidad            | Automática                  | Manual (más compleja)        |
| Personalización profunda | Limitada                    | Avanzada                     |
| Control de datos         | Bajo (en la nube)           | Total                        |
| Ideal para               | Equipos pequeños a medianos | Empresas grandes o reguladas |

---

```{admonition} ¿Qué opción es la adecuada para mí?
:class: tip
Si buscás simplicidad, velocidad de implementación y bajo mantenimiento, **Cloud** es la mejor opción. Si necesitás control absoluto, cumplimiento normativo o una arquitectura distribuida, **Data Center** es el camino.
```

---

```{admonition} Importante
:class: warning
Este libro en particular se va a centrar en la versión Cloud de los productos Atlassian. Si bien algunas configuraciones son similares, es cada vez mayor la diferencia entre las dos versiones de la herramienta
```

```{admonition} Referencia
:class: seealso
Pueden ver más información sobre este tema en este [link](https://www.atlassian.com/migration/assess/compare-cloud-data-center)
```
