# Hito 6 - Pizzería Mamma Mía 🍕
Proyecto correspondiente al Hito 6 de la Academia de Talentos
Digitales de **Desafío Latam**, enfocado en la implementación del
manejo de estado global en aplicaciones web utilizando **React
Context API**.

---
## 📌 Descripción del Proyecto

El objetivo de este hito es implementar el manejo de estado global
en la aplicación web de la **Pizzería Mamma Mía** mediante la
**Context API** de React, permitiendo sincronizar la información del
carrito de compras y del catálogo entre distintas páginas y
componentes.

* **Tema central:** React Context API & Manejo de Estado Global.
---
## 🎯 Requerimientos
1. Context del Carrito de Compras (`Cart Context`):

* Implementar un Context que permita administrar el estado global
del carrito de compras en toda la aplicación. 

2. Integración en Navbar:

* Consumir el `Cart Context` dentro del componente `Navbar` para
mostrar dinámicamente el precio total acumulado de los productos en
el carrito.

3. Agregar productos desde Home:

* Consumir el `Cart Context` en la página principal (`Home`),
permitiendo al usuario añadir productos al carrito haciendo clic en
el botón "Añadir" de cada tarjeta (*card*). 

4. Gestión del Carrito en la página `Cart`:

* Mostrar en la vista `Cart` el listado de productos agregados al
carrito mediante el `Cart Context`.
* Permitir agregar (incrementar) y eliminar/disminuir productos
del carrito. 

5. Cálculo y Sincronización del Total:

* Calcular y desplegar el total de la compra en la página `Cart`,
garantizando que coincida exactamente con el total mostrado en el
`Navbar`. 

6. Context de Pizzas (Opcional):

* Encapsular la lógica de consumo de datos (*fetch* de Home y
Pizza) dentro de un Context dedicado. 
---
## ️ Tecnologías Sugeridas
* **React** (Vite / Create React App)
* **React Context API** (`useContext`, `createContext`)
* **JavaScript (ES6+)**
* **HTML5 & CSS3**
