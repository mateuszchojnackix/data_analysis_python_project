# Opis projektu

Projekt realizowany w parze.
## Cel projektu
Celem projektu jest przewidzenie cen używanych samochodów na podstawie różnych cech, takich jak marka, cena, przebieg, rodzaj paliwa, rok produkcji, itp. Takie umiejętności przewidywania wartości rynkowej używanego samochodu mogą być pomocne zarówno dla kupujących, jak i sprzedających. Wielu ludzi w pewnym momencie życia chce sprzedać lub kupić samochód, a w tym procesie istnieje ryzyko przepłacenia lub sprzedania za zbyt niską cenę. W początkowej fazie projektu skupimy się na analizie danych zawartych w naszym pliku. A na końcu dopasujemy modele i wybierzemy najodpowiedniejszy do oszacowania wartości rynkowej danego samochodu.

## Czyszczenie i przetwarzanie danych
Brakujące wartości będą rozwiązywane poprzez usunięcie odpowiadających im wierszy lub uzupełnienie brakujących wartości za pomocą odpowiednich technik. Będziemy również radzić sobie z ewentualnymi wartościami odstającymi lub anomaliami w danych, aby zapewnić jakość naszego modelu.

## Analiza eksploracyjna danych
Przeprowadzimy analizę eksploracyjną danych, aby zrozumieć zależności między różnymi zmiennymi i uzyskać wgląd w zbiór danych.

## Wizualizacja danych
Stworzymy wizualizacje, takie jak histogramy, wykresy punktowe i wykresy pudełkowe, aby zobaczyć rozkład zmiennych i zidentyfikować wzorce lub korelacje.

## Budowanie i ocena modeli
Podzielimy zbiór danych na zestawy treningowe i testowe, a następnie zbudujemy i ocenimy różne modele regresji przy użyciu różnych algorytmów, takich jak Maszyna Wektorów Wspierających (SVM), K Najbliższych Sąsiadów (KNN), Regresja Liniowa, Drzewo Decyzyjne, Las Losowy i Gradient Boosting.
Będziemy oceniać modele na podstawie metryk takich jak R-kwadrat i Root Mean Squared Error (RMSE) w celu zmierzenia ich wydajności.

## Wybór modelu
Na podstawie wyników oceny wybierzemy najlepiej działający model do przewidywania cen używanych samochodów.

## Wnioski
W ramach tego projektu staramy się przewidzieć ceny używanych samochodów na podstawie różnych cech. Analizując dostępny zbiór danych, czyszcząc i przetwarzając dane, przeprowadzając analizę eksploracyjną danych oraz budując i oceniając modele regresji, możemy oszacować wartość rynkową używanych samochodów.
Ten projekt może być korzystny zarówno dla kupujących, jak i sprzedających używane samochody, ponieważ pomaga podejmować świadome decyzje i unikać przepłacania lub sprzedawania pojazdów po zbyt niskiej cenie.


---

# Project description

## Project Objective
The objective of the project is to predict the prices of used cars using various features such as brand, price, mileage, fuel type, year, etc.
Such predictive capability of used car market value can be helpful for both buyers and sellers. Many people at some point in their life want to buy or sell their car, and in this process, there is a risk of paying too much or selling for too little.
In the initial stage of this project, we will focus on analyzing the data contained in our file. And in the end, we will fit models and select the most appropriate one to estimate the market value for a given car.
The data was obtained from the website Kaggle: https://www.kaggle.com/datasets/christovitohidajat/car-data
It contains information about used cars, including the following variables:

- Brand: The brand of the vehicle, such as BMW, AUDI, etc.
- Price: The price of the vehicle
- Body: The type of the car, such as sedan, van, etc.
- Mileage: The mileage of the car
- EngineV: The engine volume
- Engine Type: The type of engine
- Registration: Whether the car is registered (yes/no)
- Year: The production year
- Model: The model of the car
- The dataset consists of 4345 rows of data regarding the above variables.

## Data Cleaning and Preprocessing
The missing values will be handled by either removing the corresponding rows or imputing the missing values using appropriate techniques.
We will also handle any outliers or anomalies present in the data to ensure the quality of our model.

## Exploratory Data Analysis
We will perform exploratory data analysis to understand the relationships between different variables and gain insights into the dataset.

## Data Visualization
We will create visualizations, such as histograms, scatter plots, and box plots, to visualize the distribution of variables and identify any patterns or correlations.

## Feature Engineering
We will create new features, if necessary, by transforming or combining existing features to improve the performance of our models.

## Model Building and Evaluation
We will split the dataset into training and testing sets, and then build and evaluate various regression models using different algorithms, such as Support Vector Machine (SVM), K-Nearest Neighbors (KNN), Linear Regression, Decision Tree, Random Forest, and Gradient Boosting.

We will evaluate the models based on metrics such as R-squared and Root Mean Squared Error (RMSE) to measure their performance.

## Model Selection
Based on the evaluation results, we will select the best-performing model for predicting the prices of used cars.

## Model Deployment
Once the best model is selected, we will deploy it to make predictions on new, unseen data.

## Summary and Conclusion
In this project, we aim to predict the prices of used cars based on various features. By analyzing the provided dataset, cleaning and preprocessing the data, performing exploratory data analysis, and building and evaluating regression models, we can estimate the market value of used cars.

This project can be beneficial for both buyers and sellers of used cars, as it helps in making informed decisions and avoiding overpaying or underselling vehicles.
