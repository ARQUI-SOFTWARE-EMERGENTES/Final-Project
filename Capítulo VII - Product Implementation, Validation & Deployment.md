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



### Development Evidence for Sprint Review

### Testing Suite Evidence for Sprint Review

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

## Registro de entrevistas

## Evaluaciones según heurísticas

# Video About-the-Product



