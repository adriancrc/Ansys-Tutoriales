# 🟠 ANSYS · Stepped Shaft Fatigue (Static Structural)

🌐 También disponible en español 🇪🇸: [README.md](README.md)

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

## 👨‍💻 Author
**Adrián José Quesada Martínez**  
*Instituto Tecnológico de Costa Rica (TEC)*

---

## 📘 Overview

Repository with the model and support files for the **Fatigue analysis in ANSYS Workbench (Static Structural)** applied to a **stepped shaft**.  
The case is configured to evaluate **fatigue life** using the **S–N curve**, **mean stress correction (Goodman)**, and **cumulative damage (Palmgren–Miner)**, with emphasis on stress concentration at the **fillet**.

Ideal for students, instructors, and engineers who want to strengthen **mechanics of materials**, **fatigue design**, and **FEA** skills.

---

## 📂 Included Files

- `geometry/` → CAD model of the stepped shaft (STEP/SCAD/ScDOC).  
- `workbench/` → **ANSYS Workbench** project (`.wbpz`) with the full workflow configured.  
- `results/` → Simulation results (`.rst`) for postprocessing in ANSYS.  
- 🎥 **Step-by-step video on YouTube:** https://www.youtube.com/watch?v=e0tzgJJADhs

> **Note:** Large binaries are managed with **Git LFS**.

---

## ✨ Features

- **Static Structural** setup targeted for **fatigue evaluation**.  
- **Mesh refinement** at the fillet (critical **Kt** zone).  
- Definition of **alternating load** (rotation + bending/torque depending on the case).  
- **Fatigue Tool**: **S–N**, **Goodman** mean stress correction, and **Miner** damage.  
- Postprocessing: **life**, **damage**, and location of the **critical region**.

---

## 🚀 How to Install / Use

### 🔹 Option 1: Clone with Git LFS

```bash
git lfs install
git clone https://github.com/adriancrc/Ansys-Tutoriales.git
```

Open the folder Fatiga (Static Structural).

Import the .wbpz file into ANSYS Workbench.

Check material, boundary conditions, and Fatigue Tool parameters.

Solve and analyze life/damage at the shaft fillet.

### 🔹 Option 2: Download from Releases

1. Go to the [Releases](https://github.com/adriancrc/Ansys-Tutoriales/releases) section.  
2. Download the corresponding `.zip` file.  
3. Extract and open the project in **ANSYS Workbench**.  

---

## ⚙️ Requirements

- **ANSYS Workbench** (recommended version: 2025 R2).  
- **Git LFS** installed in your environment to download large files.  

---

## 📬 Support

Questions or suggestions?  
📧 [adquesada@itcr.ac.cr](mailto:adquesada@itcr.ac.cr)

---

## 📄 License

Code and configurations → **MIT**  

Images, thumbnails, and educational material → **CC BY 4.0**  

See the [`LICENSE`](LICENSE) file for more details.  

---

## ⭐ Support this project!

If this material was useful for you:  
- Leave a ⭐ on GitHub  
- Subscribe to the channel 👉 [YouTube - Adrián Quesada](https://youtube.com/@adrian-quesada)  
- Share with colleagues and students 🚀

[![YouTube Video](https://img.shields.io/badge/YouTube-Tutorial%20Fatiga-red?logo=youtube&style=for-the-badge)](https://www.youtube.com/watch?v=e0tzgJJADhs)

---

© 2025 Adrián José Quesada Martínez
