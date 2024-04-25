# Bounded Context: Bounded Context Name
## Domain Layer
## Interface Layer
## Application Layer
## Infrastructure Layer
## Bounded Context Software Architecture Component Level Diagrams
## Bounded Context Software Architecture Code Level Diagrams
### Bounded Context Domain Layer Class Diagrams
### Bounded Context Database Design Diagram

# Bounded Context: Envío de investigaciones
## Domain Layer
<table>
  <tr>
    <td colspan="2" style="font-weight: bold;">Nombre:</td>
    <td colspan="2">SendInvestigationAggregate</td>
  </tr>
  <tr>
    <td colspan="2" style="font-weight: bold;">Categoría:</td>
    <td colspan="2">Aggregate</td>
  </tr>
  <tr>
    <td colspan="2" style="font-weight: bold;">Propósito:</td>
    <td colspan="2">bounded context engloba el comportamiento de multiples entidades y objetos.</td>
  </tr>
  <tr>
    <td colspan="4" style="text-align: center; font-weight: bold;">Atributos</td>
  </tr>
  <tr>
    <td style="font-weight: bold;">Nombre</td>
    <td style="font-weight: bold;">Tipo de dato</td>
    <td style="font-weight: bold;">Visibilidad</td>
    <td style="font-weight: bold;">Descripción</td>
  </tr>
  <tr>
    <td>InvestigationID</td>
    <td>int</td>
    <td>private</td>
    <td>Un identificador único para cada investigación</td>
  </tr>
  <tr>
    <td>Title </td>
    <td>string</td>
    <td>private</td>
    <td>titulo de la investigacion</td>
  </tr>
  <tr>
    <td>Abstract</td>
    <td>string</td>
    <td>public</td>
    <td>El resumen de la investigación.</td>
  </tr>
  <tr>
    <td>Content </td>
    <td>string</td>
    <td>public</td>
    <td>el contenido de la investigacion</td>
  </tr>
  <tr>
    <td>Authors</td>
    <td>List< AuthorUse ></td>
    <td>public</td>
    <td>Una lista de autores asociados a la investigación. </td>
  </tr>
  <tr>
    <td>ReviewStatus (Enum)</td>
    <td>enum</td>
    <td>public</td>
    <td>El estado de revisión de la investigación (por ejemplo: PENDING, IN_PROGRESS, COMPLETED).</td>
  </tr>
  <tr>
    <td>Authenticated </td>
    <td>boolean</td>
    <td>public</td>
    <td>Un indicador de si la investigación ha sido autenticada como verídica.</td>
  </tr>
  <tr>
    <td>Reviewers </td>
    <td>List< AuthorUser></td>
    <td>private</td>
    <td>Una lista de revisores asignados a la investigación.</td>
  </tr>
  <tr>
    <td>SubmissionDate</td>
    <td>Date/td>
    <td>public</td>
    <td>La fecha en que se envió la investigación.</td>
  </tr>
  <tr>
    <td>SubmissionDate</td>
    <td>Date/td>
    <td>public</td>
    <td>La fecha en que se envió la investigación.</td>
  </tr>
  <tr>
    <td>LastModifiedDate</td>
    <td>Date/td>
    <td>public</td>
    <td>La fecha en que se hizo la ultima modificacion en la investigación.</td>
  </tr>
  <tr>
    <td colspan="4" style="text-align: center;font-weight: bold;">Métodos</td>
  </tr>
  <tr>
    <td style="font-weight: bold;">Nombre</td>
    <td style="font-weight: bold;">Tipo de retorno</td>
    <td style="font-weight: bold;">Visibilidad</td>
    <td style="font-weight: bold;">Descripción</td>
  </tr>
  <tr>
    <td>submitForReview</td>
    <td>void</td>
    <td>public</td>
    <td>Método para enviar la investigación para su revisión. Actualiza el estado de revisión a "PENDING" y registra la fecha de envío.</td>
  </tr>
  <tr>
    <td>assignReviewer</td>
    <td>void</td>
    <td>public</td>
    <td>Método para asignar un revisor a la investigación. Agrega al revisor a la lista de revisores.</td>
  </tr>
   <tr>
    <td>updateReviewStatus(Enum status)</td>
    <td>void</td>
    <td>public</td>
    <td>Método para actualizar el estado de revisión de la investigación.</td>
  </tr>
  <tr>
    <td>authenticate()</td>
    <td>void</td>
    <td>public</td>
    <td>Método para marcar la investigación como autenticada.</td>
  </tr>
  <tr>
    <td>deleteInvestigation()</td>
    <td>void</td>
    <td>public</td>
    <td>Método para eliminar la investigación.</td>
  </tr>
</table>

<br> <br>

<table>
  <tr>
    <td colspan="2" style="font-weight: bold;">Nombre:</td>
    <td colspan="2">authorUser</td>
  </tr>
  <tr>
    <td colspan="2" style="font-weight: bold;">Categoría:</td>
    <td colspan="2">Entity</td>
  </tr>
  <tr>
    <td colspan="2" style="font-weight: bold;">Propósito:</td>
    <td colspan="2">Registro, inicio de sesión, gestión de perfil, gestión de roles y permisos.</td>
  </tr>
  <tr>
    <td colspan="4" style="text-align: center; font-weight: bold;">Atributos</td>
  </tr>
  <tr>
    <td style="font-weight: bold;">Nombre</td>
    <td style="font-weight: bold;">Tipo de dato</td>
    <td style="font-weight: bold;">Visibilidad</td>
    <td style="font-weight: bold;">Descripción</td>
  </tr>
  <tr>
    <td>authorUserId</td>
    <td>int</td>
    <td>private</td>
    <td>Identificador único del usuarioAutor</td>
  </tr>
  <tr>
    <td>Name</td>
    <td>string</td>
    <td>private</td>
    <td>Nombre del autor</td>
  </tr>
  <tr>
    <td>correo</td>
    <td>string</td>
    <td>private</td>
    <td>correo del usuario autor</td>
  </tr>
  <tr>
    <td>StartDatetime</td>
    <td>Datetime</td>
    <td>private</td>
    <td>Fecha de inicio en la plataforma</td>
  </tr>
  <tr>
    <td>Location</td>
    <td>Location</td>
    <td>private</td>
    <td>Ubicación del usuario autor</td>
  </tr>
  <tr>
    <td>password</td>
    <td>string</td>
    <td>private</td>
    <td>contraseña del usuario</td>
  </tr>
  <tr>
    <td>profession</td>
    <td>string</td>
    <td>private</td>
    <td>profesion del usuario (ejem: ingeniero, doctor, maestro, etc)</td>
  </tr>
  <tr>
    <td>academicDegree</td>
    <td>string</td>
    <td>private</td>
    <td>grado academico del usuario autor de investigaciones o tesis (ejem: bachiller, mestria, doctorado, etc)</td>
  </tr>
  <tr>
    <td>ActivityHistory</td>
    <td>list< string></td>
    <td>private</td>
    <td>Un registro de las actividades realizadas por el usuario autor en la plataforma (por ejemplo, investigaciones publicadas, comentarios realizados).</td>
  </tr>
  <tr>
    <td colspan="4" style="text-align: center;font-weight: bold;">Métodos</td>
  </tr>
  <tr>
    <td style="font-weight: bold;">Nombre</td>
    <td style="font-weight: bold;">Tipo de retorno</td>
    <td style="font-weight: bold;">Visibilidad</td>
    <td style="font-weight: bold;">Descripción</td>
  </tr>
  <tr>
    <td>PublishResearch</td>
    <td>void</td>
    <td>public</td>
    <td>Un método para que el usuario autor pueda publicar una nueva investigación en la plataforma. Este método tomaría como entrada los detalles de la investigación (título, resumen, contenido, etc.) y lo registraría en la base de datos.</td>
  </tr>
  <tr>
    <td>ChangeName</td>
    <td>void</td>
    <td>public</td>
    <td>Método para cambiar el nombre del usuario</td>
  </tr>
   <tr>
    <td>ChangePassword</td>
    <td>void</td>
    <td>public</td>
    <td>Cambiar la contraseña</td>
  </tr>
  <tr>
    <td>ChangeEmail</td>
    <td>void</td>
    <td>public</td>
    <td>Cambiar el correo del usuario</td>
  </tr>
</table>

<br>

## Interface Layer

<table>
  <tr>
    <td colspan="2" style="font-weight: bold;">Nombre:</td>
    <td colspan="2">SendInvestigationController</td>
  </tr>
  <tr>
    <td colspan="2" style="font-weight: bold;">Categoría:</td>
    <td colspan="2">Controller</td>
  </tr>
  <tr>
    <td colspan="2" style="font-weight: bold;">Propósito:</td>
    <td colspan="2">Servir como intermediario de la lógica de dominio ante la capa de presentación u otros servicios web que lo invoquen</td>
  </tr>
  <tr>
    <td colspan="4" style="text-align: center;font-weight: bold;">Métodos</td>
  </tr>
  <tr>
    <td style="font-weight: bold;">Nombre</td>
    <td style="font-weight: bold;">Tipo de retorno</td>
    <td style="font-weight: bold;">Visibilidad</td>
    <td style="font-weight: bold;">Desc
    ripción</td>
  </tr>
  <tr>
    <td>submitInvestigation </td>
    <td>ResponseEntity< String></td>
    <td>public</td>
    <td>Este método maneja la solicitud de envío de una nueva investigación. Toma como parámetros el título, resumen, contenido y una lista de identificadores de autores de la investigación. Realiza la validación de los datos de entrada y envía la investigación para su revisión. Retorna una respuesta con un mensaje indicando el resultado del proceso de envío.</td>
  </tr>
  <tr>
    <td>assignReviewer</td>
    <td>ResponseEntity< String></td>
    <td>public</td>
    <td>Este método maneja la solicitud de asignación de revisores a una investigación específica. Toma como parámetros el identificador de la investigación y el identificador del revisor. Realiza la validación de los datos de entrada y asigna al revisor a la investigación correspondiente. Retorna una respuesta con un mensaje indicando el resultado del proceso de asignación.</td>
  </tr>
  <tr>
    <td>updateReviewStatus</td>
    <td>ResponseEntity< String></td>
    <td>public</td>
    <td>Este método maneja la solicitud de actualización del estado de revisión de una investigación. Toma como parámetros el identificador de la investigación y el nuevo estado de revisión. Realiza la validación de los datos de entrada y actualiza el estado de revisión de la investigación correspondiente. Retorna una respuesta con un mensaje indicando el resultado del proceso de actualización.</td>
  </tr>
  <tr>
    <td>authenticateInvestigation</td>
    <td> ResponseEntity< String></td>
    <td>public</td>
    <td>Este método maneja la solicitud de autenticación de una investigación específica. Toma como parámetro el identificador de la investigación. Realiza la validación de los datos de entrada y marca la investigación como autenticada. Retorna una respuesta con un mensaje indicando el resultado del proceso de autenticación.</td>
  </tr>
  <tr>
    <td>deleteInvestigation</td>
    <td>ResponseEntity< String></td>
    <td>public</td>
    <td>Este método maneja la solicitud de eliminación de una investigación específica. Toma como parámetro el identificador de la investigación. Realiza la validación de los datos de entrada y elimina la investigación correspondiente. Retorna una respuesta con un mensaje indicando el resultado del proceso de eliminación.</td>
  </tr>
</table>

<br> <br>


## Application Layer


El Application Layer en la arquitectura de software es responsable de coordinar las operaciones y flujos de trabajo del sistema.

<table>
    <tr>
        <td colspan="2" style="font-weight: bold;">Nombre: </td>
        <td colspan="2">SendInvestigationService</td>
    </tr>
    <tr>
        <td colspan="2" style="font-weight: bold;">Categoría:</td>
        <td colspan="2">Servicio de aplicación</td>
    </tr>
    <tr>
        <td colspan="2" style="font-weight: bold;">Propósito:</td>
        <td colspan="2">Este servicio maneja la lógica de aplicación relacionada con el envío de investigaciones en PaperVault</td>
    </tr>
    <tr>
        <td style="font-weight: bold;">Nombre</td>
        <td style="font-weight: bold;">Tipo de retorno</td>
        <td style="font-weight: bold;">Visibilidad</td>
        <td style="font-weight: bold;">Descripción</td>
    </tr>
    <tr>
        <td>submitInvestigation</td>
        <td>ResponseEntity< String></td>
        <td>public</td>
        <td>Este método coordina el proceso de envío de una nueva investigación.</td>
    </tr>
</table>

<br>

<table>
    <tr>
        <td colspan="2" style="font-weight: bold;">Nombre: </td>
        <td colspan="2">DeleteInvestigationService</td>
    </tr>
    <tr>
        <td colspan="2" style="font-weight: bold;">Categoría:</td>
        <td colspan="2">Servicio de aplicación</td>
    </tr>
    <tr>
        <td colspan="2" style="font-weight: bold;">Propósito:</td>
        <td colspan="2">Este servicio maneja la lógica de aplicación relacionada con la eliminacion de investigaciones en PaperVault</td>
    </tr>
    <tr>
        <td style="font-weight: bold;">Nombre</td>
        <td style="font-weight: bold;">Tipo de retorno</td>
        <td style="font-weight: bold;">Visibilidad</td>
        <td style="font-weight: bold;">Descripción</td>
    </tr>
    <tr>
        <td>deleteInvestigation</td>
        <td>void</td>
        <td>public</td>
        <td>Coordina el proceso de eliminación de una investigación específica.</td>
    </tr>
</table>

<br>

## Infrastructure Layer

El Infrastructure Layer se encarga de implementar los detalles técnicos y de infraestructura necesarios para que la aplicación funcione correctamente. 

<table>
    <tr>
        <td colspan="2" style="font-weight: bold;">Nombre:</td>
        <td colspan="2">SendInvestigationRepository</td>
    </tr>
    <tr>
        <td colspan="2" style="font-weight: bold;">Categoría:</td>
        <td colspan="2">Repositorio de infraestructura</td>
    </tr>
    <tr>
        <td colspan="2" style="font-weight: bold;">Propósito:</td>
        <td colspan="2">Este repositorio proporciona métodos para interactuar con el almacenamiento de datos relacionados con el envío de investigaciones.</td>
    </tr>
    <tr>
        <td colspan="4" style="font-weight: bold; text-align: center;">Métodos</td>
    </tr>
    <tr>
        <td style="font-weight: bold;">Nombre</td>
        <td style="font-weight: bold;">Tipo de retorno</td>
        <td style="font-weight: bold;">Visibilidad</td>
        <td style="font-weight: bold;">Descripción</td>
    </tr>
    <tr>
        <td>saveInvestigation</td>
        <td>void</td>
        <td>protected</td>
        <td>Guarda una nueva investigación en el almacenamiento de datos.</td>
    </tr>
    <tr>
        <td>updateInvestigation</td>
        <td>void</td>
        <td>protected</td>
        <td>Actualiza los detalles de una investigación existente en el almacenamiento de datos.</td>
    </tr>
    <tr>
        <td>deleteInvestigation</td>
        <td>void</td>
        <td>protected</td>
        <td>Elimina una investigación del almacenamiento de datos.</td>
    </tr>
    <tr>
        <td>getInvestigationById</td>
        <td>int</td>
        <td>protected</td>
        <td>Recupera una investigación del almacenamiento de datos según su identificador.</td>
    </tr>
       <tr>
        <td>getInvestigationsByAuthor</td>
        <td>string</td>
        <td>protected</td>
        <td> Recupera todas las investigaciones asociadas a un autor específico.</td>
    </tr>
    </tr>
       <tr>
        <td>updateReviewStatus</td>
        <td>void</td>
        <td>protected</td>
        <td> Actualiza el estado de revisión de una investigación en el almacenamiento de datos.</td>
    </tr>
</table>

<br>

## Bounded Context Software Architecture Component Level Diagrams

## Bounded Context Software Architecture Code Level Diagrams
### Bounded Context Domain Layer Class Diagrams
### Bounded Context Database Design Diagram

# Bounded Context: Bounded Context Name
## Domain Layer
## Interface Layer
## Application Layer
## Infrastructure Layer
## Bounded Context Software Architecture Component Level Diagrams
## Bounded Context Software Architecture Code Level Diagrams
### Bounded Context Domain Layer Class Diagrams
### Bounded Context Database Design Diagram

# Bounded Context: Bounded Context Name
## Domain Layer
## Interface Layer
## Application Layer
## Infrastructure Layer
## Bounded Context Software Architecture Component Level Diagrams
## Bounded Context Software Architecture Code Level Diagrams
### Bounded Context Domain Layer Class Diagrams
### Bounded Context Database Design Diagram