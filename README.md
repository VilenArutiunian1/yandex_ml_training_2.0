# Тренировки по машинному обучению 2.0

Репозиторий с домашними заданиями по обработке естественного языка и машинному обучению.

## Содержание

| Тема | Ноутбук | Что рассматривается |
| --- | --- | --- |
| Векторные представления слов | [Word2Vec](hw01_word_vectors/assignment_word2vec.ipynb) | Обучение и визуализация векторных представлений слов с помощью PyTorch. |
| Attention и языковое моделирование | [Attention](hw02_attention_and_language_modeling/hw02_attention.ipynb) | Механизм внимания и работа декодера. |
| Классификация текстов | [Классические методы](hw04_bert_and_co/assignment_classic_text_classification.ipynb) | Мешок слов, TF-IDF, наивный байесовский классификатор и предобученные эмбеддинги. |
| Предобученные языковые модели | [BERT для классификации текстов](hw04_bert_and_co/assignment_bert_for_text_classification.ipynb) | Классификация текстов с использованием предобученной модели из библиотеки Transformers. |

## Как запустить

1. Клонируйте репозиторий:

   ```bash
   git clone https://github.com/VilenArutiunian1/yandex_ml_training_2.0.git
   cd yandex_ml_training_2.0
   ```

2. Откройте нужный ноутбук в Jupyter Notebook, JupyterLab или Google Colab.
3. Установите необходимые библиотеки и последовательно выполните ячейки. Основные используемые библиотеки: PyTorch, NumPy, pandas, scikit-learn, Matplotlib, NLTK и HuggingFace Transformers

Некоторые ячейки загружают данные или предобученные модели из интернета. Для обучения нейросетевых моделей может пригодиться GPU.
