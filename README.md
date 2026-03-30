# 👨‍💻 Swift Swift Collections - Tecsup 2026

Este repositorio contiene una serie de ejercicios prácticos desarrollados en el **Playground de Xcode**. El objetivo principal es demostrar el manejo de colecciones en Swift (Arrays, Sets y Diccionarios) aplicados a casos reales y proyecciones futuras.

---

## 📚 Contenido de los Ejercicios

### 1. Análisis de Datos Económicos (Arrays)
* **Caso:** Manejo del GDP (Producto Bruto Interno) de países de Sudamérica para el 2025.
* **Lo que aprendí:** * Manipulación de arreglos (`Array`).
    * Cálculo de promedios usando bucles tradicionales y el método funcional `.reduce`.
    * Uso de `indices.sorted` para ordenar datos sin perder la relación entre el país y su valor económico.

### 2. Cronología del Imperio Incaico (Sets)
* **Caso:** Organización de los 14 Incas divididos por las dinastías Hurin y Hanan.
* **Lo que aprendí:** * Uso de `Set` para garantizar que no existan nombres duplicados.
    * Operaciones de conjuntos como `.union()` para fusionar dinastías.
    * Filtrado de datos específicos (Incas con el apelativo "Yupanqui") mediante `.filter`.

### 3. Red del Metro de Lima 2040 (Dictionaries)
* **Caso:** Modelado de las futuras líneas del metro (Líneas 1, 2, 3 y 4).
* **Lo que aprendí:** * Estructura de Diccionarios `[String: [String]]`.
    * Búsqueda inversa (encontrar a qué línea pertenece una estación específica).
    * Manejo de opcionales con `if let` para evitar errores en el sistema.

### 4. Procesador y Traductor de Frases
* **Caso:** Limpieza de conectores y traducción de frases de inglés a castellano.
* **Lo que aprendí:** * Uso de `.split(separator: " ")` para tokenizar frases.
    * Filtrado de palabras prohibidas (conectores como *is, to, in*).
    * Traducción dinámica mediante un diccionario de términos.
    * Creación de funciones con parámetros explícitos `func traducir(frase: String)`.

---

## 🛠️ Tecnologías Utilizadas
* **Lenguaje:** Swift 5.x
* **Herramienta:** Xcode Playground
* **Conceptos:** Programación Funcional, Estructuras de Datos, Algoritmos de Filtrado.

## 🎓 Conclusiones
El desarrollo de estos ejercicios me permitió entender que **Swift** es un lenguaje muy potente cuando se trata de manejar datos. Aprendí que elegir la colección correcta (un Set en lugar de un Array, por ejemplo) puede ahorrar muchas líneas de código y hacer que la aplicación sea más rápida y segura.

---
**Desarrollado por un estudiante de Tecsup - 2026**
