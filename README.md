# BookMathcer

## Descripción
`BookMathcer` es un sistema de recomendación de libros que sugiere 3 libros basados en un libro ingresado por el usuario.

## Tabla de Contenidos
- [Descripción](#descripción)
- [Instalación](#instalación)
- [Uso](#uso)
- [Estructura del Proyecto](#estructura-del-proyecto)
- [Tecnologías Utilizadas](#tecnologías-utilizadas)
- [Futuras mejoras](#futuras-mejoras)

## Instalación
Sigue estos pasos para instalar y ejecutar el proyecto localmente:

1. **Clona el repositorio:**
    ```bash
    git clone https://github.com/ebo1703/BookMathcer.git
    cd BookMathcer
    ```

2. **Crea un entorno virtual e instala las dependencias:**
    ```bash
    python -m venv venv
    source venv/bin/activate   
    pip install -r /src/requirements.txt
    ```

3. **Asegúrate de tener los datos necesarios:**
    - Los datos se descargaron del dataset: [text](https://www.kaggle.com/datasets/mohamedbakhet/amazon-books-reviews/data) de Kaggle,
    dado el peso de estos archivos no se suben al repositorio.
    Si se descargan los archivos y se ubican en la carpeta '/Data' se pueden correr sin ningún problema los códigos

## Uso
Para ejecutar el sistema de recomendación, sigue estos pasos:

1. **Ejecuta el script principal:**
    ```bash
    python model.py
    ```

2. **Ingresa el título de un libro cuando se te solicite:**
    Tener en cuenta que
    ```text
    Ingrese el título de un libro: The Hobbit
    ```

3. **Recibe las recomendaciones:**
    ```text
    Recomendaciones para "The Hobbit":
    1. The Lord of the Rings
    2. Harry Potter and the Sorcerer's Stone
    3. The Chronicles of Narnia
    ```

## Estructura del Proyecto
La estructura del proyecto es la siguiente:


BookMatcher/
├── Code/
│ └── Notebooks/
│   └── EDA.ipynb
│ └──src/
│   └── model.py
│   └── recommend.py
│ └──requirements.txt
├── Data/
├── Docs/
│ └── Bitacora.pdf
├── README.md 



## Tecnologías Utilizadas
- **Python 3.8+**
- **Pandas**
- **Scikit-learn**

## Futuras mejoras

