# Roadmap

## Q3 2018

- `ALTER UPDATE` для массового изменения данных с использованием подхода, аналогичного `ALTER DELETE`
- Добавление Protobuf и Parquet к ассортименту поддерживаемых форматов ввода-вывода
- Улучшением совместимости с Tableau и другими инструментами бизнес-аналитики

## Q4 2018

- Соответствующий SQL стандарту синтаксис JOIN:
    - Несколько `JOIN`ов в одном `SELECT`
    - Указание связи между таблицами через `ON`
    - Возможность сослаться на имя таблицы вместо обязательного использования подзапроса

- Улучшения в исполнении JOIN:
    - Распределённый JOIN, не ограниченный оперативной памятью
    - Перенос зависящих только от одной стороны предикатов сквозь JOIN

- Пулы ресурсов для более точного распределения мощностей кластера между его пользователями
