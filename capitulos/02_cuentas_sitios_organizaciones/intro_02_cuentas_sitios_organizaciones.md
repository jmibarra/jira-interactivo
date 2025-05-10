# Capítulo 2: Cuentas, Sitios y Organizaciones Atlassian

<span class="badge badge-organization">Organization</span>

Para comprender cómo funcionan las herramientas de Atlassian, especialmente en el entorno Cloud, es esencial familiarizarse con su estructura fundamental. Esta estructura se basa en varios conceptos clave que interactúan entre sí para definir cómo se gestionan los usuarios, los productos y la facturación. Los pilares de este sistema son las **Cuentas de usuario Atlassian**, los **Sitios Atlassian**, las **Organizaciones Atlassian** y, más recientemente, las **Cuentas de Facturación**. Entender la relación entre estos elementos es crucial para una administración eficiente y segura.

## La Jerarquía Atlassian Cloud

En el nivel más alto de la jerarquía se encuentra la **Organización Atlassian**. La Organización sirve como un lugar centralizado para gestionar tus productos y usuarios[^1]. Es donde reside la configuración de administración a nivel de toda la empresa[^2]. La estructura de Organización y Sitio es fundamental y no va a desaparecer[^3].

Dentro de una Organización, puedes tener uno o más **Sitios**[^3]. Un Sitio es una instancia específica de Atlassian Cloud, a menudo identificada por una URL como `miempresa.atlassian.net`[^4], y contiene las instalaciones de los productos o "apps" que utilizas, como Jira, Jira Service Management, Confluence, etc.[^3]. Históricamente, la facturación estaba muy ligada a cada sitio[^6].

## Gestión de Usuarios y Licencias

La gestión de quién puede acceder a estos sitios y productos recae en las **Cuentas de usuario Atlassian**. Cada individuo que necesita usar un producto Atlassian dentro de tu organización tiene una cuenta única[^7]. Estas cuentas se gestionan a diferentes niveles: a nivel de toda la organización por los **Administradores de Organización**[^2] y a nivel de sitio por los **Administradores de Sitio**[^4].

El modelo de licenciamiento de Atlassian se basa en **usuarios designados**, lo que significa que cada cuenta con permiso para iniciar sesión consume una licencia, independientemente de si está activa en un momento dado o no[^7]. Esto tiene un impacto directo en el coste, especialmente para los productos Cloud con facturación mensual, donde el precio se basa en el número exacto de usuarios con licencia[^9].

## Roles Administrativos

Dentro de esta estructura, existen diferentes roles administrativos con alcances específicos[^10]:

* **Administrador de Organización:** Tiene el nivel máximo (global) y permisos totales sobre todos los sitios, productos y usuarios registrados bajo la organización[^2].
* **Administrador de Sitio:** Tiene control total sobre los usuarios y productos de un sitio específico únicamente[^4].

Es importante destacar que tanto los Administradores de Organización como los Administradores de Sitio, al tener un nivel de acceso elevado, consumen licencias de todas las apps instaladas en su ámbito de administración[^11].

## Gestión de Facturación

La gestión financiera de las suscripciones ha evolucionado con la introducción de un nuevo motor de facturación en la nube[^12]. Este nuevo sistema introduce el concepto de **Cuenta de Facturación**[^6]. Una Cuenta de Facturación es una estructura para agrupar y organizar todas las actividades de cobro y facturación con Atlassian[^6]. Permite agrupar sitios bajo una sola cuenta de facturación, ofreciendo más flexibilidad en la gestión y el pago, alejándose del modelo estricto de facturación sitio por sitio[^3].

La responsabilidad principal de esta nueva estructura recae en el rol de **Administrador de Facturación**[^14]. Los Administradores de Facturación tienen acceso a todas las tareas relacionadas con la facturación y los pagos para una cuenta de facturación específica[^16].

## Resumen

En resumen, la **Organización** actúa como el contenedor principal y punto de gobernanza global, dentro de la cual existen **Sitios** que albergan las instancias de los Productos/Apps. El acceso a estos productos está controlado por las **Cuentas de usuario**, cuyo número impacta directamente en el **Licenciamiento** y coste (especialmente en Cloud). La gestión financiera de estas suscripciones se centraliza ahora más flexiblemente a través de las **Cuentas de Facturación**, supervisadas por los **Administradores de Facturación**. Comprender cómo estos elementos se entrelazan es el primer paso para dominar la administración de tu instancia Atlassian.

---

Notas

[^1]: La Organización sirve como un lugar centralizado para gestionar tus productos y usuarios.
[^2]: Es donde reside la configuración de administración a nivel de toda la empresa.
[^3]: La estructura de Organización y Sitio es fundamental y no va a desaparecer. Dentro de una Organización, puedes tener uno o más Sitios. Un Sitio contiene las instalaciones de los productos o "apps" que utilizas. La facturación se está alejando del modelo estricto de sitio por sitio.
[^4]: Un Sitio es una instancia específica de Atlassian Cloud, a menudo identificada por una URL como miempresa.atlassian.net. El Administrador de Sitio tiene control total sobre los usuarios y productos de un sitio específico únicamente.
[^6]: Históricamente, la facturación estaba muy ligada a cada sitio. Este nuevo sistema introduce el concepto de Cuenta de Facturación. Una Cuenta de Facturación es una estructura para agrupar y organizar todas las actividades de cobro y facturación con Atlassian.
[^7]: Cada individuo que necesita usar un producto Atlassian dentro de tu organización tiene una cuenta única. El modelo de licenciamiento de Atlassian se basa en usuarios designados, lo que significa que cada cuenta con permiso para iniciar sesión consume una licencia.
[^9]: Esto tiene un impacto directo en el coste, especialmente para los productos Cloud con facturación mensual, donde el precio se basa en el número exacto de usuarios con licencia.
[^10]: Dentro de esta estructura, existen diferentes roles administrativos con alcances específicos.
[^11]: Tanto los Administradores de Organización como los Administradores de Sitio, al tener un nivel de acceso elevado, consumen licencias de todas las apps instaladas en su ámbito de administración.
[^12]: La gestión financiera de las suscripciones ha evolucionado con la introducción de un nuevo motor de facturación en la nube.
[^14]: La responsabilidad principal de esta nueva estructura recae en el rol de Administrador de Facturación.
[^16]: Los Administradores de Facturación tienen acceso a todas las tareas relacionadas con la facturación y los pagos para una cuenta de facturación específica.