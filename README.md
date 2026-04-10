# Teclado Numérico con DOM
# 🎹 Ejercicio 1: Teclado Numérico Dinámico

Este proyecto consiste en la creación de un teclado numérico (del 1 al 9) utilizando exclusivamente **JavaScript y la manipulación del DOM**. El objetivo es aprender a generar elementos "en el aire" y colocarlos en la web sin escribir HTML manualmente.

---

## 💡 Conceptos Clave Aprendidos

Para este ejercicio, he aplicado los siguientes conceptos del **DOM (Document Object Model)**:

1. **`document.createElement("div")`**: Crea un nuevo nodo (un elemento) en la memoria del navegador.
2. **`element.style.propiedad`**: Define el diseño directamente desde JS. Hemos usado **camelCase** (ej: `backgroundColor` en lugar de `background-color`).
3. **`element.textContent`**: Inserta el número dentro de cada tecla.
4. **`parent.appendChild(child)`**: Es la acción de "colgar" el elemento creado dentro del contenedor HTML para que sea visible.

---

## 🚀 Retos y Soluciones

### 1. Optimización con Bucles
**Problema:** Crear 9 teclas escribiendo el código una a una es ineficiente y genera mucho código repetido.
**Solución:** He utilizado un **bucle `for`** que recorre del 1 al 9, automatizando la creación de cada tecla en solo unas pocas líneas de código.

### 2. Diseño Responsivo con Flexbox
**Problema:** Por defecto, los `div` se colocan uno debajo de otro.
**Solución:** Apliqué `display: flex` y `flex-wrap: wrap` al contenedor principal. De esta forma, las teclas se alinean horizontalmente y saltan de línea automáticamente cuando no caben (creando la rejilla de 3x3).

---

## 🛠️ Comandos de Git utilizados
* `git init`: Para inicializar el repositorio local.
* `git remote add origin`: Para conectar mi ordenador con GitHub.
* `git add .` / `git commit`: Para guardar mis avances.
* `git push -u origin main`: Para subir todo a la nube.

---
*Apuntes realizados por Ana Hernández - 2026*
https://github.com/AnaBHernandez