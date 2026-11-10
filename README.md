# Bootstrap Shop — Контрольная работа №2

Тема: «CSS-фреймворки: разработка интерфейса на Bootstrap или альтернативном CSS-фреймворке».

## Описание

Проект представляет собой учебную версию сайта интернет-магазина, разработанную с использованием Bootstrap.
Это отдельная реализация предметной области КР №1 (каталог, карточки, заявка) через CSS-фреймворк.

## Используемый фреймворк

Bootstrap 5.3.8.

## Способ подключения

Bootstrap подключён через CDN (jsDelivr):

- CSS — `bootstrap.min.css` в `<head>`;
- JS — `bootstrap.bundle.min.js` перед `</body>` (нужен для navbar, dropdown, modal, accordion).

Собственный файл `css/custom.css` подключается после Bootstrap.

## Ссылка на опубликованный проект

GitHub Pages: https://0porn1k.github.io/kr2-bootstrap-shop/ (после публикации)

## Структура проекта

```text
kr2-bootstrap-shop/
├── index.html      — главная: hero, преимущества, популярные товары
├── catalog.html    — каталог: карточки, значки, модальное окно
├── product.html    — товар: описание, характеристики, accordion
├── order.html      — форма заявки
├── css/
│   └── custom.css  — минимальные доработки поверх Bootstrap
├── images/         — изображения товаров
├── README.md
└── .gitignore
```

## Реализованные компоненты

- сетка: `container`, `row`, `col-12`, `col-md-*`, `col-lg-*`, `g-*`;
- `navbar` с `dropdown` и мобильным меню;
- `card`;
- `btn` (`btn-primary`, `btn-outline-primary`, `btn-secondary`, `btn-lg`);
- `badge`;
- `alert`;
- `modal`;
- `form-control`, `form-select`, `input-group`, `form-check`;
- `breadcrumb`;
- `table` + `table-responsive`;
- `accordion`.

## Используемые технологии

- HTML;
- Bootstrap;
- CSS;
- Git;
- GitHub.

## История выполнения

- Практическая работа 9: главная страница на Bootstrap-сетке (шапка, navbar, hero, преимущества, товары, подвал).
- Практическая работа 10: страницы каталога, товара и заявки; компоненты card, badge, alert, modal, формы, accordion.
- Практическая работа 11: финальная проверка КР №2 — карточки на главной переведены на `card`,
  обязательные поля формы помечены `required`, README дополнен.

## Самостоятельные доработки

- выпадающее меню «Дополнительно» в navbar;
- изображения в карточках товаров (`card-img-top`);
- кнопка «Отправить» в модальном окне связана с формой через атрибут `form`.

## Автор

ФИО: Dmitrii Portnov  
Группа: укажите свою группу
