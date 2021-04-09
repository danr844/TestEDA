## Reporte y Análisis de Pruebas: 
Para los ASR propuestos para el desarrollo de este Sprint se definió el desarrollo de una prueba de genereación de PDF´s en una gran cantidad. En este caso, se tienen dos escenarios que representan un escenario medio y medio alto.

En el primer escenario se tiene que el porcentaje de peticiones rechazadas con 800 peticiones GET es 0. Esto permite establecer que esta primera versión del proyecto permite establecer una versión decente para acercarse al servicio esperado.

  ![(800 peticiones)](https://cdn.discordapp.com/attachments/808543758311227422/830035580834283550/unknown.png)
  
 En el caso de tener 1000 peticiones, se observa que el porcentaje de error se incrementa notablemente. Este incremento llega a superare el valor de reperencia que se tiene de error para el proyecto.
  
  ![(1000 peticiones)](https://cdn.discordapp.com/attachments/808543758311227422/830035260346859560/unknown.png)
  
 También es necesario resaltar, que en ambos escenarios se excede de una manera bastante notable los tiempos de espera acordados. Este incremento tan drástico en la espera puede ser originado por la búsqueda constante de datos y los datos que esten asociados a estos. 
 
 Por último, como posible solución para el desarrollo en los siguientes Sprints, se plantea reducir el tiempo que puede tomar buscar los datos en la base de datos  y lo que esto conlleva con la generación de PDF's. Pero cabe resaltar el buen porcentaje de error que se tiene en esta primera versión.
  
