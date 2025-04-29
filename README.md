# 📸 Sistema de Recomendación Basado en Visión por Computadora

Este proyecto implementa un sistema de recomendación de imágenes utilizando **redes neuronales convolucionales** preentrenadas, específicamente **EfficientNetB1**, para identificar similitudes visuales entre productos o imágenes.

## 🚀 Descripción del Proyecto

El objetivo es construir un recomendador visual que, dado un conjunto de imágenes, pueda sugerir imágenes similares basándose en características visuales extraídas automáticamente. Este tipo de sistema es ideal para aplicaciones de **e-commerce**, **búsqueda visual** y **optimización de experiencia de usuario**.

## 🎯 Motivación

Con el crecimiento de las plataformas visuales y de venta online, ofrecer recomendaciones visualmente relevantes puede incrementar significativamente la tasa de conversión y mejorar la experiencia de compra. Este proyecto explora cómo aprovechar arquitecturas de deep learning para desarrollar un motor de recomendaciones basado en imágenes.

## 🛠 Tecnologías Utilizadas

- Python
- TensorFlow y Keras
- EfficientNetB1 (preentrenada en ImageNet)
- OpenCV
- Scikit-learn
- Matplotlib
- Pandas
- NumPy

## 📂 Estructura del Proyecto

├── notebooks/ │ └── recomendacion.ipynb # Notebook principal ├── data/ # Instrucciones o ejemplos de datos ├── models/ # (Opcional) Modelos entrenados ├── requirements.txt # Dependencias del proyecto ├── README.md # Documentación principal └── .gitignore # Exclusiones de archivos temporales

bash
Copiar
Editar

## 🖥 Cómo Ejecutar el Proyecto

1. Clona el repositorio:
   ```bash
   git clone https://github.com/tu_usuario/tu_repositorio.git
   cd tu_repositorio
(Opcional) Crea un entorno virtual:

bash
Copiar
Editar
python -m venv venv
source venv/bin/activate  # En Linux/Mac
venv\Scripts\activate     # En Windows
Instala las dependencias:

bash
Copiar
Editar
pip install -r requirements.txt
Abre el Notebook:

bash
Copiar
Editar
jupyter notebook notebooks/recomendacion.ipynb
📈 Resultados
Extracción de características visuales mediante EfficientNetB1.

Cálculo de similitud entre imágenes usando distancia euclidiana en el espacio de embeddings.

Recomendaciones visuales efectivas basadas en contenido.

Ejemplo de resultados:

Imagen de entrada: 👜

Imágenes recomendadas: 👛👜🛍️ (similares en color, forma, textura).

🛤 Mejoras Futuras
Probar arquitecturas más ligeras como MobileNet o EfficientNetV2.

Implementar búsqueda visual en tiempo real.

Expandir el dataset para una mayor diversidad de productos.

Desplegar una API REST o una interfaz web de consulta.

📄 Licencia
Este proyecto está licenciado bajo la Licencia MIT. Consulta el archivo LICENSE para más detalles.

yaml
Copiar
Editar

---

# 📦 requirements.txt

```plaintext
tensorflow>=2.10.0
keras
numpy
pandas
opencv-python
scikit-learn
matplotlib
jupyter
