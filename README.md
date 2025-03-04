# **Modelado del Diodo en Python**

Este repositorio contiene un modelo matemático en Python para analizar el comportamiento de un **diodo de unión PN**, incluyendo:
- **Tensión de barrera**
- **Anchura de la zona de agotamiento**
- **Capacitancia de la unión**
- **Corriente de saturación inversa**
- **Curva característica I-V del diodo**

## **📌 Requisitos Previos**
Antes de ejecutar este código, asegúrate de tener instalado lo siguiente:

### **1️⃣ Instalación de Visual Studio Code (VS Code)**
Descarga e instala **Visual Studio Code** desde:  
[https://code.visualstudio.com/](https://code.visualstudio.com/)

### **2️⃣ Instalación de Python**
Este código está desarrollado en **Python 3.9+**. Puedes instalar Python desde:  
[https://www.python.org/downloads/](https://www.python.org/downloads/)

### **3️⃣ Instalación de Extensiones en VS Code**
Para ejecutar correctamente el código, instala las siguientes extensiones en **VS Code**:
- **Python** (extensión oficial de Microsoft)
- **Jupyter** (para ejecutar archivos `.ipynb` dentro de VS Code)

Para instalarlas, abre **VS Code**, ve a la pestaña **Extensiones (Ctrl+Shift+X)** y busca `Python` y `Jupyter`.

### **4️⃣ Instalación de Librerías Necesarias**
Ejecuta el siguiente comando en la terminal de **VS Code** para instalar las librerías necesarias:

```bash
pip install numpy matplotlib rich
```

- **numpy**: Para cálculos numéricos y algebraicos.
- **rich**: Para mostrar los resultados en formato tabla en la terminal.

## **📂 Archivos en el Repositorio**
- **`modelado_diodo.ipynb`**: Notebook con la implementación completa del modelo del diodo.
- **`imagenes/`**: Carpeta con imágenes utilizadas en el notebook.
- **`modelado_diodo.pdf`**: Versión en PDF del código del notebook.
- **`README.md`**: Este documento con la explicación de instalación y uso.
- **`proyecto_diodo.zip`**: Archivo comprimido con todos los archivos necesarios.

## **📦 Cómo Descomprimir la Carpeta del Proyecto**
Si descargaste el archivo `proyecto_diodo.zip`, sigue estos pasos para descomprimirlo:

### **Windows**
1. Ubica el archivo `proyecto_diodo.zip` en tu computadora.
2. Haz clic derecho y selecciona **Extraer aquí** o **Extraer en 'proyecto_diodo/'**.
3. Abre **VS Code** y selecciona la carpeta descomprimida.

### **Linux y MacOS**
Ejecuta el siguiente comando en la terminal:
```bash
unzip proyecto_diodo.zip -d proyecto_diodo
```
Luego, abre la carpeta en **VS Code**.

## **🚀 Cómo Ejecutar el Código en VS Code**
### **1️⃣ Abrir el Proyecto en VS Code**
1. Abre **VS Code**.
2. Ve a **Archivo > Abrir Carpeta** y selecciona la carpeta descomprimida del proyecto.

### **2️⃣ Ejecutar el Código en un Notebook**
Si deseas usar **Jupyter Notebook** dentro de **VS Code**:
1. Abre el archivo **`modelado_diodo.ipynb`**.
2. Ejecuta cada celda con **Shift + Enter**.


## **📊 Salida Esperada**
El programa imprimirá:
1. **Tensión de barrera \( V_b \)**
2. **Anchura de la zona de agotamiento \( W \)**
3. **Capacitancia de la unión \( C_j \)**
4. **Corriente de saturación inversa \( I_S \)**
