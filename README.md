# probing_BERT
# Синтаксический пробинг границ клауз на внутренних слоях BERT
# Syntactic probing of clause boundaries on internal BERT layers
This project explores how BERT encodes syntactic clause boundaries across its internal layers using Russian dependency-parsed data from the SynTagRus corpus. It implements cosine similarity analysis, linear probing with multiclass/binary classifiers, and UMAP visualization to identify layer-specific syntactic patterns. 

## Содержание репозитория 
### 1. Код

    linear0_main_file.ipynb – Анализ векторов слов, стоящих рядом (линейное расстояние = 0).

    linear1.ipynb – Анализ векторов слов, разделенных одним токеном (линейное расстояние = 1).

    linear2.ipynb – Анализ векторов слов, разделенных двумя токенами (линейное расстояние = 2).

    linear3.ipynb – Анализ векторов слов, разделенных тремя токенами (линейное расстояние = 3).

Первый скрипт включает: извлечение эмбеддингов, расчет косинусного сходства, классификацию в виде трех экспериментов и визуализацию. Остальные - только извлечение эмбеддингов и расчет косинусного сходства.
### 2. 3D-визуализации UMAP 
В папке 3d_umap содержатся 3D графики для визуализации пространств эмбеддингов при помощи UMAP в виде файлов HTML. \
Все остальные графики находятся в тетрадках с кодом.
