# 2.1 Atlassian Cloud vs Data Center

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

| Característica            | Atlassian Cloud            | Atlassian Data Center     |
|--------------------------|----------------------------|----------------------------|
| Hosting                  | Gestionado por Atlassian   | Autogestionado             |
| Mantenimiento            | Automático                 | Requiere administración    |
| Escalabilidad            | Automática                 | Manual (más compleja)      |
| Personalización profunda | Limitada                   | Avanzada                   |
| Control de datos         | Bajo (en la nube)          | Total                      |
| Ideal para               | Equipos pequeños a medianos| Empresas grandes o reguladas|

---

> 💡 **En resumen:** Si buscás simplicidad, velocidad de implementación y bajo mantenimiento, **Cloud** es la mejor opción. Si necesitás control absoluto, cumplimiento normativo o una arquitectura distribuida, **Data Center** es el camino.

---

¿Querés que preparemos también una tabla rápida para ayudarte a elegir según tu contexto organizacional?

---