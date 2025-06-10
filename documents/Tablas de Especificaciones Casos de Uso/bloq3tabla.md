## CASOS DE USO  

### Bloque 3: Envío de comandas  

| Campo                     | Detalle                                                                 |
|---------------------------|-------------------------------------------------------------------------|
| **Num Versión**           | 1.0                                                                     |
| **Fecha**                 | 09/04/2025                                                              |
| **Autores**               | Yang Chen, Liying Sun, Daniel Alberto Vaca Davalos, Nour Kobbi          |
| **Descripción**           | En este caso de uso se muestra cómo el cliente interactúa con las distintas opciones de envío del pedido. |
| **Actores**               | Cliente, Cocinero                                                       |
| **Precondición**          | El cliente debe haber confirmado un pedido, es decir que va a comer.     |
| **Flujo Principal**       | 1. El cliente accede a la aplicación y selecciona el tipo de entrega del pedido.<br>2. El sistema muestra las opciones disponibles:<br>   • **a.** Repartidor externo<br>   • **b.** Entrega por parte del cocinero<br>   • **c.** Recogida en casa del cocinero<br>3. El cliente selecciona una opción.<br>4. El sistema calcula el costo del envío (si aplica) y lo muestra al cliente.<br>5. El cliente confirma la opción de entrega.<br>6. El sistema registra la elección y actualiza el pedido. |
| **Subflujos**             | **Entrega por repartidor**:<br>7. El sistema inicia el proceso de envío y asigna un repartidor.<br>8. Se calcula el costo de envío en base a la distancia entre el cocinero y el cliente.<br>9. El sistema proporciona un enlace de seguimiento generado a través de Google Maps.<br>10. El cliente puede consultar el estado del envío en tiempo real.<br><br>**Entrega por cocinero**:<br>7. El cocinero accede a la aplicación y acepta realizar la entrega personalmente.<br>8. El sistema asigna el pedido al cocinero como repartidor.<br>9. Se calcula el costo del envío en función de la distancia, si aplica.<br>10. El cliente puede consultar el estado del pedido y su ubicación si el cocinero ha activado el seguimiento.<br><br>**Recogida en casa del cocinero**:<br>7. El cliente elige recoger el pedido en casa del cocinero.<br>8. El sistema marca el envío como gratuito.<br>9. Se informa al cocinero de la elección y se notifica cuándo el cliente puede venir a recoger el pedido.<br>10. No se genera ningún enlace de seguimiento. |
| **Flujos Alternativos**   | N/A                                                                     |
| **Postcondición**         | El pedido es entregado o recogido por el cliente según la opción seleccionada. |
| **Requisitos no Funcionales** | RNF-3-01: Integración con Google Maps para visualizar la posición del repartidor en tiempo real. |
| **Prioridad**             | Normal                                                                  |
| **Comentarios**           | N/A                                                                     |
