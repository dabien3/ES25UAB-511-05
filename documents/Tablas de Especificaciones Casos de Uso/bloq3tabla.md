## CASOS DE USO

### Bloque 3: Envío de comandas

| Campo                     | Detalle                                                                 |
|---------------------------|-------------------------------------------------------------------------|
| **Num Versión**           | 1.0                                                                     |
| **Fecha**                 | 09/04/2025                                                              |
| **Autores**               | Yang Chen, Liying Sun, Daniel Alberto Vaca Davalos, Nour Kobbi          |
| **Descripción**           | En este caso de uso se muestra cómo el cliente interactúa con las distintas opciones de envío del pedido. |
| **Actores**               | Cliente, Cocinero, Repartidor                                           |
| **Precondición**          | El cliente debe haber confirmado un pedido.                             |
| **Flujo Principal**       | 1. El cliente y el cocinero pueden seleccionar el tipo de entrega (repartidor, cocinero, o recogida en casa del cocinero). <br> 2. El cliente puede visualizar el costo de envío en función de la distancia entre él y el cocinero. Si escoge recogida, se indica que el envío es gratuito. <br> 3. Una vez iniciado el envío, el cliente puede seguir el estado del pedido en tiempo real. <br> 4. El cliente puede ver la ubicación del repartidor en un mapa. |
| **Subflujos**             | N/A                                                                     |
| **Flujos Alternativos**   | N/A                                                                     |
| **Postcondición**         | El pedido es entregado o recogido por el cliente según la opción seleccionada. |
| **Requisitos no Funcionales** | - RNF-3-01: Integración con Google Maps para visualizar la posición del repartidor en tiempo real. |
| **Prioridad**             | Alta                                                                    |
| **Comentarios**           | N/A                                                                     |
