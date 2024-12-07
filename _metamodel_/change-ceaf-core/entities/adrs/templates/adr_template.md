
[Architecture Decision Record (ADR)](@document/ceaf.change.overview)

# {{title}}

## Общая информация

* **Статус:** {{status.title}}
* **Дата:** {{date}}
* **Уровень принятия решения:** {{decision_level.title}}
* **Автор документа:** [{{author.name}}]({{author.contact}})
* **Связь с другими принятыми ADR:**
    {{#adr_links}}
    * {{.}}
    {{/adr_links}}
* **Зависит от:**
    {{depends_on}}

## Стейкхолдеры
Список всех стейкхолдеров по задаче и их ожидания:
{{#stakeholders}}
1. {{.}}
{{/stakeholders}}

## Ключевые стейкхолдеры
Список тех стейкхолдеров без которых мотивация реализовывать задачу пропадает:
{{#key_stakeholders}}
1. {{.}}
{{/key_stakeholders}}

## Согласующие

| ФИО                       | Должность/роль        | Контакт               |
|:------------------------- |:----------------------|:----------------------|
{{#desision_makers}}
| {{name}}                  | {{role}}              | {{contact}}           |
{{/desision_makers}}

## Описание проблемы и движущих факторов изменений

### Мотивация
{{motivation}}

### Контекст
{{context}}

### Цели/решаемые проблемы
{{#goals}}
1. {{.}}
{{/goals}}

### Границы изменений
{{#boarders}}
1. {{.}}
{{/boarders}}

### Дорожная карта реализации
Для реализации задачи необходимо выполнить следующие шаги:
{{#roadmap}}
1. {{.}}
{{/roadmap}}

## Планируемые затраты
{{planned_costs}}

## Планируемая выгода
{{planned_benefit}}

## Принятое решение
{{decision_taken}}

## Рассмотренные варианты
{{options_considered}}

## Бизнес-процесса
Если в рамках реализации задачи требуется изменять, удалять или создавать новые бизнес-процессы, то в рамках данного раздела необходимо это описать.

### Процессы, которые изменяются
Изменяемые процессы:
{{#changed_processes}}
1. {{.}}
{{/changed_processes}}

### Процессы, которые прекращаются
Прекращаемые процессы:
{{#terminated_process}}
1. {{.}}
{{/terminated_process}}

### Процессы, которые создаются
Создаваемые процессы:
{{created_process.doc_id}}

![Создаваемые процессы](@entity/ceaf.change.adrs/business_process?doc_id={{created_process.doc_id}})


## Архитектура решения
!!! Я не понял магию.
Должна создаваться автоматически для защиты решения

## Приложение
{{application}}
