# Carrito de tienda online de guitarras

## Descripción General

una página web de compras en línea construida con Vue.js. Permite a los usuarios explorar productos, agregarlos al carrito, ajustar la moneda de visualización y elegir la moneda requerida. Aquí hay una guía para entender cómo funciona. 

## 1. Estructura del Código

- **index.html**: Define la estructura de la página.
- **app.js**: Contiene la lógica de Vue.js para la aplicación y manejo de datos.
- **productos-data.js**: Contiene datos de productos simulados.
- **style (carpeta)**: Contiene estilos visuales en CSS.

## 2. Componentes Vue.js

1. **Navbar**: Barra de navegación con enlaces a "Productos" y "Carrito".
2. **CurrencyDropdown**: Lista desplegable para seleccionar y elegir la moneda de visualización.
3. **Productos**: Página de lista de productos.
4. **ProductoCard**: Tarjeta visual de un producto con botón para agregar al carrito.
5. **Carrito**: Página del carrito con gestión de productos.

## 3. Uso de la Aplicación

1. **Explorar Productos**:
   - Hacer clic en "Productos" para ver la lista de productos.
   - Cada tarjeta tiene detalles y un botón para agregar al carrito.

2. **Agregar al Carrito**:
   - Desde "Productos", hacer clic en "Add to Cart".
   - Ajustar cantidades y eliminar productos en "Carrito".

3. **Gestión del Carrito**:
   - Ir a "Carrito" desde la barra de navegación.
   - Ajustar cantidades y eliminar productos.

4. **Cambio de Moneda**:
   - Usar la lista desplegable para cambiar la moneda de visualización.
   - Elegir la moneda requerida para ver los precios.

## 4. Configuración y Personalización

1. **Datos de Productos**:
   - En "productos-data.js", se pueden modificar o añadir datos de productos.

2. **Estilos Visuales**:
   - Personalizar estilos en la carpeta "style" según el diseño deseado.

3. **API de Tasas de Cambio**:
   - Actualmente utiliza una API simulada. En producción, usar una API real.

## 5. Notas Adicionales

- La aplicación simula operaciones asíncronas para obtener datos y tasas de cambio.
- La gestión del estado se realiza con la instancia de Vue y sus métodos.

¡Disfruta comprando en "Mi Tienda"!
