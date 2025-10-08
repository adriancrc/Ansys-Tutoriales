# 🟠 ANSYS · Fatiga en Eje Escalonado (Static Structural)

🌐 This README is also available in English 🇺🇸: [README.en.md](README.en.md)

[![YouTube Channel](https://img.shields.io/badge/YouTube-Adrián%20Quesada-red?logo=youtube)](https://youtube.com/@adrian-quesada)
[![YouTube Playlist](https://img.shields.io/badge/YouTube-ANSYS%20Playlist-red?logo=youtube&style=flat)](https://www.youtube.com/playlist?list=PLoS7esn6vSq-qijNcN_5N_DmRPoeeX0lL)
![License](https://img.shields.io/badge/License-MIT-blue)  
![LFS](https://img.shields.io/badge/Git-LFS-important) 
![GitHub Release](https://img.shields.io/github/v/release/adriancrc/Ansys-Tutoriales)
![Total Downloads](https://img.shields.io/github/downloads/adriancrc/Ansys-Tutoriales/total)
![Tested with ANSYS](https://img.shields.io/badge/Tested%20with-ANSYS-orange)
![Top language](https://img.shields.io/badge/Top%20Language-ANSYS-blue)
![Made with ANSYS](https://img.shields.io/badge/Made%20with-ANSYS-black)
![Platform](https://img.shields.io/badge/Platform-Windows-blue)
![Use Case](https://img.shields.io/badge/Use-Educational-success)
![Author](https://img.shields.io/badge/Author-Adrián%20Quesada%20Martínez-blueviolet)
![Developed at ITCR](https://img.shields.io/badge/Developed%20at-ITCR-blue)

---

## 👨‍💻 Autor
**Adrián José Quesada Martínez**  
*Instituto Tecnológico de Costa Rica (TEC)*

---

## 📘 Descripción

Repositorio con el modelo y archivos de apoyo para el tutorial de **Fatiga en ANSYS Workbench (Static Structural)** aplicado a un **eje escalonado**.  
Se configura el caso para evaluar **vida a fatiga** usando **curva S–N**, corrección por **esfuerzo medio (Goodman)** y estimación de **daño acumulado (Palmgren–Miner)**, con énfasis en la concentración de esfuerzos en el **filete** del cambio de diámetro.  

Ideal para estudiantes, docentes e ingenieros que deseen reforzar conceptos de **mecánica de materiales**, **diseño a fatiga** y **simulación FEA**.

---

## 📂 Archivos incluidos

- `geometry/` → Geometría CAD del eje escalonado (STEP/SCAD/ScDOC).  
- `workbench/` → Proyecto de **ANSYS Workbench** (`.wbpz`) con el flujo configurado.  
- `results/` → Resultados de la simulación (`.rst`) para postprocesamiento en ANSYS.  
- 🎥 [Video paso a paso en YouTube](https://www.youtube.com/watch?v=e0tzgJJADhs) → Explicación completa del procedimiento.

> **Nota:** Los archivos pesados se gestionan con **Git LFS**.

---

## ✨ Características

- Configuración de análisis **Static Structural** para evaluación de **fatiga**.  
- **Refinamiento de mallado** en el filete (zona crítica de Kt).  
- Definición de **carga alternante** (rotación + flexión/torque según el caso).  
- **Fatigue Tool**: curva **S–N**, **Goodman** (esfuerzo medio) y **Miner** (daño).  
- Postproceso: distribución de **vida**, **daño** y localización de la **zona crítica**.  

---

## 🚀 Cómo instalar / usar

### 🔹 Opción 1: Clonar con Git LFS

```bash
git lfs install
git clone https://github.com/adriancrc/Ansys-Tutoriales.git
```
Abre la carpeta Fatiga (Static Structural).

Importa el archivo .wbpz en ANSYS Workbench.

Verifica material, condiciones de frontera y parámetros de Fatigue Tool.

Resuelve y analiza vida/daño en el filete del eje.

🔹 Opción 2: Descargar desde Releases
Ve a Releases.

Descarga el .zip correspondiente.

Extrae y abre el proyecto en ANSYS Workbench.

⚙️ Requisitos
ANSYS Workbench (recomendado: 2025 R1 o equivalente).

Git LFS instalado para descargar proyectos pesados.

📚 Referencias rápidas
Curva S–N (Wöhler) y correcciones por esfuerzo medio (Goodman).

Regla de daño acumulado (Palmgren–Miner).

Efecto de concentración de esfuerzos (Kt) por geometría del filete.

📬 Soporte
¿Consultas o sugerencias?
📧 adquesada@itcr.ac.cr

📄 Licencia
Código y configuraciones → MIT
Imágenes, miniaturas y material docente → CC BY 4.0

Consulta el archivo LICENSE para más detalles.

⭐ ¡Apoya este proyecto!
Si este material te fue útil:

Deja una ⭐ en GitHub

Suscríbete al canal 👉 YouTube - Adrián Quesada

Mira más tutoriales de ANSYS aquí 👉 YouTube Playlist

Comparte con colegas y estudiantes 🚀

© 2025 Adrián José Quesada Martínez
