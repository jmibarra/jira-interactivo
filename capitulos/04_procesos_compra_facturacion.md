# Capítulo 4: Comprendiendo la Compra y Facturación de Productos Atlassian

<span class="badge badge-organization">Organization</span>

Atlassian ofrece una amplia gama de productos, incluyendo Jira, Confluence, Jira Service Management, Bitbucket, Trello, Guard, y muchos más. La forma de adquirir y gestionar la facturación de estos productos, especialmente en la nube, tiene varias particularidades importantes a tener en cuenta.

## Modelos de Licenciamiento y Planes

En **Atlassian Cloud**, los planes más comunes son **Free, Standard, Premium y Enterprise**, aunque la disponibilidad de cada plan puede variar según el producto. Por ejemplo, Jira Work Management solo ofrece planes Free y Standard, mientras que Confluence Cloud Enterprise solo está disponible con un contrato anual.

Los planes de Cloud se pueden facturar de forma **mensual o anual**.

## Facturación Mensual vs. Anual

El **ciclo de facturación mensual** generalmente se basa en los **usuarios activos con licencias** en el momento del ciclo de facturación. Históricamente, esto podía llevar a cierta confusión sobre cómo se facturaban los usuarios que se añadían o eliminaban a mitad de ciclo.

A partir de **octubre de 2025**, Atlassian implementará un **nuevo modelo de facturación mensual** basado en la **cantidad máxima de usuarios** que hayas tenido durante el período de facturación. Esto se aplicará a suscripciones mensuales de Compass, Confluence, Atlassian Guard, Jira, Jira Product Discovery, Jira Service Management, Loom y Aplicaciones del Marketplace. Si añades usuarios a mitad de ciclo con este nuevo modelo, se calcularán **cargos adicionales prorrateados** en tu siguiente factura. Tu siguiente factura reflejará tanto la renovación estándar para el nuevo número de usuarios como los cargos adicionales por el uso parcial del mes anterior. Este cambio **no afecta a las suscripciones anuales**.

El **ciclo de facturación anual** se paga por tramos de usuarios y por año. Un beneficio del pago anual es un posible **ahorro de dos meses** en comparación con la facturación mensual. Los precios contratados anualmente se mantienen fijos, incluso si Atlassian aumenta sus precios, hasta la renovación.

## Métodos de Pago Aceptados

Atlassian acepta una variedad de métodos de pago. Para las **suscripciones mensuales a Cloud**, los pagos deben realizarse exclusivamente con **tarjeta de crédito o PayPal**. Los pagos recurrentes se cargan al inicio de cada ciclo de facturación. No se aceptan tarjetas Discover para renovaciones mensuales.

Para las **suscripciones anuales a Cloud** y los pedidos de **Data Center**, se aceptan más métodos, incluyendo **tarjeta de crédito, transferencia bancaria/ACH, cheque, PayPal y términos de pago (Net 14 o Net 30)**. Las renovaciones automáticas anuales solo pueden pagarse con tarjeta de crédito o PayPal.

Los **términos de pago a 14 días (Net-14)** pueden estar disponibles para suscripciones anuales de Cloud dentro de ciertos rangos de precios (por ejemplo, entre 1000 y 50 000 USD antes de impuestos en el nuevo motor de facturación o entre 1000 y 20 000 USD en la documentación para distribuidores), sin requerir verificación de crédito.

Los **términos de pago a 30 días (Net-30)** generalmente requieren pedidos de un importe mayor (por ejemplo, 10 000 USD o más en el sistema antiguo o 50 000 USD o más en el nuevo motor de facturación tras verificación de crédito) y pueden requerir un número de identificación fiscal.

Atlassian está implementando un **nuevo motor de facturación** para Cloud que mejora la gestión de suscripciones y cambia cómo se procesan algunos pagos, como los términos de pago que requieren aceptar el presupuesto y recibir una factura antes de enviar el pago.

## Procesos de Compra y Obtención de Presupuestos

Puedes realizar compras o solicitar presupuestos directamente a través del sitio web de Atlassian o contactando a su equipo. Para obtener un presupuesto, necesitarás proporcionar detalles como tu información de contacto y la de tu cliente (si eres distribuidor), los productos deseados y los niveles de usuario.

Los **distribuidores no afiliados** pueden comprar en nombre de terceros pero **no reciben descuentos** a menos que sean distribuidores corporativos o Partners oficiales de Atlassian. Los distribuidores pueden comprar suscripciones anuales a Cloud y licencias de Data Center para sus clientes, pero **no pueden comprar suscripciones mensuales a Cloud** para ellos. Para acceder a la clave de licencia autogestionada de un cliente, debes ser el comprador original.

## Facturación de Atlassian Guard y Usuarios Externos

Inicialmente, puede haber confusión sobre la facturación de usuarios externos por Atlassian Guard. Aunque una respuesta sugería que no se cobra por usuarios externos no gestionados, otra información indica que **si activas el SSO (Inicio de Sesión Único) para usuarios externos, se te facturará por ellos** según el número de usuarios externos a los que se les aplique SSO. Si la política para usuarios externos se configura como "no facturable", solo se puede aplicar OTP (Contraseña de un solo uso). No importa si los usuarios externos son gestionados por otra organización o si tienen su propia licencia de Atlassian Guard. La otra organización no es relevante para el SSO de usuarios externos. **Solo se cobra por Cuentas Gestionadas (reclamadas) y usuarios externos a los que se les aplica SSO**.

Es importante destacar que los clientes de Jira Service Management que solo tienen acceso de cliente (y no una licencia de Jira o Confluence) están cubiertos por Guard pero **no son facturables**.

El SSO externo actúa como una segunda capa de autenticación. Después de iniciar sesión en su cuenta de Atlassian (que podría usar el SSO de su propia organización si está gestionada), los usuarios externos pasan por tu proveedor de identidad para autenticarse en tu sitio. No pagas por el simple hecho de que usuarios externos pasen por tu SSO.

## Facturación de Aplicaciones de Marketplace

El precio de las aplicaciones de Atlassian Marketplace se calcula en función del **total mayor de usuarios** en tu instancia. Por ejemplo, si tienes 32 agentes de Jira Service Management y 75 usuarios de Jira Software, las aplicaciones se facturarán para 75 usuarios. Algunas aplicaciones ofrecen planes gratuitos para instancias Cloud con menos de 10 usuarios.

## Consideraciones sobre Políticas de Seguridad y Facturación

Configurar políticas de seguridad y autenticación para usuarios en Atlassian Cloud, como la verificación en dos pasos, la seguridad y caducidad de contraseñas, o la duración de la sesión, requiere primero la **verificación del dominio**. Con Atlassian Access, puedes establecer políticas de autenticación diferentes por grupo de usuarios. Sin embargo, estas políticas se aplican a los usuarios con licencia de productos como Bitbucket, Confluence, Jira Work Management, Jira Software y Jira Service Management (solo para usuarios con cuentas de Atlassian con dominios verificados). **No se pueden crear políticas de autenticación para los usuarios *cliente* de un portal de Jira Service Management**; para ellos, solo hay un requisito de longitud de contraseña (entre 8 y 100 caracteres).

Aunque la base de conocimientos integrada en Jira Service Management está impulsada por Confluence, los agentes de Jira Service Management **no necesitan una licencia de Confluence** para crear, leer, actualizar y eliminar artículos básicos en ella. Sin embargo, un administrador debe añadir manualmente un plan de Confluence al sitio para habilitar esta funcionalidad. Los usuarios que necesiten acceso directo a Confluence o funciones avanzadas sí requerirán una licencia de Confluence. Esta función integrada **no está disponible en Jira Service Management Data Center**.

## Soporte y Ayuda con la Facturación

Para preguntas específicas sobre facturación, pagos o precios, se recomienda **contactar directamente con el Soporte de Atlassian**. También puedes buscar ayuda en la Comunidad de Atlassian o trabajar con Partners o distribuidores oficiales de Atlassian.

Comprender estos detalles te ayudará a navegar por los procesos de compra y facturación de Atlassian de manera más efectiva.