# Tecnologías de información emergentes: NLP

## Actividad Integradora 3

#### _Analizador de sentimientos (expandido)_
---
#### Link Google Colab:

https://colab.research.google.com/drive/1wFcLabTZSO1K69MGnDSap3GkVhav4qUd?usp=sharing

---

#### Link modelos entrenados e historial (history) de entrenamiento:

https://drive.google.com/drive/folders/1tS6K4SRJK2tNihnJuBTy0LzWNuWZ58b0?usp=sharing

---

## Funcionalidades

* Analisis de sentimientos (Positivo/Negativo) sobre
    * Reseñas de la página imdb
    * Audio transcrito a texto
    * Tweets por usuarios
    * Reddit posts por usuarios
* Tres modelos diferentes usando RNN para el Analisis de sentimientos (con metricas)

* Extras
    * Recolección y clasificación de comentarios de youtube
    * Modelos de Analisis de sentimientos usando RNN con atencion (BERT) para mensajes spam        
    * Modelo de Analisis de sentimientos de tres sentimientos (neutral, positivo y negativo)
    * Recolector y etiquetador de reviews de la playstore
---

## Ejecución

Antes que nada es necesario descargar los archivos de los modelos ya entrenados los cuales se pueden encontrar en el siguiente Drive: https://drive.google.com/drive/folders/1tS6K4SRJK2tNihnJuBTy0LzWNuWZ58b0?usp=sharing

Estos archivos han de colocarse en el mismo directorio en el que este su archivo .ipynb

Además, se han de decargar y extraer las tablas de las bases de datos utilizadas y cuyos links puede encontrar más abajo en este documento.

Cada modelo generado recibe como entrada una oración como cadena de texto (string) u oraciones como en una lista de cadenas de texto (string).

---

## Bases de datos usadas

Reseñas de peliculas clasificadas como positivas o negativas: <br>
https://www.kaggle.com/ymanojkumar023/kumarmanoj-bag-of-words-meets-bags-of-popcorn?select=labeledTrainData.tsv

Mensajes spam: <br>
https://www.kaggle.com/dejavu23/sms-spam-or-ham-beginner/data

Reviews de playstore: <br>
Estas fueron recolectadas mediante la API "google-play-scraper". Se recolectaron reviews de 15 apps de la categoría "Productividad", es decir, aquellas que apoyan la eficiencia de la agenda de una persona en distintos aspectos. En este caso, se recolectaron 16k reviews. Asimismo, las 5 categorías (estrellas) fueron englobadas en 3 categorías o sentimientos: negativo, positivo, y negativo. Para lo cual, aquellas con 1 o 2 estrellas se les atribuyó una connotación negativa. Para las de 3, una neutra. Por último, las de 4 y 5 una positiva. Cabe remarcar que, las clases no presentaban desbalance significativo. No obstante, se realizó "undersampling" para tener un balance ideal.

---

## Autores 📝

_Equipo #3:_

* **Carlos Adrián Guerra Vázquez**
* **Omar Osvaldo Hernández Díaz**
* **Jesús Carlos Martínez González**
* **Luis Miguel Maawad Hinojosa**
* **Juan Edgar Juarez Mendoza**
