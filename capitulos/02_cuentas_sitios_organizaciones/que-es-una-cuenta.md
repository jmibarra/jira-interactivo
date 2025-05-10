# 2.3. ¿Qué es una cuenta?

<span class="badge badge-organization">Organization</span>

Hemos explorado la Organización, el "paraguas" global, y el Sitio, el espacio de trabajo concreto. Ahora, enfoquémonos en el actor principal dentro de estas estructuras: el usuario y su **Cuenta Atlassian**. Tu Cuenta Atlassian es tu identidad personal en el ecosistema Atlassian, tu llave para acceder a los Sitios y utilizar los productos.

## ¿Qué es una Cuenta Atlassian (Atlassian Account)?

Una **Cuenta Atlassian** es tu perfil de usuario individual. Es lo que te permite iniciar sesión en los productos Atlassian Cloud, gestionar ciertos aspectos de tus suscripciones (si tienes los permisos adecuados) y acceder a recursos como la documentación, la comunidad o tu área personal (`my.atlassian.com` en la experiencia original o `admin.atlassian.com/billing` y `id.atlassian.com` en la experiencia mejorada o para la gestión de perfil)[^1].

Tu Cuenta Atlassian está ligada a una **dirección de correo electrónico única**[^1]. Esta dirección de correo electrónico sirve como tu nombre de usuario para iniciar sesión[^1].

## La Cuenta Atlassian y el ID de Atlassian (Atlassian ID)

La base técnica detrás de tu Cuenta Atlassian es el **Atlassian ID (AAID)**[^8]. Piensa en el Atlassian ID como la identificación única y centralizada que Atlassian utiliza para reconocerte en sus diferentes servicios y productos. Cuando gestionas tu perfil, cambias tu correo electrónico o restableces tu contraseña, a menudo lo haces a través de `id.atlassian.com`, la plataforma de gestión de tu Atlassian ID[^1].

## Acceso a Productos y Sitios

Para utilizar productos como Jira Software o Confluence en un Sitio Atlassian, necesitas tener una Cuenta Atlassian y que esta cuenta haya sido **añadida al Sitio específico**[^9]. Una vez añadido, el administrador del Sitio o un administrador de facturación (dependiendo de la experiencia de facturación) te asignará acceso a los productos específicos instalados en ese sitio[^5].

## Cuentas y Licenciamiento: El Modelo de Usuario Designado

Este es un concepto fundamental en Atlassian Cloud (y Data Center): el licenciamiento se basa en **Usuarios Designados (Designated Users)**[^11]. Esto significa que:

* Cada cuenta de usuario a la que se le otorga permiso para iniciar sesión en una aplicación cuenta como un usuario designado, independientemente de si ha iniciado sesión activamente o no[^11].
* El modelo de licenciamiento no se basa en usuarios concurrentes (es decir, cuántas personas usan la aplicación al mismo tiempo)[^11].
* Cada inicio de sesión del producto solo puede asignarse a un individuo, una persona designada[^11].
* Varias personas no pueden compartir un inicio de sesión en un producto[^11].

El número total de usuarios designados licenciados en un Sitio es lo que determina el coste de la suscripción, especialmente para los planes mensuales[^10]. Los administradores de sitio pueden añadir o eliminar usuarios en cualquier momento, y estos cambios afectan el precio de la renovación[^10]. Para suscripciones anuales, el precio se basa en niveles de usuario, permitiendo flexibilidad dentro de un umbral, pero el número total de usuarios licenciados sigue siendo el factor clave para el nivel[^12].

## Roles Asociados a la Cuenta de Usuario

Más allá de ser un usuario estándar de un producto, una Cuenta Atlassian puede tener roles administrativos importantes:

* **Administrador de Sitio:** Una Cuenta Atlassian con este rol tiene permisos para gestionar usuarios dentro de ese sitio específico, asignarles productos, configurar aspectos de las aplicaciones (proyectos, espacios), etc[^9]. Un administrador de sitio puede incluso convertirse en contacto de facturación en la experiencia original[^13].
* **Contacto Técnico/de Facturación (Experiencia Original):** Cuentas Atlassian con estos roles designados en `my.atlassian.com` podían ver y pagar facturas, añadir otros contactos, generar solicitudes de soporte y gestionar licencias de prueba[^3]. Eran considerados "propietarios del producto" con autoridad para solicitar cambios en la licencia[^4].
* **Administrador de Facturación (Experiencia Mejorada):** Este es un rol nuevo que reemplaza a los contactos técnico y de facturación en el nuevo motor de facturación[^16]. Una Cuenta Atlassian con este rol tiene permisos de "superusuario" para todas las tareas relacionadas con la facturación y el cobro asociadas a una o más Cuentas de Facturación[^5]. Pueden gestionar datos de pago, pagar facturas, añadir/eliminar otros administradores de facturación y contactos empresariales, y gestionar (con ciertas limitaciones para Enterprise) planes y suscripciones[^5]. Un mismo usuario puede ser administrador de facturación de varias Cuentas de Facturación[^5]. Se recomienda tener al menos dos administradores de facturación por Cuenta de Facturación para asegurar el acceso[^19].

## Tu Cuenta Atlassian como Centro de Gestión (Según la Experiencia de Facturación)

La Cuenta Atlassian es la puerta de acceso a las interfaces de gestión:

* **`my.atlassian.com`:** El portal para la experiencia de facturación original[^1]. Aquí, los contactos designados gestionaban licencias, veían pedidos/facturas y actualizaban la información de pago asociada a los Sitios individuales[^3].
* **`admin.atlassian.com/billing`:** El portal centralizado para la experiencia de facturación mejorada[^4]. Aquí, los administradores de facturación gestionan todo lo relacionado con la facturación a nivel de la Cuenta de Facturación (que puede agrupar varios Sitios)[^4].

## Privacidad y tus Datos Personales

Tu Cuenta Atlassian contiene datos personales que Atlassian procesa para proveer sus servicios[^47]. Tienes derechos sobre tu información y, en algunos casos, puedes controlar qué datos se recopilan o comparten, dependiendo de tu ubicación, los productos que usas y su configuración[^48]. Atlassian se compromete a proteger estos datos y cumplir con normativas como GDPR, LGPD y CCPA[^50].

## Resumen

En resumen, tu **Cuenta Atlassian** es tu identidad digital personal en el universo Atlassian. Te permite acceder a los Sitios y productos, determina (a través del modelo de usuario designado) la base del licenciamiento, y, si tienes roles administrativos, te permite gestionar aspectos clave de las suscripciones y la facturación a través de los portales correspondientes. Entender que tu acceso y los permisos están ligados a esta cuenta individual es crucial para navegar el ecosistema Atlassian.

---

Notas
[^1]: Tu Cuenta Atlassian es tu perfil de usuario individual. Te permite iniciar sesión en los productos Atlassian Cloud, gestionar ciertos aspectos de tus suscripciones y acceder a recursos como la documentación, la comunidad o tu área personal (`my.atlassian.com` o `admin.atlassian.com/billing` y `id.atlassian.com`). Tu Cuenta Atlassian está ligada a una dirección de correo electrónico única, que sirve como tu nombre de usuario para iniciar sesión.
[^3]: Cuentas Atlassian con los roles de Contacto Técnico/de Facturación en `my.atlassian.com` podían ver y pagar facturas, añadir otros contactos, generar solicitudes de soporte y gestionar licencias de prueba.
[^4]: El portal centralizado para la experiencia de facturación mejorada es `admin.atlassian.com/billing`. Tu Cuenta Atlassian contiene datos personales que Atlassian procesa para proveer sus servicios.
[^5]: El administrador de facturación tiene permisos de "superusuario" para todas las tareas relacionadas con la facturación y el cobro asociadas a una o más Cuentas de Facturación. Pueden gestionar datos de pago, pagar facturas, añadir/eliminar otros administradores de facturación y contactos empresariales, y gestionar planes y suscripciones. Un mismo usuario puede ser administrador de facturación de varias Cuentas de Facturación.
[^8]: La base técnica detrás de tu Cuenta Atlassian es el Atlassian ID (AAID).
[^9]: Para utilizar productos en un Sitio Atlassian, necesitas tener una Cuenta Atlassian y que esta cuenta haya sido añadida al Sitio específico. Una Cuenta Atlassian con el rol de Administrador de Sitio tiene permisos para gestionar usuarios dentro de ese sitio específico, asignarles productos, configurar aspectos de las aplicaciones, etc.
[^10]: El número total de usuarios designados licenciados en un Sitio determina el coste de la suscripción, especialmente para los planes mensuales. Los administradores de sitio pueden añadir o eliminar usuarios en cualquier momento, y estos cambios afectan el precio de la renovación.
[^11]: El licenciamiento se basa en Usuarios Designados (Designated Users). Cada cuenta de usuario con permiso para iniciar sesión cuenta como un usuario designado, independientemente de si ha iniciado sesión activamente o no. El modelo no se basa en usuarios concurrentes. Cada inicio de sesión del producto solo puede asignarse a un individuo, y varias personas no pueden compartir un inicio de sesión.
[^12]: Para suscripciones anuales, el precio se basa en niveles de usuario, permitiendo flexibilidad dentro de un umbral, pero el número total de usuarios licenciados sigue siendo el factor clave para el nivel.
[^13]: Un administrador de sitio puede incluso convertirse en contacto de facturación en la experiencia original.
[^16]: El rol de Administrador de Facturación reemplaza a los contactos técnico y de facturación en el nuevo motor de facturación.
[^19]: Se recomienda tener al menos dos administradores de facturación por Cuenta de Facturación para asegurar el acceso.
[^47]: Tu Cuenta Atlassian contiene datos personales que Atlassian procesa para proveer sus servicios.
[^48]: Tienes derechos sobre tu información y, en algunos casos, puedes controlar qué datos se recopilan o comparten, dependiendo de tu ubicación, los productos que usas y su configuración.
[^50]: Atlassian se compromete a proteger estos datos y cumplir con normativas como GDPR, LGPD y CCPA.