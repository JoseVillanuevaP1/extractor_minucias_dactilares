# 🧠 Extracción de Minucias en Huellas Dactilares

## 👥 Autores

Este proyecto fue desarrollado por:

-   **Jose Villanueva**
-   **Henry Torres**

Para la asignatura de **Sistemas Inteligentes**.

---

## 📌 Resumen

Este proyecto implementa un sistema completo de procesamiento de imágenes de huellas dactilares. Su propósito es detectar características clave llamadas **minucias** (como bifurcaciones o terminaciones) y **singularidades** (como bucles, deltas o remolinos).

> 🔍 El proyecto fue adaptado y modificado a partir de [fingerprint_recognition](https://github.com/cuevas1208/fingerprint_recognition), con cambios en el procesamiento, visualización y parámetros para ajustarse a nuestras necesidades académicas.

---

## ▶️ ¿Cómo ejecutar?

### 1. Instalar dependencias

```bash
pip install -r requirements.txt
```

### 2. Ejecutar el Programa

```bash
python main.py
```

## 🔄 Etapas del procesamiento

El sistema sigue una serie de pasos para preparar, analizar y extraer información de la huella:

-   **Conversión a Escala de Grises**
-   **Normalización de la Imagen**
-   **Segmentación de Región de Interés (ROI)**
-   **Cálculo de Mapa de Direcciones**
-   **Mapa de Frecuencia de Crestas**
-   **Filtrado con Gabor**
-   **Esqueletización**
-   **Detección de Minucias**
-   **Detección de Singularidades** _(Loops, Deltas, Whorls)_

## 📖 Referencias

-   [Fingerprint Recognition Algorithm , Farah Dhib Tatar](https://airccj.org/CSCP/vol7/csit76809.pdf)
-   [Fingerprint Singular Point Detection Algorithm by Poincaré Index, Jin Bo, Tang Hua Ping, Xu Ming Lan](https://pdfs.semanticscholar.org/6e86/1d0b58bdf7e2e2bb0ecbf274cee6974fe13f.pdf)
-   [Fingerprint Recognition: A study on image enhancement and minutiae extraction](https://pdfs.semanticscholar.org/ca0d/a7c552877e30e1c5d87dfcfb8b5972b0acd9.pdf)
-   [Handbook of Fingerprint Recognition, Autorzy Davide Maltoni, Dario Maio, Anil K. Jain, Salil ]()
-   [Biometrics by rtshadow](https://github.com/rtshadow/biometrics)
-   [Fingerprint enhancement by Utkarsh-Deshmukh](https://github.com/Utkarsh-Deshmukh/Fingerprint-Enhancement-Python)
-   [Dataset from FVC2002](http://bias.csr.unibo.it/fvc2002/download.asp)
