# Notificaciones

Las notificaciones son mensajes enviados por el servidor de Mercado Pago de eventos que se realizan en su aplicación. Puede configurar su integración para enviar notificaciones cuando ocurran los siguientes eventos:

* Creación de pagos
* Actualización de pago
* Creación de pedidos
* Actualización de la orden
* Vinculación a un plan de suscripción
* Enlace de suscripción
* Vinculación de cuentas mp-connect
* Desvincular cuentas mp-connect
* Vinculación de facturas (factura)
* Creación de contracargos

Hay **dos tipos** de notificaciones disponibles para la configuración, que una vez configuradas, le permiten programar el backend de su tienda para, por ejemplo, actualizar el estado de los pedidos cuando se crea un pago, enviar un correo electrónico de confirmación del pedido desde la tienda cuando un el pedido se actualiza en Mercado Pago, actualizando el registro de un cliente cuando se vincula un plan de suscripción, o cualquier otra acción derivada de los eventos enumerados anteriormente.


| Tipo | Descripción |
| --- | --- |
| **Webhooks** | Utiliza HTTP REST y notifica instantáneamente las actualizaciones. Para aprender a configurar las notificaciones de webhook [haz clic aquí](https://www.mercadopago[FAKER][URL][DOMAIN]/developers/es/guides/notifications/webhooks). |
| **IPN** | La notificación puede tardar unos minutos en enviarse. Para aprender a configurar las notificaciones IPN [haz clic aquí](https://www.mercadopago[FAKER][URL][DOMAIN]/developers/es/guides/notifications/ipn). |