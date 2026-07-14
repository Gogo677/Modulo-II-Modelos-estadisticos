# Entrega Final - Módulo II: Modelos estadísticos

## Descripción del proyecto

Este repositorio contiene la entrega final del Módulo II del diplomado de Técnicas Estadísticas y minería de datos. El trabajo está organizado en tres notebooks de Jupyter, cada uno dedicado a un bloque temático del curso. En todos se combina explicación conceptual, desarrollo matemático (fórmulas en LaTeX), código en Python con cálculos y simulaciones, y visualizaciones, cerrando con una conclusión.

- **`1 Espacio de probabilidad.ipynb`**: define formalmente el espacio de probabilidad, el espacio muestral, los eventos y los axiomas de Kolmogorov; desarrolla la probabilidad condicional y la independencia; presenta los enfoques clásico, frecuentista y geométrico; e incluye ejemplos clásicos (problema del encuentro, ejemplo del volado) y un ejemplo adicional propio (problema del cumpleaños).
- **`2 Variables aleatorias.ipynb`**: cubre siete distribuciones discretas (uniforme discreta, Bernoulli, binomial, geométrica, Poisson, binomial negativa, hipergeométrica) y cuatro distribuciones continuas (uniforme continua, normal, exponencial, gamma), simulación mediante el método de la transformada inversa, la función generadora de momentos (FGM), la función característica (FC), la Ley de los Grandes Números (LGN) y el Teorema Central del Límite (TCL).
- **`3 Estadistica inferencial.ipynb`**: Ya mero (En progreso...)

El archivo `Entrega_Final_Modulo_II.ipynb` es el checklist original de requisitos de la entrega y no forma parte del contenido a evaluar.

## Bibliotecas de Python necesarias

Los notebooks se ejecutan con Python 3.10 o superior y dependen únicamente de las siguientes bibliotecas:

| Biblioteca   | Uso                                                        | Versión usada en el desarrollo |
|--------------|-------------------------------------------------------------|---------------------------------|
| `numpy`      | Simulación, arreglos y cálculos numéricos                   | 2.4.6                           |
| `scipy`      | Distribuciones de probabilidad, optimización (`scipy.stats`, `scipy.optimize`) | 1.18.0     |
| `matplotlib` | Gráficas (histogramas, funciones de densidad, dispersión, etc.) | 3.11.0                      |

Instalación:

```bash
pip install numpy scipy matplotlib
```

También se requiere Jupyter (`jupyter`, `notebook` o `jupyterlab`) o un editor con soporte de notebooks (por ejemplo, Visual Studio Code con la extensión de Jupyter) para abrir y ejecutar los archivos `.ipynb`.

## Cómo ejecutar los notebooks

1. Instalar las dependencias indicadas arriba.
2. Abrir cada notebook (`1 Espacio de probabilidad.ipynb`, `2 Variables aleatorias.ipynb`, `3 Estadistica inferencial.ipynb`) con Jupyter Notebook, JupyterLab o Visual Studio Code.
3. Ejecutar todas las celdas en orden, de principio a fin (Run All).

## Bibliografía

- [Rincón, L. (2014). *Curso elemental de probabilidad y estadística*. Facultad de Ciencias, UNAM.](https://www.cimat.mx/~pabreu/LuisRinconI.pdf) (consultado el 11/Julio/2025)

- [Pishro-Nik, H. (2014). *Introduction to Probability, Statistics, and Random Processes*. ](https://www.probabilitycourse.com/preface.php?authuser=0) (consultado el 13/Julio/2025)