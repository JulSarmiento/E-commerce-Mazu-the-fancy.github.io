## URL

## Challenge 

El objetivo de este encuentro es armar una aplicación de un e-commerce, en la cual se:

    - listen productos, 
    - le permita a un/a usuario/a añadir a un carrito aquellos que quiera comprar.
    - El carrito debe permitir que se orden por nombre y por precio.
    - Debe permitirse eliminar un elemento del carrito
    - Debe permitir actualizar el carrito si el usuario compra dos o mas productos, o vuelve a llevar uno solo.
    - El carrito debe tener un botón de Comprar para pasar a pagar los productos seleccionados.

### Productos
    Utiliza un array de productos, donde cada elemento sea un objeto que almacene toda la información que vas a mostrar en
    el diseño de tu sitio.

### Carrito
    Cada vez que un usuario añade un producto a su carrito, almacénalo en el localStorage (te permitirá mantener la
    información si el usuario recarga la página).

### Checkout
    Crea el checkout en 2 pasos:

    1. Solicita sus datos personas y si quiere retirar el producto o debes enviar a su dirección.

    2. El segundo informa los medios de pago que dispones y simula una acción de comprar.
        No olvides limpiar el localStorage si la compra es correcta.

### Divide el proceso de pago en 2 pasos:

        ● Datos personales
        ● Datos de pago
