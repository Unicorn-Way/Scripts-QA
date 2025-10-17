## Test case: Inicio de sesion con credenciales inválidas

**historia de usuario:** Como usuario del sistema, quiero recibir un mensaje de error cuando ingrese credenciales incorrectas, para saber que debo intentar nuevamente o recuperar mi contraseña.

**ID:** TC002
**Titulo:** Verificar que no se pueda acceder al sistema sin estar registrado
**Módulo:** Autenticación
**Prioridad:** alta
**Tipo:** Funcional

## Precondiciones

- El usuario se encuentra en la página de login

## Datos

**Usuario:** Usuario@ejemplo.com
**Contraseña:** Contraseña-incorrecta

## Pasos

1. Abrir la página de login
2. Escribir correo inválido en campo 'email'
3. Escribir contraseña invalida en campo 'contraseña'
4. Hacer click en boton 'Iniciar Sesion'

## Resultado esperado

- Sistema muestra el mensaje 'La contraseña o el correo son incorrectos'
- El usuario permanece en la pagina de login, sin acceso al sistema

## Estado

Passed