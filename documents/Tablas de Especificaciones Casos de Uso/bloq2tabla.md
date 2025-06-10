## CASOS DE USO

### Bloque 2: Realización de comandas

| Campo                     | Detalle                                                                 |
|---------------------------|-------------------------------------------------------------------------|
| **Num Versión**           | 1.0                                                                     |
| **Fecha**                 | 09/04/2025                                                              |
| **Autores**               | Yang Chen, Liying Sun, Daniel Alberto Vaca Davalos, Nour Kobbi          |
| **Descripción**           | En este caso de uso se representa cómo los clientes realizan comandas, desde la visualización de platos hasta la confirmación del pedido. |
| **Actores**               | Cliente                                                                 |
| **Precondición**          | El cliente debe estar registrado para realizar pedidos.                 |
| **Flujo Principal**       | 1. El cliente puede consultar los ingredientes y alérgenos de los platos, y en caso de necesario, eliminar ingredientes opcionales de los platos <br> 2. El cliente puede ver platos según sus restricciones alimentarias. <br> 3. El cliente puede consultar los platos ofrecidos por un cocinero. <br> 4. El cliente puede ver la disponibilidad de un cocinero. <br> 5. El cliente puede buscar platos o cocineros específicos. <br> 6. El cliente puede ver el tiempo estimado de entrega. <br> 7. El cliente puede confirmar y cerrar el pedido. <br> 8. El cliente puede repetir un pedido anterior. <br> 9. El cliente puede consultar su historial de pedidos. |
| **Subflujos**             | N/A                                                                     |
| **Flujos Alternativos**   | N/A                                                                     |
| **Postcondición**         | El pedido queda confirmado o reservado.                                 |
| **Requisitos no Funcionales** | - RNF-2-01: El sistema debe mostrar resultados priorizados según distancia y restricciones alimentarias de manera eficiente. <br> - RNF-2-02: El sistema debe limitar a tres los pedidos activos por cliente. |
| **Prioridad**             | Alta                                                                    |
| **Comentarios**           | Este módulo depende de la correcta configuración del perfil del cliente y de la disponibilidad de los cocineros. |
