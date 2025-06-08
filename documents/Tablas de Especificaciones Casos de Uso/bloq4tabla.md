## CASOS DE USO

### Bloque 4: Pago de la comanda

| Campo                     | Detalle                                                                 |
|---------------------------|-------------------------------------------------------------------------|
| **Num Versión**           | 1.0                                                                     |
| **Fecha**                 | 09/04/2025                                                              |
| **Autores**               | Yang Chen, Liying Sun, Daniel Alberto Vaca Davalos, Nour Kobbi Laghmich |
| **Descripción**           | Este caso de uso describe cómo se realiza el proceso de pago de una comanda desde la aplicación, así como el reparto del ingreso correspondiente al cocinero y al repartidor. |
| **Actores**               | Cliente, Cocinero, Repartidor                                           |
| **Precondición**          | N/A                                                                     |
| **Flujo Principal**       | 1. El cliente accede al apartado de pago desde la aplicación. <br> 2. Selecciona un método de pago: tarjeta bancaria o PayPal. <br> 3. La aplicación conecta con la plataforma correspondiente para procesar el pago. <br> 4. Una vez realizado el pago, se efectúa el ingreso al cocinero y al repartidor usando sus cuentas bancarias asociadas. |
| **Subflujos**             | 1. El sistema redirige al cliente al entorno seguro de la plataforma de pago seleccionada. Se requiere autenticación válida para completar la transacción económica. <br> 2. El sistema usa los datos bancarios de los perfiles para repartir el dinero automáticamente. |
| **Flujos Alternativos**   | N/A                                                                     |
| **Postcondición**         | N/A                                                                     |
| **Requisitos no Funcionales** | - RNF-4-01: El sistema debe conectarse con la plataforma de pago correspondiente para autenticar la transacción. |
| **Prioridad**             | Alta                                                                    |
| **Comentarios**           | N/A                                                                     |
