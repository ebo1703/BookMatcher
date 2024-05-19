# BookRecommendationEngine

## Descripción
`BookRecommendationEngine` es un sistema de recomendación de libros que sugiere libros basados en un libro ingresado por el usuario. Este proyecto utiliza técnicas de filtrado basado en contenido para encontrar similitudes entre libros y proporcionar recomendaciones precisas.

## Tabla de Contenidos
- [Descripción](#descripción)
- [Instalación](#instalación)
- [Uso](#uso)
- [Estructura del Proyecto](#estructura-del-proyecto)
- [Tecnologías Utilizadas](#tecnologías-utilizadas)
- [Contribuciones](#contribuciones)
- [Licencia](#licencia)

## Instalación
Sigue estos pasos para instalar y ejecutar el proyecto localmente:

1. **Clona el repositorio:**
    ```bash
    git clone https://github.com/tu-usuario/BookRecommendationEngine.git
    cd BookRecommendationEngine
    ```

2. **Crea un entorno virtual e instala las dependencias:**
    ```bash
    python -m venv venv
    source venv/bin/activate   # En Windows usa `venv\Scripts\activate`
    pip install -r requirements.txt
    ```

3. **Asegúrate de tener los datos necesarios:**
    - El archivo `books.csv` debe estar en el directorio `data/`. Este archivo debe contener información sobre los libros, incluyendo una columna `title` y una columna `description`.

## Uso
Para ejecutar el sistema de recomendación, sigue estos pasos:

1. **Ejecuta el script principal:**
    ```bash
    python recommend.py
    ```

2. **Ingresa el título de un libro cuando se te solicite:**
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


