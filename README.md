# streamlit-app

## О чём?
В этом проекте реализовано приложение Streamlit для работы с нейросетью.
Необходимо срочно узнать возможные ответы на вопросы по английскому тексту из ЕГЭ?
Введите весь текст и вопрос в соответствующие окошки, чтобы получить ответ, 
который сгенерирует нейросеть.

## Применение

Чтобы начать работу с приложением, сначала необходимо установить требуемые зависимости:
```
pip install -r requirements.txt
```
Единственный шаг отделяет от начала работы, требуется ввести следующую команду для её запуска:
```
streamlit run src/main.py
```

## Используемые материалы

Streamlit: https://streamlit.io/

Модель: https://huggingface.co/deepset/roberta-base-squad2