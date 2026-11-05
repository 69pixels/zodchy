# spec/sections/03-team.md

figma: узел `996:3363`, `TODO(human)`: id
section: NEW `scroll-horizontal / track`
variants_to_show: []

## Задача секции
Показать команду и тон бренда; горизонтальная лента управляется вертикальным скроллом.

## Контент
- Подписи сверху: «15+ years of VDI expertise.» · «15+ years of making technology seamless, so people can do their best work.»
- 8 человек (фото, имя, роль): Rod Janson — Co-Founder; Marc Leger — Co-Founder; Earl Lumpkins — CISO; Nick Volosin — CTO; Kevin González — Partner, CWO, Technology Lead; Dan Godlewski — Partner, Technology Lead; Bill Sivill — VP IT Infrastructure; Kyle Musch — VP of Technology Solutions.
- CTA-карточка (розовая): «Get to know the team better» → `#team` (страницы команды нет, `TODO`).
- Заголовок: «We're serious about what we do, but we don't take ourselves too seriously.»

## Раскладка
- Desktop: ряд карточек с разной высотой фото (321–409 в единицах макета), заголовок снизу по центру.
- Mobile: `TODO(human)`.

## Состояния и интерактив
- Нет (карточки людей без ссылок).

## Моушн
- Скролл: сцена высотой `H + 0,45H + 1,25·travel + 0,3H`; лента сдвигается на `easeIO(k)·0,15·travel + k·0,85·travel`; пауза 0,45H в начале.
- Раскадровка: 4 кадра в Figma.
- Reduced motion: лента статична с обычной горизонтальной прокруткой.

## Переход из предыдущей / в следующую секцию
Светлая секция → «Break» (фото).

## Критерии приёмки
- [ ] Все 8 карточек и CTA доходят до видимой зоны.
- [ ] Горизонтальный скролл доступен с клавиатуры в режиме reduced motion.
- [ ] Alt-тексты у фото.

## TODO(human)
- Страница или раздел «About / Team» для CTA.
- Мобильное поведение ленты.
