# Proyecto-3 Pruebas de Aplicaciones Web
# Proyecto QA - Pruebas de funcionalidad para Compartir Automóvil

Este proyecto forma parte de una evaluación práctica de aseguramiento de calidad (QA). El objetivo principal es probar y documentar el correcto funcionamiento del proceso de **compartir un automóvil** en una aplicación web, aplicando técnicas de diseño de pruebas como listas de comprobación, partición de clases de equivalencia, valores límite, y reporte de errores en Jira.

---

## 🧪 Objetivo del Proyecto

Realizar pruebas de diseño y funcionalidad sobre el formulario de reserva de automóviles en dos navegadores y resoluciones distintas:

- Google Chrome – Resolución: **800x600**
- Firefox – Resolución: **1920x1080**

Se probaron funcionalidades clave como: **formulario de reserva, botón "Reservar", método de pago, ventanas emergentes y alquiler de automóvil**.

---

## 📁 Estructura del Proyecto

El proyecto se presenta en un archivo Excel con varias pestañas, y los errores detectados están documentados en Jira. La estructura del archivo es:

1. **1. Lista de comprobación del diseño**  
   Validación visual del formulario de reserva en la opción de viaje "Lujo", incluyendo ortografía, disposición de elementos, mapa y ventanas emergentes ("Automóvil reservado", "¿Seguro que quieres cancelar el viaje?", "Viaje cancelado").

2. **2. Lista de comprobación de "Método de pago" y "Agregar tarjeta"**  
   Pruebas funcionales usando partición de clases de equivalencia y valores límite. Incluye escenarios positivos y negativos.

3. **3. Casos de prueba para el botón "Reservar"**  
   Validación del comportamiento del botón según los requisitos funcionales. No se validaron los cálculos de distancia/tiempo ni el temporizador.

4. **4. Casos de prueba para el alquiler de automóviles**  
   Casos positivos y negativos relacionados con la función de alquiler, de acuerdo a los requisitos.

5. **5. Resultados de pruebas e informes de errores**  
   Resultado de cada prueba marcada como APROBADA o NO APROBADA. En caso de fallo, se generó un ticket en Jira y se documentó el enlace correspondiente.

---

## 🧰 Herramientas utilizadas

- **Navegadores:** Google Chrome y Firefox
- **Jira:** Para la creación y seguimiento de errores
- **Excel:** Para la documentación de listas de comprobación y casos de prueba
- **Figma:** Para el análisis de diseño visual
- **Técnicas de prueba:** 
  - Lista de comprobación
  - Partición de clases de equivalencia
  - Análisis de valores límite
  - Casos positivos y negativos

---

## 📋 Entornos de prueba

| Navegador     | Resolución   | Tipo de prueba realizada             |
|---------------|--------------|--------------------------------------|
| Chrome        | 800x600      | Diseño + Funcionalidad               |
| Firefox       | 1920x1080    | Solo pruebas de diseño               |

---

## 🐞 Reporte de errores

Todos los errores detectados durante las pruebas están documentados en Jira. Cada caso NO APROBADO en el Excel contiene un **enlace al ticket** correspondiente en la columna "Enlace al informe de errores".

---

## 💼 Rol desempeñado

- Análisis de requisitos y diseño desde Figma
- Elaboración de listas de comprobación de diseño y funcionalidad
- Creación de casos de prueba con técnicas de testing
- Ejecución de pruebas en distintos entornos
- Reporte de bugs detallados en Jira
- Organización de resultados de prueba por pestaña y categoría

---

## ✅ Estado del proyecto

✔️ Proyecto finalizado con documentación completa, pruebas ejecutadas y errores reportados.

---

## 📎 Archivos incluidos

- `proyecto_compartir_auto.xlsx` — Archivo principal con las listas de comprobación, casos de prueba y enlaces a Jira.
- `capturas/` *(opcional)* — Evidencia visual de errores o comportamientos incorrectos detectados.
