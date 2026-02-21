# Fichas Triádicas — Aplicación de Análisis Semiótico Visual

![Semiótica](https://img.shields.io/badge/Semana-10-c0392b?style=for-the-badge)
![Estatus](https://img.shields.io/badge/Estado-Producción-success?style=for-the-badge)

Esta aplicación web interactiva es una herramienta pedagógica diseñada para la asignatura de **Semiótica de la Imagen**. Facilita la aplicación práctica de la **Tríada de Charles Sanders Peirce** (Representamen, Objeto e Interpretante) mediante el análisis de piezas visuales históricas y contemporáneas.



## 🎯 Objetivo de la Actividad

El proyecto permite a los estudiantes:
1.  **Fase de Análisis:** Identificar y describir los componentes de la tríada en 6 piezas visuales seleccionadas.
2.  **Fase de Creación:** Diseñar un signo nuevo basado en objetivos comunicacionales específicos.
3.  **Integración IA:** Generar prompts optimizados para herramientas de generación de imágenes (**Nanobanana**) a partir del análisis semiótico previo.

## ✨ Características Técnicas

* **Interfaz Dual:** Sistema de pestañas para alternar entre el análisis de fichas y el micro-diseño.
* **Diagnóstico Automático:** Evalúa la calidad de los textos ingresados y ofrece retroalimentación inmediata basada en una rúbrica.
* **Generador de Prompts:** Transforma conceptos semióticos complejos en descripciones legibles para modelos de IA.
* **Seguimiento de Progreso:** Dos barras de progreso dinámicas que calculan el porcentaje de completitud en tiempo real.
* **Exportación a Correo:** Genera automáticamente un resumen estructurado y abre el cliente de correo del usuario con los datos listos para el envío académico.
* **Lightbox Nativo:** Visualización ampliada de imágenes para un análisis detallado de los signos.

## 🛠️ Tecnologías

* **HTML5 / CSS3:** Diseño responsivo con uso extensivo de variables CSS (`:root`) para una identidad visual sobria y profesional.
* **JavaScript (Vanilla):** Lógica de validación, cálculos de porcentaje de completitud y manipulación dinámica del DOM.
* **Bootstrap 5:** Estructura de rejilla (Grid) y utilidades de espaciado.
* **Font Awesome 6:** Iconografía intuitiva para guiar al usuario.

## 📂 Estructura del Proyecto

El proyecto está consolidado en un **archivo único autoejecutable**, lo que permite su distribución sencilla sin dependencias externas complejas de servidor:

* **`IMGS` Array:** Contiene los metadatos y descripciones de las piezas visuales.
* **`FDS` Array:** Define las dimensiones de análisis (Representamen, Objeto, Interpretantes).
* **Lógica de Progreso:** Sistema de escucha de eventos `oninput` para actualizar visualmente la validación de cada campo.

## 🚀 Cómo usar este recurso

1.  Clona o descarga el archivo `.html`.
2.  Ábrelo en cualquier navegador moderno.
3.  **Análisis:** Completa los campos de texto para las 6 imágenes (el icono se volverá verde al detectar contenido).
4.  **Diseño:** En la pestaña 2, selecciona un objetivo y describe tu propuesta.
5.  **Envío:** Presiona "Enviar Participación" para copiar los resultados al portapapeles y preparar el correo para el docente.

---
**Nota:** Este proyecto ha sido desarrollado como material de apoyo académico para la Universidad Tecnológica del Perú (UTP).