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
            <td>Autenticación</td>
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
            <td>Como usuario, deseo solicitar la revisión de mis investigaciones para que sea evaluada para su publicación en una revista académica.</td>
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
                <b>Scenario 1:</b> Aplicación de filtros por fecha de publicación <br>
                <b>Dada</b> una búsqueda realizada en la plataforma <br>
                <b>Cuando</b> el usuario selecciona un rango de fechas <br>
                <b>Y</b> presiona el botón de filtrar <br>
                <b>Entonces</b> se muestran las publicaciones con fechas dentro del rango establecido.
            </td>
            <td>EP02</td>
        </tr>
        <tr>
            <td>US16</td>
            <td>Notificaciones automáticas sobre el estado de revisión</td>
            <td>Como autor quiero recibir notificaciones automáticas sobre el estado de revisión de mis trabajos de investigación para mantenerme actualizado sobre su progreso.</td>
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
            <td>US17</td>
            <td>Colaboraciones y redes con otros investigadores</td>
            <td>Cómo autor quiero establecer colaboraciones y redes con otros investigadores en mi campo de estudio para fomentar la colaboración y el intercambio de conocimientos en la comunidad académica.</td>
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
            <td>US18</td>
            <td>Herramientas de detección de plagio</td>
            <td>Como autor quiero tener acceso a herramientas de detección de plagio para verificar la originalidad de mis trabajos de investigación para garantizar su calidad y credibilidad.</td>
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
            <td>US19</td>
            <td>Comentar y discutir investigaciones</td>
            <td>Como usuario quiero poder comentar y discutir investigaciones en la plataforma para participar en la comunidad académica y enriquecer mi comprensión del tema.</td>
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
            <td>US20</td>
            <td>Recibir notificaciones sobre comentarios</td>
            <td>Como autor quiero recibir notificaciones sobre comentarios de mis investigaciones para estar al tanto del feedback de la comunidad académica.</td>
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
            <td>US21</td>
            <td>Gestionar perfil</td>
            <td>Como usuario quiero gestionar mi perfil para mostrar mi trayectoria académica y mejorar mi credibilidad la comunidad académica.</td>
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
            <td>25</td>
            <td>US01</td>
            <td>Registrar cuenta</td>
            <td>Como usuario deseo registrar una cuenta para crear mi perfil.</td>
            <td>5</td>
        </tr>
        <tr>
            <td>26</td>
            <td>US02</td>
            <td>Iniciar sesión</td>
            <td>Como usuario deseo iniciar sesión para acceder a la aplicación.</td>
            <td>3</td>
        </tr>
        <tr>
            <td>27</td>
            <td>US03</td>
            <td>Cerrar sesión</td>
            <td>Como usuario deseo cerrar sesión para salir de mi cuenta.</td>
            <td>1</td>
        </tr>
        <tr>
            <td>28</td>
            <td>US04</td>
            <td>Correo electrónico para cambiar contraseña</td>
            <td>Como usuario deseo enviar un correo electrónico para cambiar mi contraseña</td>
            <td>3</td>
        </tr>
        <tr>
            <td>29</td>
            <td>US05</td>
            <td>Cambiar contraseña</td>
            <td>Como usuario deseo cambiar mi contraseña para acceder nuevamente a mi cuenta.</td>
            <td>3</td>
        </tr>
        <tr>
            <td>30</td>
            <td>US06</td>
            <td>Eliminar cuenta</td>
            <td>Como usuario deseo eliminar mi cuenta para borrar todos los datos de la aplicación</td>
            <td>1</td>
        </tr>
        <tr>
            <td></td>
            <td>US07</td>
            <td>Buscar por palabras clave </td>
            <td>Como usuario deseo eliminar mi cuenta para borrar todos los datos de la aplicación</td>
            <td>5</td>
        </tr>
        <tr>
            <td></td>
            <td>US08</td>
            <td>Filtrar resultados por fecha </td>
            <td>Como usuario quiero filtrar los resultados de búsqueda por fecha de publicación para acceder a papers recientes</td>
            <td>3</td>
        </tr>
        <tr>
            <td></td>
            <td>US09</td>
            <td>Filtrar resultados por tipo </td>
            <td>Como usuario quiero filtrar los resultados de búsqueda por tipo para acceder a papers recientes</td>
            <td>2</td>
        </tr>
        <tr>
            <td></td>
            <td>US10</td>
            <td>Filtrar resultados por idioma </td>
            <td>Como usuario quiero filtrar los resultados de búsqueda por idioma para acceder a papers relevantes en un idioma en específico</td>
            <td>1</td>
        </tr>
        <tr>
            <td></td>
            <td>US11</td>
            <td>Ordenar resultados por relevancia </td>
            <td>Como usuario quiero tener la opción de ordenar los resultados de búsqueda por relevancia para identificar los papers más influyentes en mi campo de estudio</td>
            <td>1</td>
        </tr>
        <tr>
            <td></td>
            <td>US12</td>
            <td>Leer paper completo </td>
            <td>Como usuario quiero leer el paper completo para poder tener toda la información del paper</td>
            <td>5</td>
        </tr>
        <tr>
            <td></td>
            <td>US13</td>
            <td>Guardado de papers </td>
            <td>Como usuario quiero poder guardar mis búsquedas anteriores en PaperVault para poder retomar la exploración ahorrando tiempo</td>
            <td>3</td>
        </tr>
    </tbody>
</table>