## Бинарная классификация для предиктивного обслуживания оборудования

**Дополнительная профессиональная программа:** «Data Science. Искусственный интеллект» (КНИТУ-КАИ)

**Тема ВКР:** Разработка модели машинного обучения для прогнозирования отказов оборудования (Machine failure).

---

### О проекте

Цель — создать бинарную классификационную модель, которая определяет, произойдет ли сбой оборудования (1) или нет (0). Результат интегрирован в удобное Streamlit-приложение.

### Описание данных

Используется датасет [AI4I 2020 Predictive Maintenance Dataset](https://archive.ics.uci.edu/dataset/601/predictive+maintenance+dataset) (10 000 записей, 14 признаков), включающий параметры температуры, скорости, износа и т.п.

### Установка и запуск

1. Клонировать репозиторий:

   ```bash
   git clone https://github.com/norutplz/predictive_maintenance_project.git
   ```
2. Перейти в папку проекта:

   ```bash
   cd predictive_maintenance_project
   ```
3. Установить зависимости:

   ```bash
   pip install -r requirements.txt
   ```
4. Запустить приложение:

   ```bash
   streamlit run app.py
   ```

### Структура репозитория

```
predictive_maintenance_project/
├── app.py               # Главный файл Streamlit-приложения
├── analysis_and_model.py # Страница анализа данных и обучения модели
├── presentation.py      # Раздел с презентацией результатов
├── requirements.txt     # Список пакетов Python
├── predictive_maintenance # Исходные CSV-файлы с данными
├── video.mov            # Видео-демонстрация проекта
└── README.md            # Описание проекта 
```

### Видео-демонстрация

[Посмотреть демо на GitHub](https://github.com/norutplz/predictive_maintenance_project.git/video.mp4)

