# Лабораторная работа №8
## Адаптивная верстка: Grid

**Студент:** Аббасов Салман Сананович
**Группа:** ИСП-233

---

## Команды Grid

**display: grid;** - включает Grid

**grid-template-columns: repeat(3, 1fr);** - три равные колонки

**grid-template-rows: 80px 1fr 60px;** - три строки

**grid-template-areas:** - создает области
"header header"
"sidebar main"
"footer footer"

**gap: 10px;** - отступы между ячейками

**repeat(auto-fit, minmax(200px, 1fr));** - адаптивные колонки

---

## Сравнение Flexbox и Grid

| Критерий | Flexbox | Grid |
|----------|---------|------|
| Тип | Одномерная | Двумерная |
| Управление | Строка или столбец | Строки и столбцы |
| Назначение | Выравнивание | Построение макетов |
| Для чего | Компоненты | Страницы и сетки |

## Что и когда использовать

| Задача | Что лучше |
|--------|-----------|
| Навигационное меню | Flexbox |
| Карточки товаров | Flexbox |
| Центрирование | Flexbox |
| Макет страницы | Grid |
| Галерея | Grid |
| Дашборд | Grid |

---

## Мои примеры

**Пример 1: Сетка 3x3**
grid-template-columns: repeat(3, 1fr);
gap: 10px;

**Пример 2: Макет страницы**
grid-template-areas:
"header header"
"sidebar main"
"footer footer";

**Пример 3: Адаптивная галерея**
grid-template-columns: repeat(auto-fit, minmax(200px, 1fr));
gap: 15px;

---

## Вывод
Flexbox - для меню и карточек, Grid - для страниц и галерей.
