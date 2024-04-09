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

<table>
    <thead>
        <tr>
            <th>Driver ID</th>
            <th>Título de Driver</th>
            <th>Descripción</th>
            <th>Importancia para Stakeholders (High, Medium, Low)</th>
            <th>Impacto en Architecture Technical Complexity (High, Medium, Low)</th>
        </tr>
    </thead>
    <tbody>
        <tr>
            <td>D1</td>
            <td>Publicar paper</td>
            <td>Como investigador quiero publicar mis papers en la blockchain para evitar mantener la integridad de mis trabajos</td>
            <td>High</td>
            <td>High</td>
        </tr>
        <tr>
            <td>D2</td>
            <td>Visualizar paper</td>
            <td>Como tesista quiero visualizar papers para tenerlas como referencias en mi tesis</td>
            <td>High</td>
            <td>High</td>
        </tr>
        <tr>
            <td>D3</td>
            <td>Guardar papers</td>
            <td>Como tesista quiero guardar papers para tenerlas en la mano cuando lo necesite</td>
            <td>High</td>
            <td>Medium</td>
        </tr>
        <tr>
            <td>D4</td>
            <td>Buscar papers</td>
            <td>Como tesistas quiero buscar papers con palabras claves para encontrar los papers relacionados con mi tema de investigación</td>
            <td>High</td>
            <td>Medium</td>
        </tr>
        <tr>
            <td>D5</td>
            <td>Aplicación rápida</td>
            <td>Como usuario quiero que la aplicación sea rápida para no perder tiempo en cargas lentas</td>
            <td>High</td>
            <td>Medium</td>
        </tr>
        <tr>
            <td>D6</td>
            <td>Seguridad en la aplicación</td>
            <td>Como usuario quiero que la aplicación sea segura para evitar hackeos y filtraciones de datos</td>
            <td>High</td>
            <td>Medium</td>
        </tr>
        <tr>
            <td>D7</td>
            <td>Filtrar papers por año</td>
            <td>Como tesista quiero filtrar papers por año para obtener los papers de los años que necesito</td>
            <td>Medium</td>
            <td>Low</td>
        </tr>
        <tr>
            <td>D8</td>
            <td>Ordenar papers por rating</td>
            <td>Como tesista quiero ordenar los resultados por rating para visualizar los mejores papers por la comunidad</td>
            <td>Medium</td>
            <td>Low</td>
        </tr>
        <tr>
            <td>D9</td>
            <td>Visualizar perfil</td>
            <td>Como investigador quiero tener un perfil para que puedan ver mi trayectoria y me puedan contactar</td>
            <td>Low</td>
            <td>Low</td>
        </tr>
        <tr>
            <td>D10</td>
            <td>Escribir comentarios</td>
            <td>Como tesista quiero escribir comentarios en los papers para dar una opinión personal a la comunidad</td>
            <td>Low</td>
            <td>Low</td>
        </tr>
    </tbody>
</table>

## Architectural Design Decisions

<table>
    <thead>
        <tr>
            <th rowspan=2>Driver ID</th>
            <th rowspan=2>Título del driver</th>
            <th colspan=2>Factory Method</th>
            <th colspan=2>Decorator</th>
            <th colspan=2>Singleton</th>
        </tr>
        <tr>
            <th>Pro</th>
            <th>Con</th>
            <th>Pro</th>
            <th>Con</th>
            <th>Pro</th>
            <th>Con</th>
        </tr>
    <thead>
    <tbody>
        <tr>
            <td>D1</td>
            <td>Publicar paper</td>
            <td>Permite publicar papers sin preocuparse en la implementación exactos</td>
            <td>Complicación si existe sobrecarga de clases</td>
            <td>Puede desarrollar nuevas funcionalidades sin modificar el código existente</td>
            <td>Dificultad para especificar funcionalidades específicas</td>
            <td>Facilita la gestión de recursos entre la apalicación y el blockchain</td>
            <td>Genera un acoplamiento fuerte entre los componentes</td>
        </tr>
        <tr>
            <td>D2</td>
            <td>Visualizar paper</td>
            <td>Reusabilidad del código</td>
            <td>Existe una complejidad inicial al implementar el patrón</td>
            <td>Reusar código para distintos tipos de visualización</td>
            <td>Pérdida de rendimiento al haber mayor número de objetos involucrados</td>
            <td>Acceso centralizado a una instancia para visualizar un paper</td>
            <td>Es complejo para adaptar cambios en un futuro</td>
        </tr>
        <tr>
            <td>D3</td>
            <td>Guardar papers</td>
            <td>Facilidad en la creación de nuevas implementaciones</td>
            <td>Posible problemas de rendimiento</td>
            <td>Agregar distintas funcionalidades sin alterar el código base</td>
            <td>Al agregar varios objetos, puede haber una sobrecarga de memoria</td>
            <td>Garantiza que haya una sola clase para guardar papers</td>
            <td>Limitación en cuanto a cambios o nuevas funcionalidades</td>
        </tr>
        <tr>
            <td>D4</td>
            <td>Buscar papers</td>
            <td>Permite manejar distintos tipos de búsqueda sin necesidad de modificar el código</td>
            <td>Aumenta la complejidad de mantenimiento de la funcionalidad</td>
            <td>Crear diferentes decoradores para buscar mediante distintos tipos de criterios</td>
            <td>Tiempo de carga alta al haber más objetos involucrados</td>
            <td>Permite conservar el estado de la búsqueda</td>
            <td>Díficil de mantener</td>
        </tr>
        <tr>
            <td>D5</td>
            <td>Aplicación rápida</td>
            <td>Mejora la modularidad y separa responsabilidades</td>
            <td>Puede agregar una complegidad innecesaria al proyecto</td>
            <td>Permite rapidez en el desarrollo de nuevas funcionalidades</td>
            <td>Es necesario diseñar correctamenta la arquitectura para evitar sobrecarga de objetos</td>
            <td>Optimiza los recursos del sistema</td>
            <td>Alto potencial en generar cuellos de botellas</td>
        </tr>
        <tr>
            <td>D6</td>
            <td>Seguridad en la aplicación</td>
            <td>Permite centralizar la gestión de seguridad en un solo lugar</td>
            <td>El fallo en la implementación del patrón puede exponer a vulneerabilidades</td>
            <td>Se puede aumentar capas de seguridad mediante decoradores</td>
            <td>Requiere una complejidad adicional para el desarrollo</td>
            <td>Permite implementar la seguridad en una sola clase</td>
            <td>Si una clase se ve compromentida, puede dañar gran parte de la aplaicación</td>
        </tr>
        <tr>
            <td>D7</td>
            <td>Filtrar papers por año</td>
            <td>Reutilizar el código y evitar la duplicidad</td>
            <td>Sobrecarga de clases</td>
            <td>Crear nuevos criterios de filtrado fácilmente</td>
            <td>Alto potencial en tener complejidad excesiva</td>
            <td>Evita incosistencia de resultados</td>
            <td>Limita la escabilidad cuando hay una mayor cantidad de criterios</td>
        </tr>
        <tr>
            <td>D8</td>
            <td>Ordenar papers por rating</td>
            <td>Ayuda a la separación de responsabilidades</td>
            <td>Si la cantidad de papers es amplia, puede haber problemas de rendimiento</td>
            <td>Promueve la modularidad, lo que es más fácil de mantener y entender</td>
            <td>Si hay muchos criterios, puede generar una sobrecarga</td>
            <td>Centralizar el proceso de ordenación para la correcta gestión</td>
            <td>Si hay muchos criterios, se limita su escalabilidad</td>
        </tr>
        <tr>
            <td>D9</td>
            <td>Visualizar perfil</td>
            <td>Permite flexibilidad en caso ocurra cambios en los requisitos</td>
            <td>Puede agregar complejidad en el proyecto si los beneficios no son relevantes</td>
            <td>Permite agregar o modificar componentes visuales fácilmente</td>
            <td>Aumenta la complejidad de la arquitectura de la aplicación</td>
            <td>Consistencia de los datos</td>
            <td>Alto acoplamiento de la aplicación</td>
        </tr>
        <tr>
            <td>D10</td>
            <td>Escribir comentarios</td>
            <td>Abstrae la lógica de negocio de los comentarios</td>
            <td>Se pueden crear varias clases para distintos tipo, lo que genera en una sobrecarga.</td>
            <td>Permite la separación de responsabilidades</td>
            <td>El exceso de decoradores repercute en el rendimiento</td>
            <td>Optimización de recursos al evitar crear objetos innecesarios</td>
            <td>Dificultad para la concurrencia</td>
        </tr>
    </tbody>
</table>

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