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
    <tboby>
        <tr>
            <td>EP01</td>
            <td>Autenticación</td>
            <td>Como usuario deseo acceder a mi cuenta personal para entrar a la apliacación.</td>
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
    <tboby>
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
                <b>Cuando</b> el usuario ingresa una contraseña vaálida</br>
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
    </tbody>
</table>

# Impact Mapping


# Product Backlog