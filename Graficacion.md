**Impartida por Jesús Eduardo Alcaraz Chavez**

La materia de ***graficación*** tiene como **propósito** el *análisis, la realización y la comprensión de medios visuales generados atraves de computadora.*

---

## Primeros pasos

### Introducción 

Como antecedentes de la _graficación_ deben tener unos contenidos claros antes de

#### Teoría del color

Las imágenes pueden utilizar distintos protocolos de colores para su realización como lo son

* RGBA (Red, Green, Blue, Alpha) donde cada letra supone un canal con valores que van del 0 - 255. Cada canal es representada por una matriz que guarda dichos valores y que luego se combinan.
* Monocromático (Negro a Blanco) donde es un solo canal que va del 0 - 255 donde solo son totanilidades del negro.
* Otros incluyen _CYAK_ y _HEX_

#### Requisitos de software

Para trabajar de la forma mas sencilla con estos temas se va a utilizar el lenguaje **Python** en conjunto con la libreria _Open cv_ para que se encargue de la visualización de archivos y documentos. Acontinuacion se muestran los _comandos para empezar con el entorno virtual_.

```
python -m venv ejemploenv
dir
ejemploenv/Scripts/p
ejemploenv/activate.bat 
```
```

Acontinuación se menciona como _instalar la libreria_ y un programa básico para cargar una imagen con dicha libreria.

```
```
pip install opencv-contrib-python
----------------------------------
import cv2 as cv

img = cv.imread('imagen.png)
cv.imshow('Ejemplo', img)
cv.waitKey()
cv.destroyAllWindows()
```

---

## Practica 1

