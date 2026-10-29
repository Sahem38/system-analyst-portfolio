# 04 · Данные

ER-модели, нормализация и описание данных для двух систем.

[← К оглавлению](../README.md)

---

## Интернет-магазин «Накарабине»

Последовательная проработка модели данных заказа от общего описания сущности до нормализованной логической модели.

### Логическая ER-диаграмма в нотации Чена

Исходная модель: сущность «Заказ» со всеми атрибутами, включая составные - товар, доставка, оплата, пользователь.

<img src="er-chen-nakarabine.png" alt="ER-диаграмма в нотации Чена" width="420">

### Та же модель в нотации Crow's Foot

Заказ одной таблицей.

<img src="er-crows-foot-nakarabine.png" alt="ER-диаграмма Crow's Foot" width="420">

### Нормализация: 1НФ → 2НФ → 3НФ

Пошаговое приведение модели к третьей нормальной форме.

<img src="normalization-nakarabine.png" alt="Нормализация до 3НФ" width="640">

Исходник: [nakarabine-data-modeling.drawio](nakarabine-data-modeling.drawio) - вкладки «Нотация Чена», «Нотация Crow's Foot», «Нормализованная модель» (и «Use Case» из [раздела требований](../01-requirements/README.md#use-case-интернет-магазина-накарабине)).

---

## Логическая модель данных Stets Home

Модель данных приложения «умный дом» в нотации Crow's Foot.

![Модель данных Stets Home](data-model-stets-home.png)

Исходник: [stets-home-data-model.drawio](stets-home-data-model.drawio).

## Словарь данных Stets Home

Для каждого элемента данных - описание, структура или тип, длина и допустимые значения.
<img src="previews/data-dictionary-stets-home.png" alt="Словарь данных, первая страница" width="420">

Файл: [data-dictionary-stets-home.pdf](data-dictionary-stets-home.pdf)
