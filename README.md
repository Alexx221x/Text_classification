# Text_classification
Пример бинарной классификации текста по датасету соревнования [jigsaw-toxic-comment-classification-challenge](https://www.kaggle.com/competitions/jigsaw-toxic-comment-classification-challenge/) для всех желающих.


## Содержание

1. Работа с библиотеками
2.  Работа с датасетом
  * Загрузка датасета
  * Вводный анализ
      * Анализ признаков
      * Распределение в таргете
      * Уникальные символы
  * Предобработка данных
      * Выборки
      * Очистка
      * Лемматизация
      * Облако слов
  * Получение признаков
      * TF-IDF
      * BERT
  * Борьба с дисбалансом в таргете
3.  Обучение моделей
  * Дамми-модель
  * на признаках TF-IDF
  * на эмбеддингах BERT
  * CatBoost и текстовые признаки
4.  Тестирование
