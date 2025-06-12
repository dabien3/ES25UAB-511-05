# CASOS DE USO

## Bloque 5: Valoración de la comanda

| Campo                     | Detalle                                                                 |
|---------------------------|-------------------------------------------------------------------------|
| **Num Versión**           | 1.0                                                                     |
| **Fecha**                 | 09/04/2025                                                              |
| **Autores**               | Yang Chen, Liying Sun, Daniel Alberto Vaca Davalos, Nour Kobbi Laghmich |
| **Descripción**           | Este caso de uso describe cómo el cliente puede valorar una comanda recibida, introduciendo puntuaciones sobre la puntualidad y el estado del plato. El sistema registra la valoración, la asocia al cocinero correspondiente y actualiza su posicionamiento. Además, el cliente puede consultar valoraciones de otros usuarios antes de realizar un pedido. |
| **Actores**               | Cliente y Cocinero                                                      |
| **Precondición**          | La comanda ha sido entregada al cliente.                                |
| **Flujo Principal**       | 1. El cliente accede a la aplicación para valorar una comanda. <br> 2. El cliente introduce la valoración con puntuaciones y comentario. <br> 3. El sistema obtiene la información de la comanda. <br> 4. El sistema obtiene el cocinero responsable de la comanda. <br> 5. El sistema crea la valoración y la asocia al cocinero. <br> 6. El sistema devuelve una confirmación al cliente. |
| **Subflujos**             | 1. El cliente accede a la opción de consultar valoraciones. <br> 2. El sistema obtiene todas las valoraciones registradas. <br> 3. Se muestra al cliente una lista de valoraciones de otros usuarios. |
| **Flujos Alternativos**   | N/A                                                                     |
| **Postcondición**         | El sistema registra la valoración y esta queda vinculada a la comanda y al cocinero. |
| **Requisitos no Funcionales** | N/A                                                                 |
| **Prioridad**             | Normal                                                                  |
| **Comentarios**           | N/A                                                                     |
