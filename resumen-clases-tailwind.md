## **📌 Clases utilizadas en cada sección y su función**

Aquí tienes un **listado-resumen** de las clases de Tailwind utilizadas en cada sección del proyecto, junto con su explicación basada en la documentación de **Tailwind CSS 3**.

---

### **1️⃣ Navbar (Barra de navegación)**
```html
<nav class="bg-gray-900 p-4 fixed w-full top-0 z-50">
```
- `bg-gray-900`: Fondo gris oscuro.
- `p-4`: Padding de 1rem (16px).
- `fixed`: Fija el navbar en la parte superior.
- `w-full`: Ocupa el 100% del ancho.
- `top-0`: Se posiciona en la parte superior de la página.
- `z-50`: Asegura que el navbar esté sobre otros elementos.

```html
<ul class="hidden md:flex space-x-6">
```
- `hidden`: Oculta el menú en pantallas pequeñas.
- `md:flex`: Muestra el menú como un `flexbox` en pantallas medianas (≥768px).
- `space-x-6`: Agrega un margen horizontal de 1.5rem (24px) entre elementos.

```html
<div id="mobile-menu" class="hidden md:hidden bg-slate-800 p-4 mt-4">
```
- `hidden md:hidden`: Oculta el menú móvil en todos los tamaños (se muestra con JS).
- `bg-slate-800`: Fondo gris azulado oscuro.
- `p-4`: Padding interno de 1rem (16px).
- `mt-4`: Margen superior de 1rem (16px).

---

### **2️⃣ Hero Section (Sección de introducción)**
```html
<section id="hero" class="bg-gray-900">
```
- `bg-gray-900`: Fondo gris oscuro.

```html
<div class="container px-3 pt-20 md:pt-40 lg:pt-0 mx-auto flex flex-wrap flex-col md:flex-row items-center">
```
- `container`: Limita el ancho y centra el contenido.
- `px-3`: Padding horizontal de 12px.
- `pt-20 md:pt-40 lg:pt-0`: Padding superior de 5rem (80px) en móvil, 10rem (160px) en tablet y 0 en pantallas grandes.
- `mx-auto`: Centra el contenido.
- `flex flex-wrap flex-col md:flex-row items-center`: Usa `flexbox` con dirección columna en móvil y fila en pantallas medianas.

```html
<h1 class="my-4 text-4xl md:text-5xl font-bold leading-tight">
```
- `my-4`: Margen vertical de 16px.
- `text-4xl md:text-5xl`: Tamaño de fuente 2.25rem en móvil y 3rem en tablet.
- `font-bold`: Texto en negrita.
- `leading-tight`: Reduce la altura de línea.

---

### **3️⃣ Sección "¿Por qué elegirnos?"**
```html
<section id="about" class="py-8 md:py-16 px-6 text-center">
```
- `py-8 md:py-16`: Padding vertical de 2rem (32px) en móvil y 4rem (64px) en tablet.
- `px-6`: Padding horizontal de 1.5rem (24px).
- `text-center`: Texto centrado.

```html
<h2 class="w-full my-2 text-3xl lg:text-5xl font-bold leading-tight text-center text-teal-500">
```
- `w-full`: Ocupa el ancho completo.
- `my-2`: Margen vertical de 8px.
- `text-3xl lg:text-5xl`: Fuente de 1.875rem en móvil y 3rem en pantallas grandes.
- `text-teal-500`: Color verde azulado.

```html
<div class="h-1 mx-auto bg-white w-64 md:w-96 opacity-25 my-0 py-0 rounded-t"></div>
```
- `h-1`: Altura de 4px.
- `mx-auto`: Centrado horizontal.
- `bg-white`: Fondo blanco.
- `w-64 md:w-96`: Ancho de 16rem en móvil y 24rem en tablet.
- `opacity-25`: Opacidad al 25%.
- `rounded-t`: Bordes superiores redondeados.

---

### **4️⃣ Testimonios con Slider**
```html
<section id="testimonials" class="bg-slate-800">
```
- `bg-slate-800`: Fondo gris azulado oscuro.

```html
<div class="mt-6 flex space-x-4 overflow-x-auto p-4 snap-x">
```
- `mt-6`: Margen superior de 24px.
- `flex`: Usa `flexbox`.
- `space-x-4`: Espacio horizontal de 16px entre elementos.
- `overflow-x-auto`: Scroll horizontal activado.
- `p-4`: Padding de 16px.
- `snap-x`: Habilita desplazamiento con snapping en eje X.

```html
<div class="p-6 bg-slate-900 rounded-lg shadow-lg min-w-[250px] snap-center">
```
- `p-6`: Padding de 24px.
- `bg-slate-900`: Fondo gris oscuro.
- `rounded-lg`: Bordes redondeados.
- `shadow-lg`: Sombra grande.
- `min-w-[250px]`: Mínimo ancho de 250px.
- `snap-center`: Centra el elemento en scroll.

---

### **5️⃣ Formulario de Inscripción**
```html
<form class="mt-6 max-w-md mx-auto bg-slate-800 p-6 rounded-lg shadow-lg">
```
- `mt-6`: Margen superior de 24px.
- `max-w-md`: Ancho máximo de 28rem (448px).
- `mx-auto`: Centrado horizontal.
- `bg-slate-800`: Fondo gris oscuro.
- `p-6`: Padding de 24px.
- `rounded-lg`: Bordes redondeados.
- `shadow-lg`: Sombra grande.

```html
<button class="w-full bg-indigo-500 hover:bg-indigo-600 p-3 rounded font-semibold">
```
- `w-full`: Ocupa todo el ancho disponible.
- `bg-indigo-500 hover:bg-indigo-600`: Fondo azul índigo con efecto hover.
- `p-3`: Padding de 12px.
- `rounded`: Bordes redondeados.
- `font-semibold`: Texto en negrita.

---

### **6️⃣ Preguntas Frecuentes**
```html
<section id="faq" class="px-5 bg-gray-900 min-h-screen">
```
- `px-5`: Padding horizontal de 20px.
- `bg-gray-900`: Fondo gris oscuro.
- `min-h-screen`: Mínimo alto igual a la pantalla.

```html
<div class="grid divide-y divide-neutral-200 w-10/12 mx-auto mt-8">
```
- `grid`: Usa `grid layout`.
- `divide-y divide-neutral-200`: Agrega líneas divisorias en eje Y con color gris claro.
- `w-10/12`: Ocupa 10/12 del ancho total.
- `mx-auto`: Centrado horizontal.
- `mt-8`: Margen superior de 32px.

```html
<details class="group">
    <summary class="flex justify-between items-center font-medium cursor-pointer list-none">
```
- `group`: Permite estilos condicionales en los elementos hijos.
- `flex justify-between items-center`: Usa `flexbox` para separar el texto del icono.
- `font-medium`: Texto con grosor intermedio.
- `cursor-pointer`: Cambia el cursor a puntero.
- `list-none`: Elimina el estilo de lista.

---

### **7️⃣ Footer**
```html
<footer class="bg-slate-800 py-6 text-center">
```
- `bg-slate-800`: Fondo gris azulado oscuro.
- `py-6`: Padding vertical de 24px.
- `text-center`: Texto centrado.

---

## **📌 Resumen**
Este código usa **Tailwind CSS 3** para:
✔ Hacer el diseño **responsive** con `flex`, `grid` y `media queries`.  
✔ Aplicar **colores y fondos oscuros** (`bg-gray-900`, `bg-slate-800`).  
✔ Agregar **sombras y efectos visuales** (`shadow-lg`, `rounded-lg`).  
✔ Mejorar la **experiencia de usuario** (`hover`, `overflow-x-auto`, `snap-x`).  

