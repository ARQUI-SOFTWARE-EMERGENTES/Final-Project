# Software Configuration Management

## Software Development Environment Configuration

## Source Code Management

## Source Code Style Guide & Conventions

### Java y Spring Boot

- **Nombres de clases y paquetes**: Se utilizará camelCase con mayúscula inicial. Por ejemplo, `UserService`.
- **Nombres de métodos y variables**: Se utilizará camelCase sin mayúscula inicial. Por ejemplo, `getUserById()` o `firstName`.
- **Espacios en blanco y sangría**: Se utilizará 1 tabulador para la sangría
- **Comentarios**: Se utilizarán comentarios Javadoc para documentar clases, métodos y variables.
- **Importaciones**: Se utilizarán declaraciones import static para importar clases estáticas.
- **Manejo de excepciones**: Se utilizará try-catch para manejar excepciones.
- **Anotaciónes**: Se utilizarán anotaciones Spring para configurar beans y componentes.

### Flutter

* **Nombres de clases y widgets:** Se utilizará camelCase con mayúscula inicial. Por ejemplo, `MyWidget` o `MyHomePage`.
* **Nombres de métodos y variables:** Se utilizará camelCase sin mayúscula inicial. Por ejemplo, `buildWidget()` o `firstName`.
* **Espacios en blanco y sangría:** Se utilizará 1 tabulador para la sangría.
* **Comentarios:** Se utilizarán comentarios de línea y comentarios de bloque para documentar código.
* **Importaciones:** Se utilizarán declaraciones import para importar librerías y clases.
* **Manejo de estado:** Se utilizará `setState()` para actualizar el estado del widget.
* **Desarrollo asincrónico:** Se utilizará `async/await` para manejar operaciones asincrónicas.

### Angular:

* **Nombres de componentes, directivas y servicios:** Se utilizará camelCase con prefijo app. Por ejemplo, `AppComponent` o `appMyService`.
* **Nombres de propiedades y métodos:** Use camelCase sin prefijo. Por ejemplo, `firstName` o `getUserById()`.
* **Espacios en blanco y sangría:** Se utilizará 1 tabulador para la sangría.
* **Comentarios:** Use comentarios de línea y comentarios de bloque para documentar código.
* **Importaciones:** Se utilizarán declaraciones `import` para importar módulos y componentes.
* **Enrutamiento:** Se utilizará el enrutador de Angular para navegar entre componentes.
* **Manejo de datos:** Se utilizará `HttpClient` para realizar peticiones HTTP.

### PostgreSQL:

* **Nombres de tablas y columnas:** Se utilizarán minúsculas y guiones bajos para separar palabras. Por ejemplo, `user_table` o `first_name`.
* **Nombres de índices y restricciones:** Se utilizarán minúsculas y guiones bajos para separar palabras. Por ejemplo, `idx_user_id` o `fk_user_table`.
* **Tipos de datos:** Se utilizarán los tipos de datos de PostgreSQL adecuados para sus datos. Por ejemplo, `VARCHAR(255)` para almacenar cadenas de texto de hasta 255 caracteres.
* **Consultas SQL:** Se utilizarán consultas SQL claras y concisas. Evite consultas complejas y difíciles de entender.
* **Optimización de rendimiento:** Se utilizarán índices y consultas optimizadas para mejorar el rendimiento de la base de datos.

## Software Deployment Configuration

En esta sección, el equipo especifica la configuración del despliegue de la solución, incluyendo los pasos necesarios para que, a partir de los repositorios de código fuente, se pueda lograr el despliegue o publicación satisfactorio de cada uno de los productos digitales en la solución.

### Requisitos previos

**Repositorios de código fuente**

* Backend (Java y Spring Boot): Repositorio en GitHub (https://github.com/orgs/ARQUI-SOFTWARE-EMERGENTES/repositories).
* Frontend (Flutter y Angular): Repositorios separados en GitHub (https://github.com/orgs/ARQUI-SOFTWARE-EMERGENTES/repositories).
* Base de datos: PostgreSQL.

**Entorno de desarrollo**

* Java Development Kit (JDK).
* Node.js y npm.
* Flutter SDK.
* PostgreSQL.

### Pasos de despliegue

1. Configuración de PostgreSQL en AWS RDS
    - Crear una instancia de PostgreSQL en Amazon RDS. 
    - Configurar las credenciales y parámetros de conexión (host, puerto, usuario, contraseña, base de datos).,

2. Configuración de instancias EC2 
   - Crear una instancia de EC2 para el backend. 
   - Instalar JDK y configurar variables de entorno. 
   - Instalar PostgreSQL client tools para pruebas de conectividad.

3. Despliegue del Backend (Spring Boot)
   - Compilación del proyecto 
   - Clonar el repositorio del backend. 
   - Ejecutar ./mvnw clean package para compilar el proyecto y generar el archivo .jar.
 
4. Configuración del entorno

   - Establecer variables de entorno necesarias (e.g., DB_HOST, DB_PORT, DB_USER, DB_PASSWORD).
   
5. Despliegue en EC2
   - Transferir el archivo .jar a la instancia de EC2.
   - Ejecutar java -jar nombre-del-archivo.jar.

# Solution Implementation

## Sprint 1

### Sprint Planning 1

<table>
   <thead>
      <tr>
         <th> Sprint # </th>
         <th> Sprint 1 </th>
      </tr>
   </thead>
   <tbody>
   <tr>
      <td> Date </td>
      <td> 02-06-2024 </td>    
   </tr>

   <tr>
      <td> Time </td>
      <td> 06:00 PM </td>
   </tr>

   <tr>
      <td> Location </td>
      <td> Reunión por Meet </td>
   </tr>

   <tr>
      <td> Prepared By </td>
      <td> Gonzalo Barrazueta </td>
   </tr>

   <tr>
      <td> Attendees </td>
      <td> Jonatan Curi / Gonzalo Barrazueta / Vivian Pongo / Gonzalo Sakuda / Jackeline Salomé </td>
   </tr>

   <tr>
      <td> Sprint n Review Summary </td>
      <td> En esta entrega no hay un Sprint anterior, por lo tanto, no hay resúmen del Sprint anterior   </td>
   </tr>

   <tr>
      <td> Sprint n Retrospective Summary </td>
      <td> En esta entrega no hay un Sprint anterior, por lo tanto, no hay resúmen del Sprint anterior   </td>
   </tr>

   <tr>
      <th colspan="2"> Sprint Goal </th>
   </tr>

   <tr>
      <td> Sprint 1 Goal </td>
      <td> La meta de este Sprint es el desarrollo de la primera versión de la aplicación web, frontend y backend </td>
   </tr>

   <tr>
      <td> Sprint 1 Velocity </td>
      <td> X Velocity </td>
   </tr>

   <tr>
      <td> Sum of Story Points </td>
      <td> X Story Points </td>
   </tr>
      
</table>

### Sprint Backlog 1

<table>
   <thead>
      <tr>
         <th colspan="1"> Sprint # </th>
         <th colspan="7"> Sprint 1 </th>
      </tr>
      <tr>
         <th colspan="2"> User Story </th>
         <th colspan="6"> Work-Item / Task </th>
      </tr>
      <tr>
         <th> Id </th>
         <th> Title </th>
         <th> Id </th>
         <th> Title </th>
         <th> Description </th>
         <th> Estimation (Hours) </th>
         <th> Assigned To </th>
         <th> Status (To-do / Doing / Done) </th>
      </tr>
   </thead>
      <tbody>
      <tr>
         <td> US01 </td>
         <td> Registrar cuenta </td>
         <td> T1 </td>
         <td> Crear formulario de registro </td>
         <td> Diseñar e implementar el formulario de registro para nuevos usuarios </td>
         <td> 5 </td>
         <td> Gonzalo Sakuda </td>
         <td> Hecho </td>
      </tr>
      <tr>
         <td> US02 </td>
         <td> Iniciar Sesión </td>
         <td> T2 </td>
         <td> Implementar inicio de sesión </td>
         <td> Desarrollar la funcionalidad de inicio de sesión con autenticación </td>
         <td> 4 </td>
         <td> Fernanda Salomé </td>
         <td> Hecho </td>
      </tr>
      <tr>
         <td> US03 </td>
         <td> Cambiar contraseña </td>
         <td> T3 </td>
         <td> Restablecer contraseña </td>
         <td> Implementar la funcionalidad para permitir a los usuarios cambiar su contraseña </td>
         <td> 6 </td>
         <td> Gonzalo Sakuda </td>
         <td> En progreso </td>
      </tr>
      <tr>
         <td> US08 </td>
         <td> Filtrar resultados por fecha </td>
         <td> T4 </td>
         <td> Filtro por fecha </td>
         <td> Añadir funcionalidad de filtro para ordenar los resultados por fecha </td>
         <td> 3 </td>
         <td> Fernanda Salomé </td>
         <td> Hecho </td>
      </tr>
      <tr>
         <td> US09 </td>
         <td> Filtrar resultados por tipo </td>
         <td> T5 </td>
         <td> Filtro por tipo </td>
         <td> Implementar filtro de resultados basado en el tipo </td>
         <td> 3 </td>
         <td> Gonzalo Sakuda </td>
         <td> Hecho </td>
      </tr>
      <tr>
         <td> US10 </td>
         <td> Filtrar resultados por idioma </td>
         <td> T6 </td>
         <td> Filtro por idioma </td>
         <td> Añadir filtro de idioma a los resultados </td>
         <td> 3 </td>
         <td> Fernanda Salomé </td>
         <td> Hecho </td>
      </tr>
      <tr>
         <td> US11 </td>
         <td> Ordenar resultados por relevancia </td>
         <td> T7 </td>
         <td> Ordenar por relevancia </td>
         <td> Implementar la ordenación de resultados por relevancia </td>
         <td> 4 </td>
         <td> Gonzalo Sakuda </td>
         <td> Hecho </td>
      </tr>
      <tr>
         <td> US12 </td>
         <td> Leer paper completo </td>
         <td> T8 </td>
         <td> Vista completa del paper </td>
         <td> Desarrollar la funcionalidad para ver el paper completo </td>
         <td> 5 </td>
         <td> Fernanda Salomé </td>
         <td> Hecho </td>
      </tr>
      <tr>
         <td> US13 </td>
         <td> Guardado de papers </td>
         <td> T9 </td>
         <td> Guardar papers </td>
         <td> Implementar la funcionalidad de guardado de papers </td>
         <td> 6 </td>
         <td> Gonzalo Sakuda </td>
         <td> En progreso </td>
      </tr>
      <tr>
         <td> US14 </td>
         <td> Subir investigación </td>
         <td> T10 </td>
         <td> Subir investigación </td>
         <td> Desarrollar la funcionalidad para subir papers de investigación </td>
         <td> 7 </td>
         <td> Fernanda Salomé </td>
         <td> Hecho </td>
      </tr>
      <tr>
         <td> US21 </td>
         <td> Gestionar perfil </td>
         <td> T11 </td>
         <td> Gestionar perfil </td>
         <td> Implementar las características de gestión de perfil </td>
         <td> 5 </td>
         <td> Gonzalo Sakuda </td>
         <td> Hecho </td>
      </tr>
   </tbody>
</table>

### Development Evidence for Sprint Review

### Testing Suite Evidence for Sprint Review

| **Repository** | **Branch** |  **Commit Id**  | **Commit Message** | **Commited on (Date)** |
|-----------|-----------|-----------|-----------|-----------|
| Final Project    | realease/tb2    | 90b8ec755d4f995e602947d427ded8ee59adb086    | feat(docs): new chapter and sprint planning 1 added    | 04/06/2024    | 
| Final Project    | realease/tb2    | 2b3badfd78a7e5ffcc9716ab57d5857da7c6ec61    | feat(docs): describe Source Code Style Guide & Conventions    | 04/06/2024    |
| Final Project    | realease/tb2    | bd01f526f63bdf87bf3a5d0ccbf5e9270e3083fe    | feat(docs): describe Software Deployment Configuration    | 05/06/2024    | 
| Final Project    | realease/tb2    | 416f09fa0e4beeb617f8da54959f8b6f5b4026db    | feat(docs): describe Software Deployment Evidence for Sprint Review    | 05/06/2024    | 
| Final Project    | realease/tb2    | c7eb07e3928e591716c53f21235fd4416817601d    | feat(docs): add version history    | 05/06/2024    | 
| Final Project    | realease/tb2    | 37d0aa530d05902b496e89fd86365a14c9e1554a    | feat(docs): add mockups and prototipe    | 05/06/2024    | 
| Final Project    | realease/tb2    | a38ce7f8b5ba0c8043d4cdd1125a18b6e7144fdf    | feat(docs): add student outcome tb2    | 05/06/2024    |
| Final Project    | realease/tb2    | 791313d78074750cd3d1766f55d4119e2a2b9337    | feat: validation interview added    | 07/06/2024    |
| Final Project    | realease/tb2    | 5c70bf9ce34521d4b1831ca274405592daeea84c    | feat: video about-the-product added    | 07/06/2024    |
| api_user    | main    | b73d8dfb092cb79ad2117a86d724b4a97228b093   | feat: first commit   | 03/06/2024   |
| papervault-app    | realease/tb2    | 41fdee1f97e142d60662fc25519d78e41dab8d27   | feat: add my-research design
   | 01/06/2024   |
| research-service    | main    | ed6b138aab78585ba17dced884c02015ed23b729   | feat: first commit   | 03/06/2024   |


### Execution Evidence for Sprint Review

### Services Documentation Evidence for Sprint Review

### Software Deployment Evidence for Sprint Review

**Introducción**

Durante este Sprint, el equipo se centró en establecer y configurar la infraestructura de despliegue necesaria para nuestro proyecto. Esto incluyó la creación de cuentas en proveedores de la nube, la configuración de recursos necesarios y la integración de procesos de despliegue para asegurar flujos de trabajo fluidos y automatizados. El objetivo fue crear un pipeline de despliegue robusto que pudiera manejar todos los productos digitales, incluyendo el backend (Java y Spring Boot), el frontend (Flutter y Angular) y la base de datos PostgreSQL.

**Actividades Realizadas**

1. Creación de Cuentas en Proveedores de la Nube
   
   - Se creó y configuró una cuenta de AWS para gestionar los recursos en la nube. 
   - Se configuraron roles y permisos de usuario utilizando AWS Identity and Access Management (IAM) para asegurar el acceso seguro a los recursos.


2. Configuración de Recursos en la Nube

   * Se creó una instancia de Amazon RDS para PostgreSQL.
   * Se configuró la instancia de la base de datos con los grupos de seguridad y los parámetros adecuados.
   * Se establecieron configuraciones de conectividad para asegurar un acceso seguro y fiable a la base de datos.
   * Se lanzaron instancias de EC2 para los servicios del backend. 
   * Se instaló el software necesario (JDK, herramientas de cliente de PostgreSQL) en las instancias de EC2. 
   * Se configuraron grupos de seguridad para gestionar el tráfico entrante y saliente de las instancias.


3. Configuración de Proyectos de Desarrollo

   * Se clonó el repositorio del backend y se configuró el proyecto para conectarse a la nueva instancia de PostgreSQL.
   * Se actualizaron las propiedades de la aplicación con las credenciales necesarias y los detalles de conexión a la base de datos.
   * Se empaquetó la aplicación utilizando Maven y se preparó para el despliegue.

### Team Collaboration Insights during Sprint

# Validation Interviews

## Diseño de entrevistas

1. ¿Cómo descrbirías tu experiencia general con la interfaz de usuario?
2. ¿Encontraste la aplicaicón fácil de navegar o hubo algo que te resultó confuso?
3. ¿Qué opinas de las funciones disponibles para subir y visualizar los artículos?
5. ¿Qué opinas sobre el proceso de validación por otros investigadores?
6. ¿Crees que esta aplicación será útil para tu trabajo de investigación o tesis?
7. ¿Qué tan seguro te sientes respecto a la fiabilidad de los documentos en la plataforma?
8. ¿Hay alguna característica adicional que te gustaría ver en la aplicación?
9. ¿Tienes alguna sugerencia para mejorar la alguna funcionalidad actual?
10. ¿Recomendarías esta aplicación a otros tesistas o investigadores? ¿Por qué?


## Registro de entrevistas

### Entrevista 1:

* **Nombre**: Paulo Costa Mondragón
* **Link**: https://www.youtube.com/watch?v=yTkus_3xJaA
* **Duración**: 7:15
* **Captura**:

  <img src="images/screenshots-interview/Entrevista_validacion_1.png" width=500/>
<br/>

* **Resumen**: Paulo nos cuenta que le gustaría una funcionalidad diferencial a otras journals o bases de datos. Asimismo, destaca la importancia de la validación de los papers y la facilidad de uso de la plataforma. Además, sugiere la posibilidad de agregar un sistema de validación de papers y de investigadores más seguro.


## Evaluaciones según heurísticas

# Video About-the-Product

* **Link**: https://www.youtube.com/watch?v=13vUkeYQZns
* **Duración**: 3:00
* **Captura**:

<img src="images/screenshots-interview/Entrevista_validacion_1.png" width=500/>

<br/>
* **Resumen**: En el video se presenta las funcionalidades implementadas de momento en la aplicación, como el registro de usuarios, la visualización de papers, la búsqueda y filtrado de papers, y la gestión de perfil. Se destaca la facilidad de uso y la interfaz intuitiva de la aplicación, así como la importancia de la validación de los papers y la seguridad de la plataforma.