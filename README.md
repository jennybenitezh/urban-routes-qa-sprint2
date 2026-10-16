# 🚗 Proyecto 2: Análisis de Requisitos y Diseño de Pruebas - Urban Routes (Sprint 2)

> 💡 **Nota:** Este proyecto fue desarrollado como parte de mi formación en **QA Engineering en TripleTen**, aplicando técnicas avanzadas de diseño de pruebas: Mapeo Mental, Partición de Clases de Equivalencia (ECP) y Análisis de Valores Límite (BVA).

---

## 📌 Descripción del Proyecto
En esta segunda etapa del proyecto **Urban Routes**, el objetivo principal fue analizar y descomponer los requisitos para la nueva función de **"Compartir un automóvil" (Carsharing)**, enfocándose en la validación del formulario de **Licencia de Conducir** y en los algoritmos de cálculo para el precio y la duración del viaje.

---

## 🎯 Tareas y Metodología Aplicada

### 1. 🧠 Mapa Mental (Mind Mapping) — *Función "Agregar licencia de conducir"*
* **Objetivo:** Representar visualmente la estructura de la interfaz y la lógica funcional del formulario de licencia de conducir usando `draw.io`.
* **Descomposición:**
  * **Interfaz:** Validación de elementos visuales (botones, campos de texto, modales emergentes).
  * **Funcionalidad:** Comportamiento ante entradas válidas e inválidas.
  * **Zonas Grises:** Identificación y documentación de requisitos incompletos o ambiguos.

### 2. 📐 Clases de Equivalencia y Valores Límite (Parte 1)
* **Objetivo:** Diseñar combinaciones de prueba eficientes para los campos de entrada **"Nombre"** y **"Apellido"**.
* **Técnicas:** Partición en Clases de Equivalencia (ECP) y Análisis de Valores Límite (BVA) para escenarios positivos y negativos.

### 3. ⏱️ Pruebas de Cálculo de Precio y Duración (Parte 2)
* **Objetivo:** Validar la lógica matemática del servidor según la distancia, hora de salida y tarifas.
* **Resultados:** Definición de clases de equivalencia para parámetros del algoritmo y diseño de casos de prueba formalizados para el cálculo de viajes (incluyendo límites de distancia = 0).

---

## 📊 Resumen del Sprint 2

| Entregable | Herramienta / Técnica | Estado |
| :--- | :---: | :---: |
| **Mapa Mental (PDF)** | Draw.io / Google Drive | 🟢 Completado |
| **Diseño de ECP / BVA (Campos Nombre y Apellido)** | Google Sheets / Excel | 🟢 Completado |
| **ECP / BVA (Lógica de Precio y Duración)** | Google Sheets / Excel | 🟢 Completado |
| **Diseño de Casos de Prueba** | Google Sheets / Matriz de Pruebas | 🟢 Completado |

---

## 📁 Estructura del Repositorio

```text
├── README.md                           <- Descripción general y resumen del Sprint 2
├── Sprint2_Analisis_y_Casos_de_Prueba.xlsx <- Matriz con ECP, BVA y Casos de Prueba de cálculo
└── /documentos                         <- Mapa Mental en PDF e informes del sprint
