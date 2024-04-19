# Clasificacion-de-Residuos--YOLO

Reciclaje Inteligente con YOLOv5
Este proyecto utiliza el modelo YOLOv5 para detectar y clasificar diferentes tipos de desechos, como metal, vidrio, plástico, cartón y desechos médicos, en tiempo real a través de una cámara web. Además, proporciona una interfaz gráfica de usuario (GUI) para visualizar los resultados de la detección.

Instalación de Dependencias
Instala las dependencias necesarias utilizando pip:

pip install opencv-python

NumPy:
pip install numpy

Pillow:
pip install pillow

imutils:
pip install imutils

Ultralytics:
pip install yolov5

Requisitos del Software
Python 3.x
OpenCV
NumPy
Pillow
imutils
ultralytics
Cómo Ejecutar el Código
Asegúrate de tener una cámara web conectada a tu dispositivo.

Desde la terminal, navega al directorio del proyecto:
cd reciclaje_ai
Ejecuta el archivo main.py:

python main.py
Se abrirá la interfaz gráfica de usuario (GUI) donde podrás ver la detección en tiempo real de los diferentes tipos de desechos.

Para salir de la aplicación, presiona la tecla 'ESC' en tu teclado.

Estructura del Proyecto:

main.py: Contiene el código principal para la interfaz gráfica de usuario y la integración del modelo YOLOv5.

Modelos/best.pt: Archivo del modelo YOLOv5 preentrenado.

setUp/: Directorio que contiene imágenes utilizadas en la interfaz gráfica de usuario.

Créditos:

Este proyecto utiliza la biblioteca YOLOv5 desarrollada por Ultralytics.

modelo preentrenado: best.py

El modelo YOLO (You Only Look Once) que estamos utilizando en este proyecto viene preentrenado, lo que significa que ha sido entrenado previamente en un conjunto de datos grande y diverso antes de ser utilizado para la detección de objetos en tiempo real.

La razón principal para utilizar un modelo preentrenado es que el proceso de entrenamiento de un modelo desde cero requiere una gran cantidad de datos etiquetados y mucho tiempo de cómputo. Los modelos preentrenados nos ofrecen la ventaja de tener pesos y parámetros ya ajustados para tareas específicas, lo que nos permite utilizarlos como punto de partida para nuestra propia tarea de detección de objetos.

En el caso de YOLO, el modelo preentrenado ha sido entrenado en un conjunto de datos que contiene una amplia variedad de clases de objetos, lo que le permite detectar diferentes tipos de objetos con una precisión razonable. Al utilizar un modelo preentrenado, podemos aprovechar el conocimiento y la capacidad de generalización que el modelo ha adquirido durante el entrenamiento en conjunto de datos masivos, lo que puede mejorar significativamente el rendimiento de nuestra aplicación de detección de objetos con un esfuerzo mínimo de entrenamiento adicional.
