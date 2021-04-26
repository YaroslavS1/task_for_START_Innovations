# Установка:
* Клонировать репозиторий:
```bash
git clone https://github.com/YaroslavS1/task_for_START_Innovations
```
* Установить виртуальное окружение:
```bash
python -m venv venv
```
Windows
```bash
.\venv\Scripts\activate
```
Linux/Mac OS
```bash
source venv/bin/activate
```
* Установить зависимости из файла **requirements.txt**:
```bash
pip install -r requirements.txt
```
* Команда для создания миграций приложения для базы данных:
```bash
python manage.py makemigrations
python manage.py migrate
```
* Чтобы заполнить БД данными из **emoji_df.csv** нужно запустить скрипт **fill_db.py**

emoji|name|group|sub_group|codepoints
--- | --- | --- | --- | ---
|😀|grinning face|Smileys & Emotion|face-smiling|1F600|
|😃|grinning face with big eyes|Smileys & Emotion|face-smiling|1F603|
|😄|grinning face with smiling eyes|Smileys & Emotion|face-smiling|1F604|
|😁|beaming face with smiling eyes|Smileys & Emotion|face-smiling|1F601|
|😆|grinning squinting face|Smileys & Emotion|face-smiling|1F606|
|😅|grinning face with sweat|Smileys & Emotion|face-smiling|1F605|
|🤣|rolling on the floor laughing|Smileys & Emotion|face-smiling|1F923|
|😂|face with tears of joy|Smileys & Emotion|face-smiling|1F602|
|🙂|slightly smiling face|Smileys & Emotion|face-smiling|1F642|
|...|...|...|...|...|

* Команда для запуска приложения:
```bash
python manage.py runserver
```