Para el caso de Gnosoft Académico, se han definido los siguientes puntos de vista de arquitectura.

 * [Contexto](#contexto)
 * [Funcional](#funcional)
 * [Despliegue](#despliegue)
 * [Dominio](#dominio)
    * [Subdominio de Académico](#Subdominio-de-Académico)
    * [Subdominio Administrativo](#Subdominio-Administrativo)
    * [Subdominio Boletines](#Subdominio-Boletines)
    * [Subdominio Pagos](#Subdominio-Pagos)
    * [Subdominio Usuarios](#Subdominio-Usuarios)

## Contexto

   Para el caso de Gnosoft se define el siguiente modelo de contexto, donde se ven los usuarios directos del colegio en el costado izquierdo, los 
   administrativos de Gnosoft en la parte inferior. Desde la parte de componentes involucrados están las API's en la parte superior y las bases de datos 
   en el costado derecho.

   ![Modelo de Contexto](https://cdn.discordapp.com/attachments/770159999967821835/812196889323503657/Modelo_de_Contexto.jpeg)

## Funcional

   Para las funcionalidades de Gnosoft se define, a partir del modelo de dominio, el siguiente modelo de componentes. El cual representa cada uno de los 
   módulos que cumplirán las funcionalidades esperadas para Gnosoft Académico:

  ![Modelo de Componentes](https://cdn.discordapp.com/attachments/770159999967821835/812205860562141204/Modelo_de_Componentes.jpeg)

## Despliegue

   ### Sprint 1
   Para Gnosoft se definen se define el siguiente modelo de despliegue a partir de las necesidades de Gnosoft. Este modelo está acorde a lo definido en 
   el modelo de componentes.

  ![Modelo de Despliegue V_1](https://cdn.discordapp.com/attachments/770159999967821835/812206602391257109/Modelo_de_Despliegue.jpeg)
  
  ### Sprint 2 
   Para esta segunda iteración del proyecto realizado para Gnosoft Académico, se propone el siguiendo modelo de despliege, el cual se divide en diferentes manejadores para        facilitar la modularidad del sistema.
   
   ![Modelo de Despliegue V_2](https://cdn.discordapp.com/attachments/819466978774876174/830033429487812678/Modelo_de_Despliegue_4.0.png)
   
   ### Sprint 3 
   Para esta tercera iteración del proyecto realizado para Gnosoft Académico, se propone el siguiendo modelo de despliege, el cual se divide en diferentes manejadores para        facilitar la modularidad del sistema, además, se adiciona el manejador de autorización y autenticación para mejorar y garantizar la seguridad del sistema.
   
   ![Modelo de Despliegue V_3](https://media.discordapp.net/attachments/839731469060276235/842767017190883418/ArquiSoft_-_Pagina_10.png)
   
## Dominio

  De acuerdo a los features, historias de usuario y ASR se define el siguiente modelo de dominio. Este modelo representa cada uno de los conceptos 
  involucrados en Gnosoft Académico, sus atributos y las relaciones entre estos.

  ![Modelo de Dominio](https://cdn.discordapp.com/attachments/770159999967821835/812199294818975754/Modelo_de_Dominio.jpeg)

  Así mismo, se definen diferentes subdominios para Gnosoft Académico. Estos subdominios se definen a partir de las funcionalidades esperadas en el 
  programa y la forma esperada para solucionar los inconvenientes actuales.

### Subdominio de Académico: 
Subdominio del sistema orientado a permitir el manejo de los cursos de cada uno de los colegios pertenecientes a Gnosoft Académico.

![Subdominio Académico](https://cdn.discordapp.com/attachments/770159999967821835/812200553475080212/Subdominio_Academico.jpeg)

### Subdominio Administrativo: 

 Subdominio del sistema orientado al manejo central del sistema de Gnosoft Académico. Desde acá se maneja la creación de roles y las PQR's que se 
 realizan a Gnosoft Académico.

![Subdominio Administrativo](https://cdn.discordapp.com/attachments/770159999967821835/812201508908564510/Subdominio_Administrativo.jpeg)

### Subdominio Boletines:

 Subdominio del sistema orientado al manejo de notas a través del tiempo y la generación de PDF's a partir de los consolidados de notas actuales e 
 históricos de los estudiantes.

![Subdominio Boletines](https://cdn.discordapp.com/attachments/770159999967821835/812202102750576650/Subdominio_Boletines.jpeg)

### Subdominio Pagos:

 Subdominio del sistema orientado a la generación de facturas y pagos por el concepto de matrícula en Gnosoft Académico.
![Subdominio Pagos](https://cdn.discordapp.com/attachments/770159999967821835/812202573338771486/Subdominio_Pagos.jpeg)

### Subdominio Usuarios:

  Subdominio del sistema orientado al manejo de cada uno de los tipos de usuarios involucrados en Gnosoft Académico. A partir de este se establecen cada 
  una de las funcionalidades a las que tienen acceso cada uno de los usuarios.

![Subdominio Usuarios](https://cdn.discordapp.com/attachments/770159999967821835/812203362241609758/Subdominio_Usuarios.jpeg)
