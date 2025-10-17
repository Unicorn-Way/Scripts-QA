## Test case: Flujo de compra

**Historia de usuario:**  
Como cliente registrado, quiero poder comprar productos fácilmente para completar mis pedidos sin errores.

**ID:** TC005
**Titulo:** Validar que el usuario pueda realizar una compra sin problemas
**Módulo:** E-commerce
**Prioridad:** Alta
**Tipo:** Funcional

## Precondiciones

- Usuario Logueado y registrado
- Tener al menos un producto en el carrito

## Pasos

1. Seleccionar un producto del catalogo
2. Agregarlo al carrito
3. Ir al carrito y proceder al checkout
4. Ingresar informacion de pago válida
5. Confirmar compra

## Resultado esperado

- Pedido completado con éxito
- Número de orden visible
- Correo de confirmacion enviado

## Estado

- passed