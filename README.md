# Detector de Botellas MobileNet-SSD

Este script en Python implementa un detector de botellas en tiempo real utilizando OpenCV y el modelo preentrenado MobileNet SSD. Se necesitan los siguientes archivos en el mismo directorio que el script:

- `deploy.prototxt`
- `mobilenet_iter_73000.caffemodel`

Puedes descargar los archivos del modelo MobileNet SSD desde [aquí](https://github.com/chuanqi305/MobileNet-SSD).

Antes de ejecutar el detector, verifica la existencia de estos archivos. El script utiliza la cámara en tiempo real y aplica la detección de objetos en cada fotograma.

## Requisitos

Asegúrate de tener instalados los siguientes paquetes:

- OpenCV
- NumPy


# Detector de Botellas con YOLOv3

Este script en Python utiliza el modelo preentrenado YOLOv3 para detectar botellas en un entorno de video en tiempo real. Se necesitan  los siguientes archivos en el mismo directorio que el script:

- `yolov3.weights`
- `yolov3.cfg`
- `coco.names`

Puedes descargar los archivos del modelo YOLOv3 desde [aquí](https://pjreddie.com/darknet/yolo/).

## Requisitos

Asegúrate de tener instalados los siguientes paquetes:

- OpenCV
- NumPy





