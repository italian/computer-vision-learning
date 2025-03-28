# Путь в компьютерное зрение

Этот репозиторий документирует мое обучение компьютерному зрению (CV), эксперименты и проекты по мере изучения фундаментальных и продвинутых концепций CV с особым фокусом на системы автопилотирования и генеративные модели. Проект структурирован по темам и представляет собой пошаговое погружение в область - от базовых операций с изображениями до сложных моделей глубокого обучения.

## Цели проекта

- Освоить фундаментальные концепции и инструменты компьютерного зрения
- Научиться применять алгоритмы CV для решения практических задач
- Создать портфолио проектов в области систем автопилотирования и генеративных моделей
- Документировать учебный процесс для будущего референса и обмена знаниями

## Структура репозитория

```
computer-vision-learning/
├── README.md                   # Главное описание проекта
├── LICENSE                     # Файл лицензии MIT
├── requirements.txt            # Зависимости проекта
├── .gitignore                  # Настройки игнорирования файлов
│
├── notebooks/                  # Jupyter ноутбуки для экспериментов
│   └── README.md               # Описание содержимого директории
│
├── data/                       # Директория для данных
│   ├── README.md               # Описание организации данных
│   ├── raw/                    # Исходные данные
│   └── processed/              # Обработанные данные
│
├── basics/                     # Основы компьютерного зрения
│   ├── README.md               # Описание раздела
│   ├── image_basics.py         # Базовые операции с изображениями
│   ├── filtering.py            # Фильтры и преобразования
│   └── feature_extraction.py   # Выделение признаков
│
├── object-detection/           # Обнаружение объектов
│   └── README.md               # Описание раздела (будет заполнено позже)
│
├── lane-detection/             # Обнаружение дорожной разметки
│   └── README.md               # Описание раздела (будет заполнено позже)
│
├── advanced-cv/                # Продвинутые техники
│   └── README.md               # Описание раздела (будет заполнено позже)
│
├── generative-models/          # Генеративные модели
│   └── README.md               # Описание раздела (будет заполнено позже)
│
└── utils/                      # Вспомогательные функции и классы
    ├── __init__.py             # Инициализация пакета
    ├── visualization.py        # Функции для визуализации результатов
    └── image_processing.py     # Общие функции обработки изображений
```

## План обучения

1. **Этап 1**: Фундаментальные основы (2-3 месяца, 5 часов в неделю)
   - Освоение базовых концепций и инструментов компьютерного зрения
   - Работа с OpenCV и основными библиотеками для анализа данных
   - Проекты по базовой обработке изображений и видео

2. **Этап 2**: Продвинутое компьютерное зрение (3-4 месяца, 10-20 часов в неделю)
   - Изучение нейронных сетей для задач CV
   - Работа с современными архитектурами и предобученными моделями
   - Проекты по детекции объектов и семантической сегментации

3. **Этап 3**: Специализация (4-6 месяцев, 10-20 часов в неделю)
   - Фокус на выбранном направлении (автопилоты или генеративные модели)
   - Разработка комплексных проектов
   - Интеграция с реальными системами или приложениями

## Используемые технологии

- Python 3.11
- OpenCV
- NumPy, Pandas, Matplotlib
- TensorFlow/Keras
- PyTorch (по мере необходимости)
- Другие специализированные библиотеки

## Ресурсы и ссылки

[Будут добавлены по мере изучения материалов]

## Лицензия

Этот проект распространяется под лицензией MIT. См. файл [LICENSE](LICENSE) для получения дополнительной информации.