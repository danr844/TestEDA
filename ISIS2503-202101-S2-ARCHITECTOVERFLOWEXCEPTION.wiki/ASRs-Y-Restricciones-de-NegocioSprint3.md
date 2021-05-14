## ASR's Sprint 3: 
  ## ASR 1 
  *  Integridad:

  ASR 1: Como profesor, dado que el sistema está funcionando correctamente , cuando una nota de mis estudiantes sea o intente ser modificada, deseo que esta modificación sea        registrada en un log de cambios y esto debe ocurrir en el 99.9999% de los casos. 

Cómo: Admin Log* . 
  ## ASR 2
  *  Confidencialidad : 

ASR 2: Como rector, dado que el sistema está funcionando correctamente, cuando cada uno de los usuarios de la plataforma solicite un servicio, deseo que la solicitud sea aprobada sólo si está permitida en su rol, y esto debe ocurrir en el 99.9999% de los casos. 

Cómo: Auth0 :
  ## ASR 3
  
  * Disponibilidad : 

ASR 3: Como acudiente, dado que el sistema se encuentra en una operatividad alta, cuando solicite descargar el reporte notas de mi acudido, pero obtener el reporte en pdf con un porcentaje de éxito mayor a un 95% de los intentos realizados durante este periodo de saturación. 

Cómo: Despliegue en la nube/ bases de datos* 

Las imposiciones de negocio y de tecnología que se tienen para el desarrollo de una solución desarrollada con Gnosoft Académico son:

* [Restricciones de Negocio](#Restricciones-de-negocio)
   * [Restricción de negocio 1](#Restricción-de-negocio-1) 
   * [Restricción de negocio 2](#Restricción-de-negocio-2) 
* [Restricciones de Tecnología](#Restricciones-de-tecnología)
   * [Restricción de tecnología 1](#Restricción-de-tecnología-1) 
   * [Restricción de tecnología 2](#Restricción-de-tecnología-2) 

## Restricciones de Negocio: 

  * ### Restricción de negocio 1:
     - Para que la nueva solución propuesta (infraestructura y software) sea considerada para su uso, esta no debe superar en costo los $20.000.000 anuales.
  * ### Restricción de negocio 2:
     - La solución debe estar dirigida estrictamente a la estructura de los colegios de básica primaria, secundaria y media.

## Restricciones de Tecnología:

  * ### Restricción de tecnología 1:
     - Dada la gran cantidad de líneas de código existentes en Gnosoft Académico, cerca de 5 millones, la solución propuesta debe adaptarse al sistema 
       existente y debe promover la escalabilidad e independencia de los procesos.
  * ### Restricción de tecnología 2:
     - La solución propuesta debe ser parametrizable, con el fin de que se adapte a la estructura organizacional y funcional de cada colegio.
