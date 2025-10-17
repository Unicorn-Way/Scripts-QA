## Test case: Validacion de correo y contraseña

**Historia de usuario:** Como nuevo usuario, quiero que el sistema valide los requisitos de la contraseña durante el registro, para garantizar la seguridad de mi cuenta.

## Criterios de aceptacion

- La contraseña debe tener al menos 8 caracteres.
- Debe incluir al menos una letra mayúscula, una minúscula, un número y un carácter especial (! @ # $ % ^ & *).
- No debe contener espacios ni caracteres no permitidos.
- La confirmación de la contraseña debe coincidir exactamente con la contraseña ingresada.

**ID:** TC004
**Titulo:** Verificar validación de contraseña durante el registro
**Módulo:** Autenticación
**Prioridad:** Alta
**Tipo:** Funcional

## Precondiciones

- El usuario se encuentra en la pagina de registro

## Pasos

1. Abrir pagina de registro
2. ingresar datos de usuario
3. ingresar la contraseña valida
4. Confirmar la contraseña
5. Hacer clic en 'Registrarse'

## Resultado esperado

El sistema muestra mensajes claros segun la validacion:

- Si la contraseña cumple todos los criterios se confirma el registro
- Si no cumple muestra mensaje de error: 'La contraseña debe tener al menos 8 caracteres y un carácter especial'
- En caso de que cumpla con los criterios de aceptacion el usuario es redirigido a la pagina de login
- Solo las contraseñas validas permiten crear una cuenta


## Estado

- Passed