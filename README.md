https://github.com/ArishaMak/ono-tebe-nado-fd

Описание проекта
«Оно тебе надо» — первый проект по вёрстке в курсе Fullstack Developer от Yandex Practicum (спринт 1). Сайт статичный, с семантической HTML-структурой, фокусом на CSS: гриды для шапки/футера, флекс для меню/карточек, оверлеи и фоны. Дизайн с фиксированной шириной для ноутбуков, прогрессивный подход (эскиз → детализация).
В проекте всё переиспользуемо (оверлей, адрес в header/footer).

Возможности
Структура: Семантическая (header, main с sections, footer; nav, address, article в карточках).
Шапка: Грид с меню (флекс + gap), логотипом и адресом (tel/mailto); активные ссылки без подчёркивания.
Обложка: Фон с оверлеем, h1 с spans для выравнивания строк (text-transform, letter-spacing), подзаголовок с word-spacing, прозрачная кнопка.
Лоты: Сетка карточек (флекс с gap, перенос строк), фоны (cover/center), оверлеи; 3 типа (film/book/picture).
Об аукционе: Грид колонок (левая = ширине карточки), круглый логотип (flex center), тексты с gap.
Футер: Грид, переиспользованный адрес, меню (центр), соцсети (иконки).
Оптимизации: Pixel Perfect подход, сброс стилей (global.css), min-height для обложки.

Нет адаптива (пока), но резиновые отступы.

Технологии
Верстка:
HTML5 (семантика: header/main/footer, nav/address/article, spans для типографики).
CSS3 (Grid/Flexbox, gap, background-size/position, overlay с absolute/relative/z-index, text-transform/letter-spacing/word-spacing).

Шрифты: Локальные (fonts.css), глобальный family.
Инструменты:
Figma (макет, Pixel Perfect).
Git/GitHub (версионный контроль).


Стили: global.css (reset), style.css (локальные).

Чистый vanilla HTML/CSS, без JS.
