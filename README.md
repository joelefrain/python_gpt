# Curso: Python y ChatGPT aplicados al procesamiento de instrumentación geotécnica

**Instructor:** Joel Alarcón  
**Duración:** 12 horas  
**Horario:** Jueves y viernes de 19:30 – 21:30  
**Lugar:** Aula virtual  
**Correo:** [joel.alarcon.o@uni.pe](mailto:joel.alarcon.o@uni.pe)  
**Página del curso:** [GitHub - Python y ChatGPT para Geotecnia](http://github.com/joelefrain/python_gpt)

---

## Descripción del curso

Este curso está diseñado para enseñar a profesionales de la ingeniería geotécnica cómo aplicar Python y ChatGPT al procesamiento y automatización de tareas relacionadas con la instrumentación geotécnica. A lo largo de las 12 horas de formación, los participantes aprenderán a automatizar procesos como la limpieza de datos, conversión de unidades, análisis de series temporales y la generación de reportes, utilizando ChatGPT como asistente técnico para generar y depurar código.

## Objetivos generales

- **Comprender** la aplicación de Python en el análisis de datos geotécnicos.
- **Usar** ChatGPT como asistente de codificación para generar y depurar scripts.
- **Automatizar** tareas repetitivas en el monitoreo de instrumentación geotécnica.
- **Generar** reportes gráficos y exportables a partir de datos reales.

## Plan de sesiones (12 horas)

### **Sesión 1: Introducción a Python y ChatGPT**

- **Objetivo:** Familiarizarse con los entornos de trabajo y los principios del uso de ChatGPT como copiloto técnico.
- **Descripción:** Instalación de Python, JupyterLab y bibliotecas básicas (pandas, matplotlib). Ejemplos prácticos sobre cómo interactuar con ChatGPT para solicitar ayuda en la creación de scripts y depuración de código.
- **Librerías:** `pandas`, `matplotlib`, `openai`, `os`, `sys`
- **Recursos:** Manual de instalación, guía de prompts, ejemplos de buenas prácticas.
- **Ejercicio:** Crear un script que lea un archivo CSV y grafique una serie temporal.

---

### **Sesión 2: Limpieza y estandarización de datos reales**

- **Objetivo:** Identificar y corregir inconsistencias en datos provenientes de sensores.
- **Descripción:** Tratamiento de valores nulos, formatos de fecha, detección de outliers, unidades inconsistentes (ej. mm a m, °C a K). Ejemplo con sensores PCV y PTA.
- **Librerías:** `pandas`, `numpy`, `datetime`
- **Recursos:** Dataset real anonimizado, scripts de ejemplo.
- **Ejercicio:** Limpieza de un dataset de PCV y graficado posterior con valores corregidos.

---

### **Sesión 3: Conversión de formatos y unificación**

- **Objetivo:** Automatizar la conversión de unidades y el formateo de fechas.
- **Descripción:** Conversión de profundidad (mm a m), fechas (diferentes formatos a ISO 8601), presión (kPa a MPa). Generación de funciones universales.
- **Librerías:** `pandas`, `datetime`, funciones personalizadas.
- **Recursos:** Plantilla de funciones, guía de unidades.
- **Ejercicio:** Convertir y guardar los datos en un nuevo archivo limpio.

---

### **Sesión 4: Gráficos de series temporales**

- **Objetivo:** Visualizar los datos procesados para distintos tipos de instrumentos.
- **Descripción:** Creación de gráficos con `matplotlib` y `seaborn` para series como SACV, CPCV y PCT. Personalización de ejes, títulos, líneas límite y exportación en PNG/PDF.
- **Librerías:** `matplotlib`, `seaborn`, `os`
- **Recursos:** Plantillas de graficado y ejemplos reales.
- **Ejercicio:** Graficar series de tres sensores con límites normativos superpuestos.

---

### **Sesión 5: Automatización de reportes y carpetas**

- **Objetivo:** Generar reportes automáticos y estructurar carpetas para almacenamiento.
- **Descripción:** Creación de funciones que generen carpetas por fecha/poza, exporten gráficos e inserten títulos. Interacción con ChatGPT para la generación automática de scripts repetitivos.
- **Librerías:** `os`, `shutil`, `matplotlib`, `pandas`
- **Recursos:** Scripts base, árbol de directorios, modelo de nomenclatura.
- **Ejercicio:** Crear un lote de reportes de diferentes instrumentos en carpetas ordenadas.

---

### **Sesión 6: Proyecto final asistido con ChatGPT**

- **Objetivo:** Integrar los conocimientos adquiridos en una solución completa.
- **Descripción:** Elección de un caso práctico (PTA, SACV o CPCV), con limpieza, conversión, graficado y exportación automatizada. Uso intensivo de ChatGPT para escribir funciones personalizadas, validar resultados y documentar código.
- **Librerías:** Todas las anteriores.
- **Recursos:** Dataset completo, guía paso a paso, conexión a ChatGPT.
- **Ejercicio:** Entrega de script funcional con documentación y outputs gráficos en una estructura de carpetas predefinida.

---

## Requisitos previos

- Conocimientos básicos de Python.
- Acceso a JupyterLab o un entorno similar para ejecutar scripts de Python.
- Ganas de aprender y automatizar procesos en geotecnia.

## Materiales adicionales

- [Manual de instalación y configuración de Python y JupyterLab](http://example.com/python-setup)
- [Guía de uso de ChatGPT en proyectos de geotecnia](http://example.com/chatgpt-geotecnia)

---

¡Esperamos verte en el curso y ayudarte a automatizar tu flujo de trabajo con Python y ChatGPT!
