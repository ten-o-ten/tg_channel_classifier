# Классификация Telegram-каналов по тематикам
<ul>
Этот репозиторий содержит код для мультиклассовой и мультиlabel классификации Telegram-каналов на основе их текстового контента. В проекте реализованы этапы сбора данных, предобработки текста и обучения модели на основе трансформеров.

<br><b>Функциональность
<li>✅ Сбор данных из Telegram (код для парсинга каналов)
<li>✅ Очистка и предобработка текста (удаление лишних символов, токенизация)
<li>✅ Обучение модели для классификации каналов по тематикам
<li>✅ Реализованы варианты на трансформерах и CatBoost

<br><b>Структура проекта
<br>notebooks/ – Jupyter Notebook'и с кодом для предобработки и обучения
<br>scripts/ – Код для сбора данных и обработки текста

<br><b>Файлы
<li><b>Дообучение трансформера мультиклассификации: </b> <a href="https://github.com/ten-o-ten/tg_channel_classifier/blob/main/notebooks/tg_classifier_transformers.ipynb">tg_classifier_transformers.ipynb</a><br>
<li><b>Дообучение трансформера мульти-лейбл классификации: </b> <a href="https://github.com/ten-o-ten/tg_channel_classifier/blob/main/notebooks/tg_multilable_classifier_transformers.ipynb">tg_multilable_classifier_transformers.ipynb</a><br>
<li><b>Обучение модели с помощью CatBoost: </b> <a href="https://github.com/ten-o-ten/tg_channel_classifier/blob/main/notebooks/tg_classifier_catboost.ipynb">tg_classifier_catboost.ipynb</a><br>
<li><b>Парсер телеграмм каналов: </b> <a href="https://github.com/ten-o-ten/tg_channel_classifier/blob/main/scripts/parser_tg.ipynb">parser_tg.ipynb</a><br>
<li><b>Преобразование меток в мульти-лейбл </b> <a href="https://github.com/ten-o-ten/tg_channel_classifier/blob/main/scripts/make_multilabel_dataset.ipynb">make_multilabel_dataset.ipynb</a><br>
