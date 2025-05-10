# 2.2. ¿Qué es un Sitio Atlassian?

<span class="badge badge-organization">Organization</span>

En términos sencillos, un **Sitio Atlassian** es una instancia específica de los productos Atlassian Cloud bajo tu Organización[^1]. Piensa en él como la instalación de software para tu equipo o empresa en la nube de Atlassian. Es el entorno operativo donde tus aplicaciones como Jira Software, Jira Service Management, Confluence, etc., están instaladas y funcionando[^2].

## Identificación Única: La URL del Sitio

Cada Sitio Atlassian tiene una dirección web única (URL). Cuando creas un nuevo sitio o te registras en un producto por primera vez, se te pide que elijas un nombre para tu sitio. Este nombre formará parte de la URL que usas para acceder a él, típicamente siguiendo el formato `https://<nombre_de_tu_sitio>.atlassian.net`. Esta URL es la puerta de entrada a tu instancia específica de Atlassian Cloud [Mencionado en conversación previa y soportado implícitamente por el contexto de URL de acceso en fuentes como 113, 119].

## Ubicación en la Jerarquía: Dentro de la Organización

Como vimos en la introducción general, el Sitio no existe de forma aislada. Un Sitio siempre está asociado y reside bajo una **Organización Atlassian**[^1]. Una sola Organización puede tener uno o más Sitios bajo su control[^5]. Es importante entender que esta estructura de Organización y Sitio es fundamental en el modelo de Atlassian Cloud y, según Atlassian, no va a desaparecer [^89, Mencionado en conversación previa].

## ¿Qué Contiene Tu Sitio? Productos y Usuarios

Dentro de un Sitio Atlassian, encontrarás:

* **Instancias de Productos/Apps:** Es aquí donde instalas y utilizas las aplicaciones que tu equipo necesita[^2]. Puedes tener Jira Software, Confluence, Jira Service Management y otras apps del Marketplace funcionando dentro del mismo sitio[^2]. Las aplicaciones del Marketplace, por ejemplo, se gestionan y se activan para un sitio[^8].
* **Usuarios:** Las cuentas de usuario se gestionan a nivel de sitio para determinar quién tiene acceso a qué productos dentro de ese sitio[^4]. Un **Administrador de Sitio** tiene la capacidad de añadir o eliminar usuarios en cualquier momento[^4].
* **Configuraciones Específicas:** La configuración de tus proyectos, espacios, permisos a nivel de proyecto o espacio, flujos de trabajo, etc., todo reside dentro del Sitio.

## El Rol del Administrador de Sitio

El **Administrador de Sitio** es un rol crucial dentro de un Sitio Atlassian. Sus permisos y responsabilidades están limitados a ese sitio específico [Soportado implícitamente por el contraste con el Administrador de Organización en 1 y el ámbito de gestión de usuarios y productos a nivel de sitio en 110, 111]. Las tareas típicas de un Administrador de Sitio incluyen:

* Invitar y gestionar usuarios para ese sitio[^4].
* Asignar licencias de productos a los usuarios en ese sitio[^4].
* Instalar, configurar y gestionar las aplicaciones y productos instalados en ese sitio[^8].
* Configurar aspectos funcionales de las aplicaciones (proyectos, espacios, permisos internos, etc.).

Mientras que el **Administrador de Organización** tiene una vista global de todos los sitios bajo la organización[^11], el Administrador de Sitio se enfoca en la operación diaria y la configuración de una instancia específica del producto[^4]. Se accede a la administración a nivel de sitio, por ejemplo, para gestionar usuarios o revisar el uso actual desde el panel de Administración de tu sitio[^10].

## Sitios y el Licenciamiento (Especialmente en Cloud)

El concepto de Sitio está intrínsecamente ligado al licenciamiento en Atlassian Cloud. El modelo de Atlassian se basa en **usuarios designados**, lo que significa que cada cuenta con permiso para iniciar sesión consume una licencia[^4]. Para las suscripciones de Cloud que se renuevan mensualmente, el precio se basa en el número exacto de usuarios con licencia[^4]. Esto significa que cualquier cambio en el número de usuarios realizado por un Administrador de Sitio afectará directamente el precio de la próxima renovación[^4]. Para las suscripciones anuales, el precio se basa en niveles de usuario, ofreciendo flexibilidad dentro de un umbral, pero el número total de usuarios licenciados en ese sitio (o en la organización para la facturación agrupada) sigue siendo el factor determinante[^4].

## Sitios y Facturación: Una Relación en Evolución

Históricamente, la facturación de las suscripciones de Cloud estaba muy ligada al Sitio, facturándose sitio por sitio[^13]. La gestión de facturación para la experiencia "original" se realizaba a menudo a través de `my.atlassian.com`, donde los contactos técnicos y de facturación designados podían ver y pagar facturas o gestionar la información de pago asociada a un sitio[^16].

Con la introducción del nuevo motor de facturación mejorado, la facturación se traslada a una estructura de **Cuenta de Facturación**, que permite agrupar varios sitios bajo una sola cuenta de facturación para simplificar la gestión y el pago[^5]. Aunque la estructura de pago ha cambiado para ofrecer más flexibilidad[^14], los sitios siguen siendo las instancias donde residen las suscripciones de productos de Cloud[^15]. La gestión del método de pago para las suscripciones bajo el nuevo motor de facturación se realiza ahora a través de `admin.atlassian.com/billing`, seleccionando la cuenta de facturación (que puede contener múltiples sitios)[^18].

## Otras Particularidades del Sitio

* **Pruebas Gratuitas:** Las versiones de prueba de los productos Cloud se asocian a un sitio específico[^20].
* **Ubicación de Datos:** Aunque Atlassian gestiona activamente la ubicación de los datos para optimizar el rendimiento, para organizaciones con productos Enterprise, los administradores de organización pueden fijar el contenido del producto en reposo a un dominio[^21]. Esto contrasta fuertemente con los productos Data Center, donde el cliente autogestiona el alojamiento y, por lo tanto, la ubicación de los datos[^22].

## Resumen

En resumen, el **Sitio Atlassian** es tu entorno de trabajo real en la nube, el lugar donde tus equipos interactúan con las aplicaciones, donde se gestionan los usuarios que acceden a esas herramientas, y cuya existencia e historial está fuertemente ligada a la facturación, aunque el modelo de pago se esté centralizando a nivel de cuenta de facturación en la nueva experiencia. Es un componente esencial para entender cómo se organiza el acceso y el uso de las herramientas de Atlassian en el entorno Cloud.

---

Notas
[^1]: Un Sitio Atlassian es una instancia específica de los productos Atlassian Cloud bajo tu Organización. Un Sitio siempre está asociado y reside bajo una Organización Atlassian.
[^2]: Es el entorno operativo donde tus aplicaciones como Jira Software, Jira Service Management, Confluence, etc., están instaladas y funcionando. Es aquí donde instalas y utilizas las aplicaciones que tu equipo necesita. Puedes tener Jira Software, Confluence, Jira Service Management y otras apps del Marketplace funcionando dentro del mismo sitio.
[^4]: Las cuentas de usuario se gestionan a nivel de sitio para determinar quién tiene acceso a qué productos dentro de ese sitio. Un Administrador de Sitio tiene la capacidad de añadir o eliminar usuarios en cualquier momento. El modelo de Atlassian se basa en usuarios designados, lo que significa que cada cuenta con permiso para iniciar sesión consume una licencia. Para las suscripciones de Cloud que se renuevan mensualmente, el precio se basa en el número exacto de usuarios con licencia. Cualquier cambio en el número de usuarios realizado por un Administrador de Sitio afectará directamente el precio de la próxima renovación. Para las suscripciones anuales, el precio se basa en niveles de usuario, ofreciendo flexibilidad dentro de un umbral, pero el número total de usuarios licenciados en ese sitio (o en la organización para la facturación agrupada) sigue siendo el factor determinante.
[^5]: Una sola Organización puede tener uno o más Sitios bajo su control. La facturación se traslada a una estructura de Cuenta de Facturación, que permite agrupar varios sitios bajo una sola cuenta de facturación para simplificar la gestión y el pago.
[^8]: Las aplicaciones del Marketplace, por ejemplo, se gestionan y se activan para un sitio. Instalar, configurar y gestionar las aplicaciones y productos instalados en ese sitio.
[^10]: Se accede a la administración a nivel de sitio, por ejemplo, para gestionar usuarios o revisar el uso actual desde el panel de Administración de tu sitio.
[^11]: Mientras que el Administrador de Organización tiene una vista global de todos los sitios bajo la organización.
[^13]: Históricamente, la facturación de las suscripciones de Cloud estaba muy ligada al Sitio, facturándose sitio por sitio.
[^14]: Aunque la estructura de pago ha cambiado para ofrecer más flexibilidad.
[^15]: Los sitios siguen siendo las instancias donde residen las suscripciones de productos de Cloud.
[^16]: La gestión de facturación para la experiencia "original" se realizaba a menudo a través de my.atlassian.com, donde los contactos técnicos y de facturación designados podían ver y pagar facturas o gestionar la información de pago asociada a un sitio.
[^18]: La gestión del método de pago para las suscripciones bajo el nuevo motor de facturación se realiza ahora a través de admin.atlassian.com/billing, seleccionando la cuenta de facturación (que puede contener múltiples sitios).
[^20]: Las versiones de prueba de los productos Cloud se asocian a un sitio específico.
[^21]: Aunque Atlassian gestiona activamente la ubicación de los datos para optimizar el rendimiento, para organizaciones con productos Enterprise, los administradores de organización pueden fijar el contenido del producto en reposo a un dominio.
[^22]: Esto contrasta fuertemente con los productos Data Center, donde el cliente autogestiona el alojamiento y, por lo tanto, la ubicación de los datos.
[^89]: La estructura de Organización y Sitio es fundamental en el modelo de Atlassian Cloud y, según Atlassian, no va a desaparecer.
