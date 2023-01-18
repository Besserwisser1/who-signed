# [Кто подписал?](https://github.com/comptech-winter-school/who-signed/tree/main)

«Кто подписал?» представляет собой реализацию проекта в рамках зимней школы [CompTech School 2022](https://comptechschool.com/).

### Папки репозитория

- [`docs`](https://github.com/comptech-winter-school/who-signed/tree/main/docs) - папка с документацией проекта;
- [`who-signed`](https://github.com/comptech-winter-school/who-signed/tree/main/who-signed) - папка со скриптами для Telegram-Bot.

## Назначение

«Кто подписал?» это проект для верификации рукописных подписей.

Продукт разрабатывается для решения RnD-задач компаний-спонсоров зимней школы CompTech School, а также для обучения студентов проектной работе.

## Принцип работы

Взаимодейтвие конечного пользователя происходит через Telegram-Bot, который использует нейронную сеть и базу данных для определения человека, которому принадлежит подпись. 

<p align="center">
<img src="/docs/assets/Diagram.png">
</p>

## Целевая аудитория (пользователи продукта)

Пользователями могут быть:

- Cотрудники банков или частных компаний, которым нужно верифицировать подпись;
- Офисные сотрудники, которым требуется автоматизировать документооборот.

Другие области, где возможно применение данной технологии:

- страховое дело;
- электронную коммерцию;
- автоматизацию подписания государственных бумаг;
- контроль физического доступа;
- контроль заключенных;
- учёт рабочего времени.

## Установка и настройка

1. Открыть приложение Telegram;
2. Ввести название Telegram-Bot в строку поиска: @Sign_Verif_bot (либо воспользоваться ссылкой: @Sign_Verif_bot);
3. Нажать кнопку `START`;
4. Ввести имя пользователя и загрузить фото подписи.

[`Руководство пользователя`](/docs/assets/user_guide.md)

### Зависимости

    - albumentations 1.1.0
    - Flask 2.0.2
    - keras 2.8.0
    - Keras-Preprocessing 1.1.2
    - matplotlib 3.5.1
    - notebook 5.3.1
    - numpy 1.22.1
    - pandas 1.4.0
    - pandas-datareader 0.9.0
    - pathlib 1.0.1
    - Pillow 9.0.1
    - pyngrok 5.1.0
    - requests 2.26.0
    - scikit-learn 1.0.2
    - scipy 1.4.1
    - sklearn-pandas 1.8.0
    - torch 1.10.2
    - torchvision 0.11.3

## Использование

Подробно описано в [`Руководстве пользователя`](/docs/assets/user_guide.md).

## Датасет 

https://www.kaggle.com/tienen/handwritten-signature-verification

## Дополнительно

Рекомендуется делать подпись на белой не мятой бумаге, загружать фото подписи в хорошем качестве. 

## Команда

- Исаков Игорь - тимлид, Back-end, ML
- Чанчиков Антон - Back-end
- Патрушев Борис - Back-end, ML
- Хаецкая Дарья - ML
- Скудина Виктория - технический писатель

### Куратор

Захар Пашкин - Data Scientist, ЦФТ

