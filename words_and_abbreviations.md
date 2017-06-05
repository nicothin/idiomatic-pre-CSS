# Слова и сокращения в CSS-классах

Слово           | Сокращение | Пример(ы) применения      | Пояснение
----------------| -----------| --------------------------| ---------
`button`        | `btn`      | `.btn`, `.promo__btns`    | Кнопка/Кнопки. Сама по себе кнопка — всегда [БЭМ-блок](http://nicothin.github.io/idiomatic-pre-CSS/#bem-block). Может иметь миксование с БЭМ-элементами. Слово может использоваться в классах-обёртках (см. пример).
`description`   | `descr`    | `.product__descr`         | Описание какой-либо сущности
`image`         | `img`      | `.promo__img`             | Изображение.
`icon`          | -          | `.icon`                   | Иконка.
`link`          | -          | `.product__more-link`     | Ссылка.
`list`          | -          | `.features__list`         | Список.
`picture`       | `pict`, `pic` | `.promo__pict`         | Изображение.
`inner`         | -          | `.promo__inner`           | Внутренняя обёртка чего-либо (чаще всего — для ограничения ширины и выравнивания по центру).
`navigation`    | `nav`      | `.main-nav`               | Навигация — главная (см. пример) или дополнительная.
`title`         | -          | `.promo__title`           | Название какого-либо БЭМ-блока. Обычно, это тег заголовка 1-го или 2-го уровня.
`toggle`        | -          | `.main-nav__toggle`       | Переключение, тумблер. Часто — «гамбургер», переключающий показ/сокрытие главного меню (на медиа-условии, при котором меню скрывается под «гамбургером»).
`wrapper`       | `wrap`     | `.contacts__wrapper`      | Обёртка чего-либо.
`thumbnail`     | `thumb`    | `.photo__thumb`           | Миниатюра (обычно, в какой-либо галерее).
`avatar`        | -          | `.user__avatar`           | Аватарка, маленькая картинка пользователя.
`title`, `heading`, `caption` | - | `.title`             | Заголовок.
`subtitle`      | -          | `.subtitle`               | Подзаголовок.
`description`   | `descr`    | `.product__descr`         | Описание чего-либо.
`slogan`        | -          | `.logo__slogan`           | Слоган.
`text`          | -          | `.about__text`            | Текстовой фрагмент (обычно, выводимый из CMS).
`logo`          | -          | `.logo`, `.partner__logo` | Логотип.
`subtitle`      | -          | `.subtitle`               | Подзаголовок.
`grid`          | -          | `.grid`                   | Сетка (для раскладки блоков по модульной сетке).
`row`           | -          | `.grid__row`              | Общая обертка для ячеек модульной сетки.
`column`        | `col`      | `.grid__col-md-6`         | Ячейка модульной сетки.
`advertisement` | `adv`      | `.aside__adv`             | Рекламный фрагмент.
`promo`         | -          | `.promo`                  | Внутренняя реклама, какое-то введение.
`author`        | -          | `.post__author`           | Автор.
`modal`         | -          | `.modal`                  | Модальное окно.
`popup`         | -          | `.popup`                  | Всплывающий блок (обычно, по клику на чем-либо).
`tooltip`       | -          | `.tooltip`                | Всплывающая подсказка, небольшой блок (обычно, по наведению на что-либо).
`user`          | -          | `.user`                   | Пользователь.
`more`          | -          | `.product__more-link`     | «Далее», «Подробнее».
`features`      | -          | `.features`               | Особенности, преимущества.
`container`     | -          | `.container`              | Контейнер, обёртка.
`pagination`    | -          | `.pagination`             | Навигация по нескольким страницам (1 2 3 ...).
`breadcrumbs`   | -          | `.breadcrumbs`            | «Хлебные крошки» (Главная > Каталог > Товар).
`widget`        | -          | `.aside__widget`          | Виджет.
`dropdown`      | `drop`     | `.filter__drop`           | Выпадающий элемент (направление выпадения не имеет значения).
`copyright`     | -          | `.copyright`              | Копирайт.
`sidebar`, `aside` | -       | `.sidebar`, `.aside`      | Дополнительная информация.
`active`, `current` | -      | `.main-nav__item--active` | Активный элемент (пункт навигации, активный таб).
`hidden`        | -          | `.products--hidden`       | Скрытое.
`shown`         | -          | `.products--shown`        | Показанное.
`error`         | -          | `.field-text--error`      | Состояние ошибки.
`success`       | -          | `.field-text--success`    | Состояние успеха.
`warning`       | -          | `.btn--warning`           | Предупреждение.
`pending`       | -          | `.btn--pending`           | Ожидание чего-либо (к примеру, ответа севера после асинхронной отправки формы).
`info`, `meta`  | -          | `.post__info`             | Информация о какой-либо сущности.
`body`          | -          | `.post__body`             | Главная контентная часть чего-либо.
`cart`          | -          | `.cart`                   | Корзина в магазине.
`content`       | -          | `.post__content`          | Содержимое чего-либо.
`section`       | -          | `.subscribe-form__section` | Крупный раздел чего-либо.
`page`          | -          | `.page`                   | Страница (обычно, корневой элемент).
`search`        | -          | `.search-form`            | Поиск.
`socials`       | -          | `.socials__list`          | Социальные сети (иконки, обычно).
`extra small`   | `xs`       | `.col-xs-6`               | Очень маленький.
`small`         | `sm`       | `.col-sm-6`               | Маленький.
`medium`        | `md`       | `.col-md-6`               | Средний.
`large`         | `lg`       | `.col-lg-6`               | Большой.
`extra large`   | `xl`       | `.col-xl-6`               | Очень большой.
`extra extra large` | `xxl`  | `.col-xxl-6`              | Очень-очень большой.
`narrow`        | -          | `.btn--narrow`            | Узкий.
`wide`          | -          | `.btn--wide`              | Широкий.
`tablet`        | -          | `.filter--tablet`         | Планшеты (ориентировочно до 12 дюймов).
`phone`, `mobile` | -        | `.filter--phone`          | Мобильные устройства (телефоны до 5 дюймов).
`carousel`, `slider` | -     | `.promo__slider`          | Карусель, слайдер (несколько сменяющих друг друга слайдов).
`notebook`, `laptop` | -     | `.filter--laptop `        | Ноутбуки.
`desktop`       | -          | `.filter--desktop `       | Настольные компьютеры.
`header`        | -          | `.page-header` `.post__header` | Верхняя часть, «шапка».
`footer`        | -          | `.page-footer` `.post__footer` | Нижняя часть, «подвал».
`additional`    | `add`      | `.location__btn-add`      | Добавление чего-либо.
`background`    | `bg`       | `.top-rated--bg-gray`     | Фон (чаще — какое-то изменение фонового цвета блока).
`category`      | `cat`      | `.post__cats`             | Рубрика(и).
`label`         | -          | `.label`                  | Метка, тег.
`name`          | -          | `.product__name`          | Название.
`number`        | `num`      | `.field-text--num`        | Число.
`item`, `element`, `part` | `el`     | `.nav__list-item`, `.filter__part` | Часть, элемент. Отдельная «единица». Универсальное слово, если не удаётся придумать что-то специфическое.
