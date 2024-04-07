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
    </tbody>
</table>