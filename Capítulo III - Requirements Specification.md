# To-Be Scenario Mapping


# User Stories

<table>
    <thead>
        <tr>
            <th>Epic ID</th>
            <th>Título</th>
            <th>Descripción</th>
        </tr>
    </thead>
    <tbody>
        <tr>
            <td>EP01</td>
            <td>Autenticación y Autorización</td>
            <td>Como usuario deseo acceder a mi cuenta personal para entrar a la aplicación.</td>
        </tr>
        <tr>
            <td>EP02</td>
            <td>Búsqueda de Investigaciones</td>
            <td>Como usuario deseo buscar papers para realizar mi tesis.</td>
        </tr>
        <tr>
            <td>EP03</td>
            <td>Registro de Investigaciones Académicas</td>
            <td>Como usuario, deseo solicitar la revisión de mis investigaciones para que sean evaluadas para su publicación en una revista académica.</td>
        </tr>
        <tr>
            <td>EP04</td>
            <td>Información de Revistas Académicas</td>
            <td>Como usuario, deseo tener la posibilidad de visualizar datos sobre las revistas académicas de los articulos científicos para no tener que cambiar de pestaña constantemente.</td>
        </tr>
        <tr>
            <td>EP05</td>
            <td>Gestión de Referencias Bibliográficas</td>
            <td>Como usuario, deseo poder obtener las referencias bibliograficas de articulos cientificos para poder utilizarlos en mi tesis.</td>
        </tr>
    </tbody>

</table>

<table>
    <thead>
        <tr>
            <th>User Story ID</th>
            <th>Título</th>
            <th>Descripción</th>
            <th>Criterios de aceptación</th>
            <th>Relacionado con Epic ID</th>
        </tr>
    </thead>
    <tbody>
        <tr>
            <td>US01</td>
            <td>Registrar cuenta</td>
            <td>Como usuario deseo registrar una cuenta para crear mi perfil.</td>
            <td>
                <b>Scenario 01:</b> Ingreso correcto de datos</br>
                <b>Dado</b> que el usuario se encuentra en el formulario de registro</br>
                <b>Cuando</b> ingresa sus datos correctamente</br>
                <b>Y</b> presiona el botón registrarse</br>
                <b>Entonces</b> se registra su nueva cuenta</br></br>
                <b>Scenario 02:</b> Ingreso incorrecto de datos</br>
                <b>Dado</b> que el usuario se encuentra en el formulario de registro</br>
                <b>Cuando</b> ingresa sus datos incorrectamente</br>
                <b>Y</b> presiona el botón registrarse</br>
                <b>Entonces</b> sale un mensaje de error</br>
                <b>Y</b> el controno del campo de texto donde ocurre el error se pone de color rojo
            </td>
            <td>EP01</td>
        </tr>
        <tr>
            <td>US02</td>
            <td>Iniciar sesión</td>
            <td>Como usuario deseo iniciar sesión para acceder a la aplicación.</td>
            <td>
                <b>Scenario 01:</b> Ingreso correcto de datos</br>
                <b>Dado</b> que el usuario se encuentra en el formulario de inicio de sesión</br>
                <b>Cuando</b> ingresa sus datos correctamente</br>
                <b>Y</b> presiona el botón iniciar sesión</br>
                <b>Entonces</b> accede a la página de inicio de la aplicacicón</br></br>
                <b>Scenario 02:</b> Ingreso incorrecto de datos</br>
                <b>Dado</b> que el usuario se encuentra en el formulario de inicio de sesión</br>
                <b>Cuando</b> ingresa sus datos incorrectamente</br>
                <b>Y</b> presiona el botón registrarse</br>
                <b>Entonces</b> sale un mensaje de error indicando que los datos ingresados son incorrectos
            </td>
            <td>EP01</td>
        </tr>
        <tr>
            <td>US03</td>
            <td>Cerrar sesión</td>
            <td>Como usuario deseo cerrar sesión para salir de mi cuenta.</td>
            <td>
                <b>Scenario 01:</b> Cerrar sesión</br>
                <b>Dado</b> que el usuario se encuentra en el menú</br>
                <b>Cuando</b> presiona el botón cerrar sesión</br>
                <b>Entonces</b> se cierra la sesión</br>
                <b>Y</b> se muestra la la página de iniciar sesión</br>
            </td>
            <td>EP01</td>
        </tr>
        <tr>
            <td>US04</td>
            <td>Correo electrónico para cambiar contraseña</td>
            <td>Como usuario deseo enviar un correo electrónico para cambiar mi contraseña</td>
            <td>
                <b>Scenario 01:</b> Correo electrónico válido</br>
                <b>Dado</b> que el usuario se encuentra en el formulario de envío de correo electrónico para recuperación de contraseña</br>
                <b>Cuando</b> ingresa un correo electrónico válido</br>
                <b>Y</b> presiona el botón enviar correo electrónico</br>
                <b>Entonces</b> se muestra un mensaje que se envío un correo electrónico</br>
                <b>Y</b> se envía un correo electrónico con un link para cambiar de contraseña</br></br>
                <b>Scenario 02:</b> Correo electrónico inválido</br>
                <b>Dado</b> que el usuario se encuentra en el formulario de envío de correo electrónico para recuperación de contraseña</br>
                <b>Cuando</b> ingresa un correo electrónico inválido</br>
                <b>Y</b> presiona el botón enviar correo electrónico</br>
                <b>Entonces</b> se muestra un mensaje que no existe una cuenta con el correo electrónico</br>
            </td>
            <td>EP01</td>
        </tr>
        <tr>
            <td>US05</td>
            <td>Cambiar contraseña</td>
            <td>Como usuario deseo cambiar mi contraseña para acceder nuevamente a mi cuenta.</td>
            <td>
                <b>Scenario 01:</b> Contraseña válida</br>
                <b>Dado</b> que el usuario se encuentra en el formulario de cambio de contraseña</br>
                <b>Cuando</b> el usuario ingresa una contraseña válida</br>
                <b>Y</b> repite correctamente la contraseña</br>
                <b>Y</b> presiona el botón cambiar contraseña</br>
                <b>Entonces</b> se muestra un mensaje que sla contraseña se cambió correctamente</br></br>
                <b>Scenario 02:</b> Contraseña inválida</br>
                <b>Dado</b> que el usuario se encuentra en el formulario de cambio de contraseña</br>
                <b>Cuando</b> ingresa una contraseña invaálida</br>
                <b>Y</b> presiona el botón cambiar contraseña</br>
                <b>Entonces</b> se muestra un mensaje que la contraseña es inválida</br>
            </td>
            <td>EP01</td>
        </tr>
        <tr>
            <td>US06</td>
            <td>Eliminar cuenta</td>
            <td>Como usuario deseo eliminar mi cuenta para borrar todos los datos de la aplicación</td>
            <td>
                <b>Scenario 01:</b> Cerrar cuenta</br>
                <b>Dado</b> que el usuario se encuentra en la página de ajustes</br>
                <b>Cuando</b> el usuario presiona el botón eliminar cuenta</br>
                <b>Y</b> presiona el botón aceptar en el mensaje de confirmación</br>
                <b>Entonces</b> se elimina al cuenta</br>
                <b>Y</b> se muestra la página de inicio de sesión
            </td>
            <td>EP01</td>
        </tr>
        <tr>
            <td>US07</td>
            <td>Buscar por palabras clave</td>
            <td>Como usuario quiero realizar búsquedas por palabras clave para encontrar papers relevantes para mi tesis.</td>
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
            <td>US08</td>
            <td>Filtrar resultados por fecha</td>
            <td>Como usuario quiero filtrar los resultados de búsqueda por fecha de publicación para acceder a papers recientes.</td>
            <td>
                <b>Scenario 1:</b> Aplicación de filtros por fecha de publicación <br>
                <b>Dada</b> una búsqueda realizada en la plataforma <br>
                <b>Cuando</b> el usuario selecciona un rango de fechas <br>
                <b>Y</b> presiona el botón de filtrar <br>
                <b>Entonces</b> se muestran las publicaciones con fechas dentro del rango establecido.
            </td>
            <td>EP02</td>
        </tr>
        <tr>
            <td>US09</td>
            <td>Filtrar resultados por tipo</td>
            <td>Como usuario quiero filtrar los resultados de búsqueda por tipo para acceder a papers recientes.</td>
            <td>
                <b>Scenario 1:</b> Aplicación de filtros por relevancia de publicación <br>
                <b>Dada</b> una búsqueda realizada en la plataforma <br>
                <b>Cuando</b> el usuario selecciona uno o varios tipos de publicacion en los filtros <br>
                <b>Y</b> presiona el botón de filtrar <br>
                <b>Entonces</b> se muestran las publicaciones de los tipos seleccionados.
            </td>
            <td>EP02</td>
        </tr>
        <tr>
            <td>US10</td>
            <td>Filtrar resultados por idioma</td>
            <td>Como usuario quiero filtrar los resultados de búsqueda por idioma para acceder a papers relevantes en un idioma en específico.</td>
            <td>
                <b>Scenario 1:</b> Aplicación de filtros por tipo de publicación <br>
                <b>Dada</b> una búsqueda realizada en la plataforma <br>
                <b>Cuando</b> el usuario selecciona uno o varios idiomas en los que quiere ver las publicaciones <br>
                <b>Y</b> presiona el botón de filtrar <br>
                <b>Entonces</b> se muestran las publicaciones en los idiomas seleccionados.
            </td>
            <td>EP02</td>
        </tr>
        <tr>
            <td>US11</td>
            <td>Ordenar resultados por relevancia</td>
            <td>Como usuario quiero tener la opción de ordenar los resultados de búsqueda por relevancia para identificar los papers más influyentes en mi campo de estudio.</td>
            <td>
                <b>Scenario 1:</b> Aplicación de ordenamiento de publicación <br>
                <b>Dada</b> una búsqueda realizada en la plataforma <br>
                <b>Cuando</b> el usuario selecciona la opción de ordenar los resultados por relevancia <br>
                <b>Entonces</b> se muestran las publicaciones ordenadas según la relevancia.
            </td>
            <td>EP02</td>
        </tr>
        <tr>
            <td>US12</td>
            <td>Leer paper completo</td>
            <td>Como usuario quiero leer el paper completo para poder tener toda la información del paper.</td>
            <td>
                <b>Scenario 1:</b> Redirección a página de publicación <br>
                <b>Dada</b> una publicación seleccionada <br>
                <b>Cuando</b> el usuario selecciona la opción de leer el paper completo <br>
                <b>Entonces</b> se redirige a la página de publicación original. <br>
                <!--<b>Scenario 2:</b> Página con restricción <br>
                <b>Dada</b> una publicación seleccionada <br>
                <b>Cuando</b> el usuario selecciona la opción de leer el paper completo <br>
                <b>Entonces</b> se muestra un mensaje de publicación completa bloqueada.-->
            </td>
            <td>EP02</td>
        </tr>
        <tr>
            <td>US13</td>
            <td>Guardado de papers</td>
            <td>Como usuario quiero poder guardar mis búsquedas anteriores en PaperVault para poder retomar la exploración ahorrando tiempo.</td>
            <td>
                <b>Scenario 1:</b> Guardar una búsqueda <br>
                <b>Dado</b> que un usuario ha realizado una búsqueda <br>
                <b>Cuando</b> el usuario decide guardar esa búsqueda <br>
                <b>Y</b> presiona el botón de guardar <br>
                <b>Entonces</b> la búsqueda se guarda correctamente en la cuenta del usuario. <br>
                <b>Scenario 2:</b> Eliminar una búsqueda guardada <br>
                <b>Dado</b> que un usuario ha guardado búsquedas anteriores <br>
                <b>Cuando</b> el usuario opta por eliminar una búsqueda guardada <br>
                <b>Y</b> presiona el botón de borrar <br>
                <b>Entonces</b> la búsqueda seleccionada se elimina exitosamente de la lista de búsquedas guardadas del usuario.
            </td>
            <td>EP02</td>
        </tr>
        <tr>
            <td>US14</td>
            <td>Subir investigación</td>
            <td>Como tesista, deseo solicitar la revisión de mi investigación para saber si va a ser aprobada.</td>
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
            <td>US15</td>
            <td>Notificaciones sobre nuevas investigaciones relevantes</td>
            <td>Cómo autor quiero recibir notificaciones sobre nuevas investigaciones relevantes en mi campo de estudio para estar al tanto de los avances en la investigación </td>
            <td>
                <b>Scenario 1:</b> Configuración de Notificaciones <br>
                <b>Dado que</b> soy un autor registrado en la plataforma <br>
                <b>Cuando</b> acceda a la configuración de notificaciones en mi perfil <br>
                <b>Entonces</b> podré habilitar la opción de recibir notificaciones sobre nuevas investigaciones en mi campo de estudio.
                <br><br>
                <b>Scenario 2:</b> Selección de Áreas de Estudio <br>
                <b>Dado que</b> soy un autor registrado y quiero recibir notificaciones sobre investigaciones relevantes en mi campo de estudio específico<br>
                <b>Cuando</b> acceda a mi perfil de usuario y seleccione las áreas de estudio que me interesan<br>
                <b>Entonces</b> solo recibiré notificaciones sobre investigaciones relacionadas con esas áreas de estudio seleccionadas.
            </td>
            <td>EP06</td>
        </tr>
        <tr>
            <td>US16</td>
            <td>Notificaciones automáticas sobre el estado de revisión</td>
            <td>Como autor quiero recibir notificaciones automáticas sobre el estado de revisión de mis trabajos de investigación para mantenerme actualizado sobre su progreso.</td>
            <td>
                <b>Scenario 1:</b> Registro y Configuración de Notificaciones <br>
                <b>Dado que</b> soy un autor registrado en la plataforma <br>
                <b>Cuando</b>  accedo a mi cuenta de autor <br>
                <b>Entonces</b> debería tener la opción de configurar mis preferencias de notificación sobre el estado de revisión de mis trabajos de investigación.
            </td>
            <td>EP06</td>
        </tr>
        <tr>
            <td>US17</td>
            <td>Colaboraciones y redes con otros investigadores</td>
            <td>Cómo autor quiero establecer colaboraciones y redes con otros investigadores en mi campo de estudio para fomentar la colaboración y el intercambio de conocimientos en la comunidad académica.</td>
            <td>
                <b>Scenario 1:</b> Conexión con Investigadores <br>
                <b>Dado que</b> me encuentro en el perfil del investigador con el que deseo colaborar <br>
                <b>Cuando</b> cuando haga click en "Conectar" <br>
                <b>Y</b> el investigador en cuestion acepte conectar <br>
                <b>Entonces</b> podré enviar una solicitud de colaboración
                <br/><br/>
                <b>Scenario 2:</b> Envío de Solicitudes de Colaboración <br>
                <b>Dado que</b> he conectado con un investigador <br>
                <b>Cuando</b> cuando haga click en "Solicitar colaboración" <br>
                <b>Y</b> el investigador en cuestion acepte la solicitud <br>
                <b>Entonces</b> podré colaborar con el investigador en cuestion
                <br/><br/>
                <b>Scenario 3:</b> Aceptación de Solicitudes <br>
                <b>Dado que</b> he recibido una solicitud de colaboración de otro investigador <br>
                <b>Cuando</b> reviso la solicitud en mi bandeja de entrada de la plataforma <br>
                <b>Y</b> estoy interesado en colaborar con ese autor <br>
                <b>Entonces</b> podré aceptar la solicitud de colaboración
            </td>
            <td>EP03</td>
        </tr>
        <tr>
            <td>US18</td>
            <td>Herramientas de detección de plagio</td>
            <td>Como autor quiero tener acceso a herramientas de detección de plagio para verificar la originalidad de mis trabajos de investigación para garantizar su calidad y credibilidad.</td>
            <td>
                <b>Scenario 1:</b> Acceso a Herramientas de Detección de Plagio <br>
                <b>Dado que</b> soy un autor registrado en la plataforma <br>
                <b>Cuando</b> subo un trabajo de investigación para su verificación de originalidad mediante la herramienta de detección de plagio <br>
                <b>Entonces</b> el sistema debería procesar el documento y proporcionar un informe detallado sobre cualquier similitud encontrada con otros trabajos existentes.
            </td>
            <td>EP03</td>
        </tr>
        <tr>
            <td>US19</td>
            <td>Comentar y discutir investigaciones</td>
            <td>Como usuario quiero poder comentar y discutir investigaciones en la plataforma para participar en la comunidad académica y enriquecer mi comprensión del tema.</td>
            <td>
                <b>Scenario 1:</b> Comentar Investigaciones <br>
                <b>Dado que</b> soy un usuario registrado en la plataforma <br>
                <b>Cuando</b> accedo a una investigación que me interesa <br>
                <b>Y</b> hago click en la seccion de comentarios <br>
                <b>Y</b> hago escribo un comentario en la primera casilla de la seccion de comentarios <br>
                <b>Y</b> hago click en "Comentar" <br>
                <b>Entonces</b>  debería poder dejar comentarios y opiniones sobre la investigación en dicha sección.
                <br><br>
                <b>Scenario 2:</b> Visualización de Comentarios <br>
                <b>Dado que</b> soy un usuario registrado en la plataforma <br>
                <b>Cuando</b> accedo a una investigación que me interesa <br>
                <b>Y</b> hago click en la seccion de comentarios <br>
                <b>Entonces</b>  debería poder ver todos los comentarios dejados por otros usuarios en la misma investigación.
            </td>
            <td>EP02</td>
        </tr>
        <tr>
            <td>US20</td>
            <td>Recibir notificaciones sobre comentarios</td>
            <td>Como autor quiero recibir notificaciones sobre comentarios de mis investigaciones para estar al tanto del feedback de la comunidad académica.</td>
            <td>
                <b>Scenario 1:</b> Recepción de Notificaciones <br>
                <b>Dado que</b> soy un autor registrado en la plataforma <br>
                <b>Cuando</b> alguien deja un comentario en una de mis investigaciones <br>
                <b>Entonces</b> debería recibir una notificación automática en la plataforma, informándome sobre el comentario y proporcionando un enlace directo para acceder a él.
            </td>
            <td>EP06</td>
        </tr>
        <tr>
            <td>US21</td>
            <td>Gestionar perfil</td>
            <td>Como usuario quiero gestionar mi perfil para mostrar mi trayectoria académica y mejorar mi credibilidad la comunidad académica.</td>
            <td>
                <b>Scenario 1:</b> Edición de Perfil <br>
                <b>Dado que</b> soy un usuario registrado en la plataforma <br>
                <b>Cuando</b> accedo a mi perfil personal <br>
                <b>Entonces</b>  debería poder editar la información de mi perfil, incluyendo mi nombre, institución académica, área de estudio, experiencia académica, logros y cualquier otra información relevante.
            </td>
            <td>EP01</td>
        </tr>
        <tr>
            <td>US22</td>
            <td>Seguimiento del proceso</td>
            <td>Como tesista, quiero poder rastrear el estado de la revisión de mi investigación en tiempo real, para tener una visión clara del progreso y estar informado sobre cualquier actualización o cambio en el proceso de revisión.</td>
            <td>
                <b>Scenario 1:</b> Estado de Revisión Actualizado<br>
                <b>Dado que</b> el tesista se encuentra en la sección "Mis Investigaciones"<br>
                <b>Cuando</b> selecciona la opción "Seguimiento" de una de las  investigaciones enviadas<br>
                <b>Entonces</b> encuentra que el estado de revisión de su investigación ha sido actualizado.
                <br><br>
                <b>Scenario 2:</b> Revisión Completada<br>
                <b>Dado que</b> el tesista recibe una notificación de que el proceso de revisión de su investigación ha sido completado<br>
                <b>Cuando</b> selecciona la opción "Seguimiento" de su investigación<br>
                <b>Entonces</b> el tesista puede acceder a los comentarios y revisar el veredicto final emitido para su investigación.
            </td>
            <td>EP03</td>
        </tr>
        <tr>
            <td>US23</td>
            <td>Verificar indexación de revistas en la plataforma</td>
            <td>Como tesista, quiero poder verificar si una revista académica está indexada para evaluar su calidad.</td>
            <td>
                <b>Scenario 1:</b> Verificación de indexado<br>
                <b>Dado que</b> ingreso a la plataforma de Research Guard,<br>
                <b>Cuando</b> selecciono una revista específica<br>
                <b>Entonces</b> veo claramente si está indexada o no.
            </td>
            <td>EP04</td>
        </tr>
        <tr>
            <td>US24</td>
            <td>Ver el nivel de las revistas en la plataforma</td>
            <td>Como tesista, deseo conocer el nivel de las revistas académicas para evaluar su prestigio.</td>
            <td>
                <b>Scenario 1:</b> Visualización del nivel de revistas<br>
                <b>Dado que</b> seleccioné los artículos científicos que usaré,<br>
                <b>Cuando</b> busco la revista del articulo seleccionado<br>
                <b>Entonces</b> visualizo su nivel de forma clara y precisa.
            </td>
            <td>EP04</td>
        </tr>
        <tr>
            <td>US25</td>
            <td>Exportar referencias bibliográficas desde la plataforma</td>
            <td>Como tesista, quiero poder exportar las referencias bibliográficas de los trabajos académicos para utilizarlas en mis investigaciones.</td>
            <td>
                <b>Scenario 1:</b> Exportación de referencias<br>
                <b>Dado que</b> ingreso a la plataforma Research Guard,<br>
                <b>Cuando</b> selecciono un trabajo académico<br>
                <b>Entonces</b> puedo exportar sus referencias en formatos comunes como APA, MLA, etc.
            </td>
            <td>EP05</td>
        </tr>
        <tr>
            <td>US26</td>
            <td>Filtrar trabajos académicos por autor en la plataforma</td>
            <td>Como tesista, deseo filtrar trabajos académicos por autor para encontrar fácilmente las publicaciones de un autor específico.</td>
            <td>
                <b>Scenario 1:</b> Filtrado por Autor<br>
                <b>Dado que</b> entro a la plataforma Research Guard,<br>
                <b>Cuando</b> ingreso el nombre del autor en el campo de búsqueda<br>
                <b>Entonces</b> se muestran todos los trabajos académicos relacionados con ese autor.
            </td>
            <td>EP01</td>
        </tr>
        <tr>
            <td>US27</td>
            <td>Recibir notificaciones sobre nuevos trabajos de un autor</td>
            <td>Como tesista, quiero recibir notificaciones cuando un autor específico publique un nuevo trabajo académico para estar al tanto de sus últimas investigaciones.</td>
            <td>
                <b>Scenario 1:</b> Notificaciones de nuevos trabajos<br>
                <b>Dado que</b> sigo a un autor,<br>
                <b>Cuando</b>  ese autor publique un nuevo trabajo académico,<br>
                <b>Entonces</b> recibo una notificación en mi perfil o correo electrónico, según mis preferencias de configuración.
            </td>
            <td>EP01</td>
        </tr>
        <tr>
            <td>US28</td>
            <td>Crear grupos de investigación en la plataforma</td>
            <td>Como autor, deseo crear grupos de investigación en la plataforma para colaborar y compartir recursos con otros investigadores en un proyecto específico.</td>
            <td>
                <b>Scenario 1:</b> Creación de grupos<br>
                <b>Dado que</b> soy un autor registrado,<br>
                <b>Cuando</b>  creo un nuevo grupo de investigación,<br>
                <b>Entonces</b>  puedo invitar a otros usuarios a unirse al grupo y colaborar en un entorno seguro y privado.
            </td>
            <td>EP03</td>
        </tr>
        <tr>
            <td>US29</td>
            <td>Acceder a métricas de impacto de trabajos académicos</td>
            <td>Como tesista, acceder a métricas de impacto (citas, descargas, etc.) de trabajos académicos para evaluar su relevancia e influencia en la comunidad académica.</td>
            <td>
                <b>Scenario 1:</b>Métricas de impacto<br>
                <b>Dado que</b> accedo a un trabajo académico,<br>
                <b>Cuando</b>  navego por las métricas de impacto,<br>
                <b>Entonces</b>  puedo ver estadísticas actualizadas sobre citas, descargas u otras métricas relevantes.
            </td>
            <td>EP02</td>
        </tr>
        <tr>
            <td>US30</td>
            <td>Roles y permisos</td>
            <td>Como usuario, quiero que la interfaz muestre únicamente las funcionalidades relevantes para mi rol, para poder acceder fácilmente a las herramientas que necesito sin distracciones innecesarias.</td>
            <td>
                <b>Scenario 1:</b> Ingreso a la plataforma como tesista<br>
                <b>Dado que</b> creé una cuenta como tesista<br>
                <b>Cuando</b> inicie sesión<br>
                <b>Entonces</b> tendré acceso a todas las funcionalidades de un tesista.
                <br><br>
                <b>Scenario 2:</b> Ingreso a la plataforma como Autor<br>
                <b>Dado que</b> creé una cuenta como autor<br>
                <b>Cuando</b> inicie sesión <br>
                <b>Entonces</b> tendré acceso a todas las funcionalidades de un autor.
            </td>
            <td>EP01</td>
        </tr>
        <tr>
            <td>US31</td>
            <td>Aceptación de la investigación</td>
            <td>Como autor, quiero tener la capacidad de confirmar el proceso de revisión de una investigación, para que pueda ser almacenada de manera segura en el repositorio académico y avanzar con el siguiente paso en el proceso de publicación.</td>
            <td>
                <b>Scenario 1:</b> Confirmación exitosa<br>
                <b>Dado que</b> se ha terminado de revisar una investigación<br>
                <b>Cuando</b> el autor confirme la publicación del estudio<br>
                <b>Entonces</b> se muestra un mensaje indicando que el estudio ha sido almacenado en un repositorio académico de manera exitosa.
                <br><br>
                <b>Scenario 2:</b> Confirmación Pendiente<br>
                <b>Dado que</b> se ha terminado de revisar una investigación<br>
                <b>Cuando</b> el autor confirme la publicación del estudio<br>
                <b>Entonces</b> el sistema muestra un mensaje indicando que la investigación está en proceso de ser almacenada en el repositorio académico.
            </td>
            <td>EP01</td>
        </tr>
        <tr>
            <td>US32</td>
            <td>Colaboración en la revisión de investigaciones</td>
            <td>Como autor, quiero poder discutir y colaborar con otros revisores sobre investigaciones específicas para garantizar una evaluación completa y justa.</td>
            <td>
                <b>Scenario 1:</b> Inicio de una discusión<br>
                <b>Dado que</b> el autor tiene asignada una investigación para revisarla<br>
                <b>Cuando</b> requiere una opinión adicional<br>
                <b>Entonces</b> solicita la colaboración de otro autor.
                <br><br>
                <b>Scenario 2:</b> Respuesta a comentarios<br>
                <b>Dado que</b> Un autor está revisando una investigación en conjunto con otro<br>
                <b>Cuando</b> tiene un observación o comentario<br>
                <b>Entonces</b> la envía a su compañero.
            </td>
            <td>EP03</td>
        </tr>
        <tr>
            <td>US33</td>
            <td>Visualización del plazo de revisión</td>
            <td>Como autor, deseo poder visualizar claramente el plazo de tiempo restante para revisar una investigación asignada, para gestionar eficientemente mi tiempo.</td>
            <td>
                <b>Scenario 1:</b> Plazo restante<br>
                <b>Dado que</b> el autor desea ver cuánto tiempo le queda para revisar una investigación<br>
                <b>Cuando</b> selecciona la investigación asignada<br>
                <b>Entonces</b> el sistema muestra información relevante de la investigación como las fechas importantes.
                <br><br>
                <b>Scenario 2:</b> Extensión de plazo<br>
                <b>Dado que</b> el autor desea extender el plazo de revisión de una investigación<br>
                <b>Cuando</b> solicita la extensión<br>
                <b>Entonces</b> el sistema actualiza las fechas importantes de la revisión. 
            </td>
            <td>EP03</td>
        </tr>
        <tr>
            <td>US34</td>
            <td>Acceso a investigaciones en múltiples formatos</td>
            <td>Como autor, deseo acceder y descargar las investigaciones en una variedad de formatos, como PDF, Word o LaTeX, para poder revisarlas de manera conveniente y eficiente.</td>
            <td>
                <b>Scenario 1:</b> Descarga en PDF<br>
                <b>Dado que</b> el autor se encuentra en la vista de revisión de una investigación<br>
                <b>Cuando</b> selecciona la opción "Descargar archivo como pdf"<br>
                <b>Entonces</b> el archivo se descarga en el formato especificado.
                <br><br>
                <b>Scenario 2:</b> Descarga en Word<br>
                <b>Dado que</b> el autor se encuentra en la vista de revisión de una investigación<br>
                <b>Cuando</b> selecciona la opción "Descargar archivo como documento word"<br>
                <b>Entonces</b> el archivo se descarga en el formato especificado.
            </td>
            <td>EP03</td>
        </tr>
        <tr>
            <td>US35</td>
            <td>Ordenar resultados por fecha</td>
            <td>Como usuario quiero tener la opción de ordenar los resultados de búsqueda por fecha para identificar los papers más recientes en mi campo de estudio.</td>
            <td>
                <b>Scenario 1:</b> Aplicación de ordenamiento de publicación por fecha <br>
                <b>Dada</b> una búsqueda realizada en la plataforma <br>
                <b>Cuando</b> el usuario selecciona la opción de ordenar los resultados por fecha <br>
                <b>Entonces</b> se muestran las publicaciones ordenadas de más reciente a más antiguo.
            </td>
            <td>EP02</td>
        </tr>
    </tbody>
</table>

# Impact Mapping


# Product Backlog

<table>
    <thead>
        <tr>
            <th># Orden</th>
            <th>User Story Id</th>
            <th>Título</th>
            <th>Descripción</th>
            <th>Story Points (1 / 2 / 3 / 5 / 8)</th>
        </tr>
    </thead>
    <tbody>
        <tr>
            <td>1</td>
            <td>US12</td>
            <td>Leer paper completo </td>
            <td>Como usuario quiero leer el paper completo para poder tener toda la información del paper</td>
            <td>5</td>
        </tr>
        <tr>
            <td>2</td>
            <td>US07</td>
            <td>Buscar por palabras clave </td>
            <td>Como usuario deseo eliminar mi cuenta para borrar todos los datos de la aplicación</td>
            <td>5</td>
        </tr>
        <tr>
            <td>3</td>
            <td>US08</td>
            <td>Filtrar resultados por fecha </td>
            <td>Como usuario quiero filtrar los resultados de búsqueda por fecha de publicación para acceder a papers recientes</td>
            <td>3</td>
        </tr>
        <tr>
            <td>4</td>
            <td>US09</td>
            <td>Filtrar resultados por tipo </td>
            <td>Como usuario quiero filtrar los resultados de búsqueda por tipo para acceder a papers recientes</td>
            <td>2</td>
        </tr>
        <tr>
            <td>5</td>
            <td>US11</td>
            <td>Ordenar resultados por relevancia </td>
            <td>Como usuario quiero tener la opción de ordenar los resultados de búsqueda por relevancia para identificar los papers más influyentes en mi campo de estudio</td>
            <td>1</td>
        </tr>
         <tr>
            <td>6</td>
            <td>US10</td>
            <td>Filtrar resultados por idioma </td>
            <td>Como usuario quiero filtrar los resultados de búsqueda por idioma para acceder a papers relevantes en un idioma en específico</td>
            <td>1</td>
        </tr>
        <tr>
            <td>7</td>
            <td>US13</td>
            <td>Guardado de papers </td>
            <td>Como usuario quiero poder guardar mis búsquedas anteriores en PaperVault para poder retomar la exploración ahorrando tiempo</td>
            <td>3</td>
        </tr>
        <tr>
            <td>8</td>
            <td>US14</td>
            <td>Subir investigación</td>
            <td>Como tesista, deseo solicitar la revisión de mi investigación para saber si va a ser aprobada.</td>
            <td>5</td>
        </tr>
        <tr>
            <td>9</td>
            <td>US22</td>
            <td>Seguimiento del proceso</td>
            <td>Como tesista, quiero poder rastrear el estado de la revisión de mi investigación en tiempo real, para tener una visión clara del progreso y estar informado sobre cualquier actualización o cambio en el proceso de revisión.</td>
            <td>3</td>
        </tr>
        <tr>
            <td>10</td>
            <td>US30</td>
            <td>Roles y permisos</td>
            <td>Como usuario, quiero que la interfaz muestre únicamente las funcionalidades relevantes para mi rol, para poder acceder fácilmente a las herramientas que necesito sin distracciones innecesarias.</td>
            <td>5</td>
        </tr>
        <tr>
            <td>11</td>
            <td>US31</td>
            <td>Aceptación de la investigación</td>
            <td>Como autor, quiero tener la capacidad de confirmar el proceso de revisión de una investigación, para que pueda ser almacenada de manera segura en el repositorio académico y avanzar con el siguiente paso en el proceso de publicación.</td>
            <td>8</td>
        </tr>
        <tr>
            <td>12</td>
            <td>US32</td>
            <td>Colaboración en la revisión de investigaciones</td>
            <td>Como autor, quiero poder discutir y colaborar con otros revisores sobre investigaciones específicas para garantizar una evaluación completa y justa.</td>
            <td>5</td>
        </tr>
        <tr>
            <td>13</td>
            <td>US33</td>
            <td>Visualización del plazo de revisión</td>
            <td>Como autor, deseo poder visualizar claramente el plazo de tiempo restante para revisar una investigación asignada, para gestionar eficientemente mi tiempo.</td>
            <td>2</td>
        </tr>
        <tr>
            <td>14</td>
            <td>US34</td>
            <td>Acceso a investigaciones en múltiples formatos</td>
            <td>Como autor, deseo acceder y descargar las investigaciones en una variedad de formatos, como PDF, Word o LaTeX, para poder revisarlas de manera conveniente y eficiente.</td>
            <td>3</td>
        </tr>
        <tr>
            <td>15</td>
            <td>US18</td>
            <td>Herramientas de detección de plagio</td>
            <td>Como autor quiero tener acceso a herramientas de detección de plagio para verificar la originalidad de mis trabajos de investigación para garantizar su calidad y credibilidad.</td>
            <td>8</td>
        </tr>
        <tr>
            <td>16</td>
            <td>US28</td>
            <td>Crear grupos de investigación en la plataforma</td>
            <td>Como autor, deseo crear grupos de investigación en la plataforma para colaborar y compartir recursos con otros investigadores en un proyecto específico.</td>
            <td>5</td>
        </tr>
        <tr>
            <td>17</td>
            <td>US29</td>
            <td>Acceder a métricas de impacto de trabajos académicos</td>
            <td>Como tesista, acceder a métricas de impacto (citas, descargas, etc.) de trabajos académicos para evaluar su relevancia e influencia en la comunidad académica.</td>
            <td>5</td>
        </tr>
        <tr>
            <td>18</td>
            <td>US17</td>
            <td>Colaboraciones y redes con otros investigadores</td>
            <td>Cómo autor quiero establecer colaboraciones y redes con otros investigadores en mi campo de estudio para fomentar la colaboración y el intercambio de conocimientos en la comunidad académica.</td>
            <td>5</td>
        </tr>
        <tr>
            <td>19</td>
            <td>US19</td>
            <td>Comentar y discutir investigaciones</td>
            <td>Como usuario quiero poder comentar y discutir investigaciones en la plataforma para participar en la comunidad académica y enriquecer mi comprensión del tema.</td>
            <td>5</td>
        </tr>
        <tr>
            <td>20</td>
            <td>US23</td>
            <td>Verificar indexación de revistas en la plataforma</td>
            <td>Como tesista, quiero poder verificar si una revista académica está indexada para evaluar su calidad.</td>
            <td>5</td>
        </tr>
        <tr>
            <td>21</td>
            <td>US24</td>
            <td>Ver el nivel de las revistas en la plataforma</td>
            <td>Como tesista, deseo conocer el nivel de las revistas académicas para evaluar su prestigio.</td>
            <td>1</td>
        </tr>
        <tr>
            <td>22</td>
            <td>US21</td>
            <td>Gestionar perfil</td>
            <td>Como usuario quiero gestionar mi perfil para mostrar mi trayectoria académica y mejorar mi credibilidad la comunidad académica.</td>
            <td>3</td>
        </tr>
        <tr>
            <td>23</td>
            <td>US35</td>
            <td>Ordenar resultados por fecha</td>
            <td>Como usuario quiero tener la opción de ordenar los resultados de búsqueda por fecha para identificar los papers más recientes en mi campo de estudio.</td>
            <td>3</td>
        </tr>
        <tr>
            <td>24</td>
            <td>US15</td>
            <td>Notificaciones sobre nuevas investigaciones relevantes</td>
            <td>Cómo autor quiero recibir notificaciones sobre nuevas investigaciones relevantes en mi campo de estudio para estar al tanto de los avances en la investigación</td>
            <td>1</td>
        </tr>
        <tr>
            <td>25</td>
            <td>US25</td>
            <td>Exportar referencias bibliográficas desde la plataforma</td>
            <td>Como tesista, quiero poder exportar las referencias bibliográficas de los trabajos académicos para utilizarlas en mis investigaciones.</td>
            <td>3</td>
        </tr>
        <tr>
            <td>26</td>
            <td>US27</td>
            <td>Recibir notificaciones sobre nuevos trabajos de un autor</td>
            <td>Como tesista, quiero recibir notificaciones cuando un autor específico publique un nuevo trabajo académico para estar al tanto de sus últimas investigaciones.</td>
            <td>3</td>
        </tr>
        <tr>
            <td>27</td>
            <td>US26</td>
            <td>Filtrar trabajos académicos por autor en la plataforma</td>
            <td>Como tesista, deseo filtrar trabajos académicos por autor para encontrar fácilmente las publicaciones de un autor específico.</td>
            <td>1</td>
        </tr>
        <tr>
            <td>28</td>
            <td>US16</td>
            <td>Notificaciones automáticas sobre el estado de revisión</td>
            <td>Como autor quiero recibir notificaciones automáticas sobre el estado de revisión de mis trabajos de investigación para mantenerme actualizado sobre su progreso.</td>
            <td>1</td>
        </tr>
        <tr>
            <td>29</td>
            <td>US20</td>
            <td>Recibir notificaciones sobre comentarios</td>
            <td>Como autor quiero recibir notificaciones sobre comentarios de mis investigaciones para estar al tanto del feedback de la comunidad académica.</td>
            <td>1</td>
        </tr>
        <tr>
            <td>30</td>
            <td>US01</td>
            <td>Registrar cuenta</td>
            <td>Como usuario deseo registrar una cuenta para crear mi perfil.</td>
            <td>5</td>
        </tr>
        <tr>
            <td>31</td>
            <td>US02</td>
            <td>Iniciar sesión</td>
            <td>Como usuario deseo iniciar sesión para acceder a la aplicación.</td>
            <td>3</td>
        </tr>
        <tr>
            <td>32</td>
            <td>US03</td>
            <td>Cerrar sesión</td>
            <td>Como usuario deseo cerrar sesión para salir de mi cuenta.</td>
            <td>1</td>
        </tr>
        <tr>
            <td>33</td>
            <td>US04</td>
            <td>Correo electrónico para cambiar contraseña</td>
            <td>Como usuario deseo enviar un correo electrónico para cambiar mi contraseña</td>
            <td>3</td>
        </tr>
        <tr>
            <td>34</td>
            <td>US05</td>
            <td>Cambiar contraseña</td>
            <td>Como usuario deseo cambiar mi contraseña para acceder nuevamente a mi cuenta.</td>
            <td>3</td>
        </tr>
        <tr>
            <td>35</td>
            <td>US06</td>
            <td>Eliminar cuenta</td>
            <td>Como usuario deseo eliminar mi cuenta para borrar todos los datos de la aplicación</td>
            <td>1</td>
        </tr>
    </tbody>
</table>