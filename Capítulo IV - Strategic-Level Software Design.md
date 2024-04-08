# Strategic-Level Attribute-Driven Design.

## Design Purpose

En PaperVault, nuestra solución se centra en ofrecer seguridad en cuanto a la autoría de los trabajos publicados por nuestros usuarios. Otro de nuestros objetivos es crear un entorno acogedor y dinámico donde investigadores, estudiantes y profesionales puedan publicar, buscar e interactuar de manera directa con investigaciones académicas. Queremos proporcionar una plataforma accesible para todos nuestros usuarios, facilitando la difusión y el descubrimiento de conocimiento. Al hacerlo, ayudamos a los investigadores a obtener el reconocimiento que merecen por sus contribuciones innovadoras al campo académico.

## Attribute-Driven Design Inputs

### Primary Functionality (Primary User Stories)

Se seleccionaron los user stories que cuentan con una mayor relevancia para la solución a desarrollar en el siguiente cuadro:

<table>
    <thead>
        <tr>
            <th>Epic / User Story ID</th>
            <th>Título</th>
            <th>Criterios de Aceptación</th>
            <th>Relacionado con (Epic ID)</th>
        </tr>
    </thead>
    <tbody>
        <tr>
            <td>US07</td>
            <td>Buscar por palabras clave</td>
            <td>
                <b>Scenario 1:</b> Aplicación de filtros por palabra clave <br>
                <b>Dada</b> una búsqueda en la plataforma <br>
                <b>Cuando</b> el usuario ingresa palabras clave <br>
                <b>Y</b> presiona el boton de buscar <br>
                <b>Entonces</b> se muestran las publicaciones que contengan dichas palabras.
            </td>
            <td>EP02</td>
        </tr>
        <tr>
            <td>US14</td>
            <td>Subir investigación</td>
            <td>
                <b>Scenario 1:</b> Archivo cargado correctamente<br>
                <b>Dado que</b> el tesista selecciona la opción "Subir Investigación" desde el menú principal<br>
                <b>Y</b> completa los campos requeridos, como título, autores, resumen y palabras clave<br>
                <b>Cuando</b> adjunta el archivo de investigación<br>
                <b>Y</b> confirma la carga de la investigación para su revisión <br>
                <b>Entonces</b> recibe una confirmación del sistema de que la investigación ha sido enviada correctamente.
                <br><br>
                <b>Scenario 2:</b> Archivo no válido <br>
                <b>Dado que</b> el tesista adjunta el archivo de investigación para solicitar su revisión<br>
                <b>Cuando</b> el tesista intenta confirmar la carga de su investigación<br>
                <b>Entonces</b> El sistema muestra un mensaje de error indicando que el archivo no es válido y solicita al usuario que seleccione un archivo compatible.
            </td>
            <td>EP03</td>
        </tr>
        <tr>
            <td>US18</td>
            <td>Herramientas de detección de plagio</td>
            <td>
            </td>
            <td></td>
        </tr>
    </tbody>
</table>

### Quality attribute Scenarios

<table>
    <thead>
        <tr>
            <th>ID</th>
            <th>Atributo</th>
            <th>Fuente</th>
            <th>Estímulo</th>
            <th>Artefacto</th>
            <th>Entorno</th>
            <th>Respuesta</th>
            <th>Medida</th>
        </tr>
    </thead>
    <tbody>
        <tr>
            <td></td>
        </tr>
    </tbody>
</table>

### Constraints

<table>
    <thead>
        <tr>
            <th>Technical Story ID</th>
            <th>Título</th>
            <th>Descripción</th>
            <th>Criterios de Aceptación</th>
            <th>Relacionado con (Epic ID)</th>
        </tr>
    </thead>
    <tbody>
    </tbody>
</table>

## Architectural Drivers Backlog

## Architectural Design Decisions

## Quality Attribute Scenario Refinements

# Strategic-Level Domain-Driven Design

## Event Storming

## Candidate Context Discovery

## Domain Message Flows Modeling

## Bounded Context Canvases

## Context Mapping

# Software Architecture

## Software Architecture System Landscape Diagram


## Software Architecture Context Level Diagrams

<img src="images/structurizr-74120-SystemContext-001.png"/>

## Software Architecture Container Level Diagrams

## Software Architecture Deployment Diagrams

![Deployment Diagram](images/c4%20model%20diagrams/deployment%20diagram.png)