## Glosario

Algunos términos son nuevos y quizás no estés familiarizado con ellos. ¡Usa este glosario para no perderte!

| Término | Descripción |
| --- | --- |
| PDV | Punto de venta.|
| Integrador | Persona o entidad que quiere procesar un pago por medio de nuestra API.|
| Intención de pago | Contiene los detalles de la transacción.|
| Access token | Llave privada con la cual podrás generar cobros. Debes usarla para identificarte en tus integraciones. Es muy importante que estos datos estén protegidos en tus servidores y no sean accesibles por ningún usuario o atacante. |
| Webhook | Es una notificación que se envía desde nuestro servidor al del integrador mediante una llamada HTTP POST en relación a tus transacciones. |
| Poi | Serial del dispositivo. Lo puedes ver en la parte posterior de tu dispositivo (SN, NS). |
| Poi Type | Tipo de dispositivo. |

## Posibles estados de una intención de pago

| Término | Descripción |
| --- | --- |
| Open | Estado inicial de una intención de pago al crearlo desde el PDV |
| On Terminal | Estado intermedio de una intención de pago al momento de obtenerla desde el dispositivo Point |
| Processing | Estado intermedio de una intención de pago al momento de conciliar con una entidad financiera |
| Processed | Estado intermedio de una intención de pago al momento de finalizar la conciliación con una entidad financiera |
| Canceled | Estado final de una intención de pago cuando se cancela |
| Abandoned | Estado final de una intención de pago cuando no se procesa después de determinado tiempo |
| Error | Estado final de una intención de pago cuando ocurre un error en la transacción |
| Finished | Estado final de una intención de pago cuando finaliza la transacción |
