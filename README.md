# Análisis de Esfuerzo Normal por Flexión Biaxial

Este repositorio contiene una herramienta en Python diseñada para calcular los esfuerzos normales resultantes de la combinación de carga axial y momentos flectores en dos ejes ($M_x, M_y$).

##  Características
El algoritmo permite analizar tres geometrías comunes en ingeniería estructural:
1. **Sección Rectangular:** Ideal para vigas y columnas sólidas.
2. **Sección Circular Hueca:** Para análisis de tuberías o postes.
3. **Sección Tipo I:** Vigas estructurales estandarizadas.

##  Requisitos
* Python 3.x
* Biblioteca `math` (incluida por defecto en Python).

##  Funcionamiento del Algoritmo
El programa utiliza la fórmula general de flexión biaxial:

$$\sigma = -\frac{P}{A} - \frac{M_x y}{I_x} - \frac{M_y x}{I_y}$$

Donde:
- **P:** Carga axial.
- **A:** Área de la sección transversal.
- **Mx / My:** Momentos flectores en los ejes X e Y.
- **Ix / Iy:** Momentos de inercia.
- **x / y:** Distancias desde el eje neutro a los puntos críticos.

##  Instalación y Uso
1. Clona este repositorio:
   ```bash
   git clone https://github.com
   ```
2. Ejecuta el archivo `.py`:
   ```bash
   python U3_ACT_02.py
   ```

##  Colaboradores
* **Nombre del Integrante 1** - [@HugoGC-In](https://github.com)
* **Nombre del Integrante 2** - [@Diego-perezdl](https://github.com)
* **Nombre del Integrante 3** - [@luisrobertoramirezramirez0-png](https://github.com)
* **Nombre del Integrante 4** - [@ferchojd433-jph](https://github.com)
* **Nombre del Integrante 5** - [@LuisJimenez007](https://github.com)
* **Nombre del Integrante 6** - [@DACG-tech](https://github.com)
* **Nombre del Integrante 7** - [@fernandojimenez8084-ux](https://github.com)

##  Licencia
Este proyecto es de acceso libre y educativo.
