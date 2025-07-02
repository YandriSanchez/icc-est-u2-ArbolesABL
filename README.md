# Práctica Arboles AVL

## 📌 Información General

- **Título:** Práctica Arboles AVL
- **Asignatura:** Estructura de Datos
- **Carrera:** Computación
- **Estudiante:** Yandri Eduardo Sanchez Yanza
- **Fecha:** 01/07/2025
- **Profesor:** Ing. Pablo Torres

---

## 🛠️ Descripción


Este proyecto implementa una estructura de datos tipo **Árbol AVL**, utilizando una arquitectura modular compuesta por dos clases principales:

### 📁 Estructura del Proyecto

- `AVLTree.java`: Clase encargada de gestionar el árbol, incluyendo inserciones, cálculo de altura, balanceo y rotaciones.
- `Node.java`: Representa un nodo individual del árbol, con atributos para el valor, la altura y sus hijos izquierdo y derecho.

---

### ⚙️ Funcionalidades Principales

- **Inserción dinámica:** Inserta un valor entero en su posición ordenada dentro del árbol.
- **Altura y balanceo automáticos:** Cada nodo actualiza su altura tras cada inserción y se verifica su balance.
- **Rotaciones AVL:** Cuando se detecta un desbalance, se aplica una de estas rotaciones:
  - LL: Rotación simple a la derecha.
  - RR: Rotación simple a la izquierda.
  - LR: Rotación doble izquierda-derecha.
  - RL: Rotación doble derecha-izquierda.
- **Mensajes por consola:** El sistema imprime cada operación realizada para facilitar la depuración:
  - Valor insertado.
  - Altura y balance del nodo actual.
  - Tipo de rotación aplicada si es necesario.

---

### 🧠 Lógica Interna

- El método `insert()` llama internamente a `insertRec()`, que se encarga de:
  - Navegar recursivamente por el árbol.
  - Insertar el nuevo nodo.
  - Recalcular las alturas.
  - Detectar si se rompe el balance.
  - Corregirlo con la rotación correspondiente.

- Las rotaciones se implementan en métodos separados `rotateLeft()` y `rotateRight()` que:
  - Reasignan punteros de hijos.
  - Actualizan las alturas.
  - Devuelven el nuevo subárbol raíz.


---

## 🚀 Ejecución

Para ejecutar el proyecto:

1. Compila el código:
    ```bash
    javac App.java
    ```
2. Ejecuta la aplicación:
    ```bash
    java App
    ```

---

## 🧑‍💻 Ejemplo de Entrada


---

## 🧑‍💻 Ejemplo de Salida

![Image](https://github.com/user-attachments/assets/957c5c05-50c8-45bf-8d72-e2501c6bbb9b)

---

