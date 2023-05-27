# Анализ текстов

## Описание проекта

Требуется анализировать комментарии пользователей на английском языке и выделять токсичные, чтобы отправить на модерацию.

## Навыки и инструменты

- **python**
- **pandas**
- **numpy**
- nltk.tokenize.**RegexpTokenizer**
- nltk.stem.**WordNetLemmatizer**
- nltk.corpus.**stopwords**
- sklearn.feature_extraction.text.**TfidfVectorizer**
- sklearn.linear_model.**LogisticRegression**
- sklearn.ensemble.**RandomForestClassifier**
- **lightgbm**
- **fasttext**
- gensim.models.**Word2Vec**
- **gensim.downloader**


## Вывод

Была проведена исследовательская работа по обработке текстов и обучению и выбору модели для определения токсичных комментариев. Проведен сравнитальный анализ различных конвертеров текста на различных этапах предобработки текста в совокупности с разными моделями. Выбран лучший пайплайн, состоящий из конвертера и модели. Исследована более продвинутая модель FastText, выбрана в качестве наиболее эффективной.
