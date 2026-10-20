-Revision / correccion de texto


| Pantalla / componente      | nombre/ID del frame       | enlace                                                                                                         | estado     | web/movil | ruta html                 |   |
|----------------------------|---------------------------|----------------------------------------------------------------------------------------------------------------|------------|-----------|---------------------------|---|
| Dashboard                  | Dashboard / 523:280       | https://www.figma.com/design/NX2O5kjifpIzqvrGUDhwXp/Farmacia-La-Esperanza?node-id=523-280                      | incompleto | web       | admin/login.html          |   |
| Pedidos                    | Pedidos / 523:422         | https://www.figma.com/design/NX2O5kjifpIzqvrGUDhwXp/Farmacia-La-Esperanza?node-id=523-422&t=zSoUrqmCL92aaUY4-0 | incompleto | web       | admin/pedidos.html        |   |
| Usuarios                   | Usuarios / 523:623        | https://www.figma.com/design/NX2O5kjifpIzqvrGUDhwXp/Farmacia-La-Esperanza?node-id=523-623                      | incompleto | web       | admin-usuarios.html       |   |
| Producto                   | Producto / 523-729        | https://www.figma.com/design/NX2O5kjifpIzqvrGUDhwXp/Farmacia-La-Esperanza?node-id=523-729                      | incompleto | web       | admin-productos.html      |   |
| Notificaciones             | Notificaciones / 523:822  | https://www.figma.com/design/NX2O5kjifpIzqvrGUDhwXp/Farmacia-La-Esperanza?node-id=523-822                      | completo   | web       | admin-notificaciones.html |   |
| Chat emergente(componente) | chat-emergente / 523:1136 | https://www.figma.com/design/NX2O5kjifpIzqvrGUDhwXp/Farmacia-La-Esperanza?node-id=523-1136                     | compleot   | web       | admin-notificaciones.html |   |
| Recetas                    | Recetas / 535:35          | https://www.figma.com/design/NX2O5kjifpIzqvrGUDhwXp/Farmacia-La-Esperanza?node-id=535-35&t=zSoUrqmCL92aaUY4-0  | ausente    | web       | admin-recetas.html        |   |


-Relacion de botones 

| Boton/enlace              | ID/Nombre | Destino esperado       | Destino ID | Estado      |   |
|---------------------------|-----------|------------------------|------------|-------------|---|
| Entrar                    | 535-59    | Dashboard              | 523-280    | existente   |   |
| ¿Olvidaste tu contraseña? | 535-57    | Recuperar contrasena   | -          | Ausente     |   |
| Dashboard (menu)          | 523-296   | Dashboard              | 523-280    | existente   |   |
| Pedidos (menu)            | 523-297   | Pedidos                | 523-422    | existente   |   |
| Usuarios (menu)           | 523-298   | Usuarios               | 523-623    | existente   |   |
| Recetas (menu)            | 523-299   | Recetas                | 535-35     | frame vacio |   |
| Inventario (menu)         | 523-304   | Productos e inventario | 523-729    | existente   |   |
| Notificaciones (menu)     | 523-305   | Notificaciones         | 523-822    | existente   |   |
| Barra de busqueda         | 523-308   | Resultado              | -          | ausente     |   |
| DIARIO                    | 523-352   | grafico/diario         | -          | ausente     |   |
| SEMANAL                   | 523-353   | grafico/mensual        | -          | ausente     |   |
| AGREGAR PEDIDO            | 523-448   | formulario de pedido   | -          | ausente     |   |
| REPARTIDOR ->             | 523-560   | filtro en tabla        | -          | ausente     |   |
| EXPORTAR -> (pedidos)     | 523-462   | Descarga/confirmacion  | -          | ausente     |   |
| Asignar repartidor        | 528-1394  | Lista de repartidores  | -          | ausente     |   |
| ACEPTAR                   | 523-488   | Confirmacion           | -          | ausente     |   |
| RECHAZAR                  | 523-492   | Confirmacion/rechazo   | -          | ausente     |   |
| +NUEVO USUARIO            | 523-640   | Formulario de usuario  | -          | ausente     |   |
| editar/suspender          | 523-654   | Confirmacion           | -          | ausente     |   |
| GUARDAR CAMBIOS           | 523-709   | Mensaje de guardado    | -          | ausente     |   |
| +AGREGAR PRODUCTO         | 523-804   | Formulario de producto | -          | ausente     |   |
| +NUEVA OFERTA             | 528-1367  | Formulario de oferta   | -          | ausente     |   |
| MARCAR COMO AGOTADO       | 528-1380  | Confirmacion           | -          | ausente     |   |
| EXPORTAR-> (productos)    | 528-1229  | Confirmacion           | -          | ausente     |   |
| ENVIAR                    | 523-864   | Mensaje en el chat     | 523-1136   | existente   |   |
| Cerrar chat               | 523-1139  | Chat-burbuja           | 523-421    | existente   |   |

-Contradicciones de botones

| Contradiccion                                                        | Evidencia(ID origen) | Evidencia (ID Destino) |
|----------------------------------------------------------------------|----------------------|------------------------|
| Recetas esta en el menu, pero su fram esta vacio                     | 523-299              | 535-35                 |
| "En camino" sin ningun pedido de ejemplo                             | 523-395              | 523-456                |
| ENTREGADA/CANCELADA escritos como  ENTREGADO/CANCELADO en otro frame | 523-486              | 523-1167               |
| Estado de pedido "CONFIRMADO" dentro de la tabla de productos        | 523-382             | 523-382                |
| ACEPTAR y RECHAZAR sin estados resultantes                           | 523-488              | 523-492                |


-Propuestas:

1-Disenar la pantalla de receta para mantener la coherencia y relacion entre pantallas.

2-Disenar los estados y formularios faltantes de las pantallas para conectar los botones con sus respectivas pantallas y mantener el flujo.

3-Terminar de disenar todas las pantallas, revisar el flujo y disenar la version movil del apartado de administracion.