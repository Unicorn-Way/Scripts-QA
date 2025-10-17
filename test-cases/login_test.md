# Test case: Login de Usuario

**Historia de usuario:**  
Como usuario registrado, quiero poder iniciar sesión en la aplicación para acceder a mi cuenta y usar mis servicios personalizados.


**ID:** TC001
**Titulo:** Validar que el usuario pueda entrar al sistema con credenciales validas
**Módulo:** Autenticación
**Prioridad:** Alta
**tipo:** Funcional

## Precondiciones

- Pestaña de login abierta
- Usuario registrado en el sistema

## Datos de entrada

*Usuario o email:* Usuario123
*Contraseña:* Password123

## Pasos

1. Abrir página de Login
2. Ingresar email válido en campo ´´email o usuario´´
3. Ingresar contraseña válida en campo ´´contraseña´´
4. Presionar botón ´´Iniciar Sesión´´

## Resultado esperado

- El usuario es redirigido a la pestaña ´´dashboard´´
- Mensaje de bienvenida visible que diga ´´Bienvenido de vuelta Usuario´´

## Estado

- Passed ✅