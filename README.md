# Actividad Formativa 3: Implementación y Evaluación de Filtros Digitales

Repositorio correspondiente a la actividad práctica de procesamiento de señales para el diseño, implementación y evaluación de filtros digitales (pasa bajos, pasa altos y pasa bandas) utilizando Python.

---

##Descripción del Proyecto

El objetivo de esta práctica es comprender y aplicar los conceptos fundamentales del procesamiento digital de señales:
* **Diseño de filtros IIR** (tipo Butterworth) para diferentes respuestas en frecuencia.
* **Generación de señales compuestas** combinando múltiples frecuencias senoidales y ruido blanco de alta frecuencia.
* **Aplicación y análisis comparativo** de las señales en el dominio del tiempo antes y después del filtrado.

---

## Tecnologías y Librerías Utilizadas

El script fue desarrollado en **Python** utilizando las siguientes librerías científicas:
* **[NumPy](https://numpy.org/):** Creación de vectores de tiempo, señales senoidales y manipulación de arreglos numéricos.
* **[SciPy](https://scipy.org/):** Módulo `scipy.signal` para el diseño de los coeficientes del filtro (`butter`) y su aplicación directa (`lfilter`).
* **[Matplotlib](https://matplotlib.org/):** Visualización gráfica de las señales originales, ruidosas y filtradas.

---

## ⚙️ Instrucciones de Instalación y Ejecución

### 1. Clonar el repositorio
```bash
git clone [https://github.com/Jazmin777/tu-repositorio.git](https://github.com/Jazmin777/tu-repositorio.git)
cd tu-repositorio
