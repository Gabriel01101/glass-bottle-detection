# Detector de Botellas en Tiempo Real

Este script en Python implementa un detector de botellas en tiempo real utilizando OpenCV y el modelo preentrenado MobileNet SSD. Asegúrate de tener los siguientes archivos en el mismo directorio que el script:

- `deploy.prototxt`
- `mobilenet_iter_73000.caffemodel`

Puedes descargar los archivos del modelo MobileNet SSD desde [aquí](https://github.com/chuanqi305/MobileNet-SSD).

Antes de ejecutar el detector, verifica la existencia de estos archivos. El script utiliza la cámara en tiempo real y aplica la detección de objetos en cada fotograma.

## Requisitos

Asegúrate de tener instalados los siguientes paquetes:

- OpenCV
- NumPy

## Ejecución

Para ejecutar el script, utiliza el siguiente comando:

```bash
python detect_bottles.py
