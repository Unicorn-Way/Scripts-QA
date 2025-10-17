## Test case: Restablecimiento de contraseña

**Historia de usuario:**  
Como usuario registrado, quiero poder restablecer mi contraseña en caso de olvidarla para recuperar el acceso a mi cuenta.

**ID:** TC007
**Módulo:** Autenticación
**Prioridad:** Media
**Tipo:** Funcional

## Precondiciones 

- página de login disponible
- Usuario registrado con correo válido

# Datos de entrada

**Usuario:** Usuario123

## Pasos

1. Presionar '¿Olvidaste tu contraseña?'
2. Ingresar correo electronico registrado
3. Recibir email con enlace de restablecimiento
4. escribir nueva contraseña y confirmarla
5. Darle a 'Cambiar contraseña'

## resultado esperado

- Contraseña se restablece exitosamente
- El usuario es redirigido a la página de login
- Usuario puede loguearse con nueva contraseña