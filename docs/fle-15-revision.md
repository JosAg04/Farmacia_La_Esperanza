-Especificar estados y pantallas publicas faltantes 

| Pantalla / componente              | nombre/ID frame | enlace  | estado     | web / movil | ruta html propuesta       |
|------------------------------------|-----------------|---------|------------|-------------|---------------------------|
| Detalle producto                   | -               | -       | ausente    | web         | detalle-producto.html     |
| Busqueda/sin resultados            | 319:117         | 319-117 | incompleto | web         | sin-resultados.html       |
| compra existosa/error (componente) | -               | -       | ausente    | web         | compra.html               |
| recuperacion contrasena            | 307:592         | 307-592 | incompleto | web         | recuperar-contresena.html |
| detalle pedido                     | 307:719         | 307-719 | incompleto | web         | usuario-pedido.html       |
| carga y detalle de receta          | 307:803         | 307-803 | incompleto | web         | usuario-receta.html       |
| estado vencido receta              | 307:867         | 307-867 | incompleto | web         | usuario-receta.html       |
|                                    |                 |         |            |             |                           |
| seguimiento del pedido             | -               | -       | ausente    | web         | pedido-seguimiento.html   |


-Botones y contradicciones 

| Boton/enlace                | ID/Nombre         | Destino esperado                       | Destino ID | Estado     |   |
|-----------------------------|-------------------|----------------------------------------|------------|------------|---|
| barra de busqueda           | 307-398           | resultados                             | -          | incompleto |   |
| FINALIZAR COMPRA            | 307-486           | Confirmacion                           | -          | ausente    |   |
| LIMPIAR CARRITO             | 307-482 / 329-212 | Pregunta                               | -          | ausente    |   |
| ¿Olvidaste tu contraseña?   | 307-592           | recuperar contrasena                   | -          | ausente    |   |
| busqueda pedidos            | 307-741           | resultados                             | -          | ausente    |   |
| CERRAR SESION               | 330-707           | pregunta                               | -          | ausente    |   |
| Ver detalle ->              | 307-820           | recetas detalles                       | -          | ausente    |   |
| busqueda recetas            | 330-935           | resultados                             | -          | ausente    |   |
| Registrar recetas           | 307-870           | formulario registra receta             | -          | ausente    |   |
| Registrar Condicion/Alergia | 307-1203          | formulario registrar condicion/alergia | -          | ausente    |   |

-Contradicciones

| Contradiccion                                                                 | Evidencia(ID origen) | Evidencia (ID Destino) |
|-------------------------------------------------------------------------------|----------------------|------------------------|
| La web tiene pantallas de busqueda sin pantalla de resultados                 | 307-398              | -                      |
| El movil tiene flujo de receta (escanear, formulario y confirmacion) la web no | 27-178               | -                      |


-Propuestas:

1-Completar el flujo de receta en la version web, agregar pantallas de subir, formulario para llenar y confirmar
2-Completar componente de la barra de busqueda (encontrado/no encontrado)
3-Crear pantallas faltantes en flujo de recuperar contrasena
4-Agregar estado de vencio en recetas
5-Agregar todas las pantallas y componentes faltantes.