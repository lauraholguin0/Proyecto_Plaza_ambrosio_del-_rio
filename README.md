# 🌿🖥️ Identificación Botánica con Redes Neuronales en la Plaza Ambrosio del Río  

![Python](https://img.shields.io/badge/Python-3.8%2B-blue?logo=python)
![TensorFlow](https://img.shields.io/badge/TensorFlow-2.0%2B-orange?logo=tensorflow)
![License](https://img.shields.io/badge/License-MIT-green)
![Contributions](https://img.shields.io/badge/Contributions-Welcome-brightgreen)

**Sistema de clasificación de flora urbana usando CNN** | Proyecto desarrollado por: *Laura Holguín, Santiago Alea, Camilo Avendaño y Benjamín Muñoz*  

---

## 📌 Descripción  
Este repositorio contiene el código y dataset de un modelo de **red neuronal convolucional (CNN)** entrenado para identificar **17 especies vegetales** de la Plaza Ambrosio del Río (Chile). El sistema clasifica árboles, arbustos y flores a partir de imágenes capturadas con dispositivos móviles.  

✨ **Características clave:**  
- Modelo basado en **MobileNetV2** (transfer learning).  
- Precisión validada: **87%**.  
- Dataset con **578 imágenes** (propias + aumentadas).  
- Optimizado para condiciones reales (luz, ángulo, estacionalidad).  

---

## 📂 Estructura del Repositorio  
├── /data/ # Dataset de imágenes (train/val/test)
├── /models/ # Modelos entrenados (.keras, .h5)
├── /notebooks/ # Jupyter Notebooks de entrenamiento
├── /src/ # Código fuente (preprocesamiento, predicción)
├── README.md # Este archivo
└── requirements.txt # Dependencias

---

## 🛠️ Instalación y Uso  

### 🔧 Requisitos  
```bash
Python 3.8+  
TensorFlow 2.x  
OpenCV  
Pandas  
Matplotlib  
