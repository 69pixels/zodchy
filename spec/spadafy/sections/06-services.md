# spec/sections/06-services.md

figma: узел `996:3363` (7 кадров раскадровки), `TODO(human)`: id
section: NEW `scroll-scene / frame-services` + `mark / s-draw`
variants_to_show: []

## Задача секции
Показать шесть услуг как «связанную систему»; самая сложная сцена страницы.

## Контент
- h2: «Connected at every level: our thinking, our people, and our services.»
- Текст: «Technology can be complex. We get that.» / «Spadafy exists to make it feel simple. We look at the whole picture, from identity and security to infrastructure, cloud and everything in between.» / «Every part plays a role. Every service pulls its weight. It's a connected system, designed to work together.»
- 6 услуг (заголовок, текст, «Learn more →» → `#contact`; фото слева): VDI Implementation · VDI assessments and architecture design · VDI Managed Services · User Experience & Performance Optimization · Hybrid Cloud Modernization · Imprivata Support. Описания — в `index.html`.
- Метка «Services», номер услуги, знак S (рисуется), кнопка «Let's Talk».

## Раскладка
- Desktop: фото на весь экран → вписывается в контейнер слева; справа колонка карточек услуг скроллится.
- Mobile: `TODO(human)`; черновик: контейнер сверху, карточки под ним.

## Состояния и интерактив
- Активная услуга определяется по скроллу (`aria-live` у номера); фото меняются кроссфейдом 800 мс.
- «Learn more →» — все ведут на `#contact` (заменить, когда появятся страницы услуг).

## Моушн
- Скролл-фазы: A — parallax фото и дрейф текста вниз (`max(1,3H, 3·A)`); B — текст гаснет, кадр вписывается через `clip-path: inset()` (0,8H); C — карточки въезжают справа (0,5H); D — скролл карточек, смена фото; E — выдержка (0,35H).
- Знак S: пунктир по контуру (0–48 %) → заливка по «хребту» (40–90 %) → сплошной контур (88–100 %), через `stroke-dasharray`.
- Раскадровка: 7 кадров в Figma.
- Reduced motion: статичные блоки: фото, текст, список карточек, знак S собран.

## Переход из предыдущей / в следующую секцию
Из «Green flags» (белая) → «Break Care».

## Критерии приёмки
- [ ] Фазы идут по порядку при скролле вперёд и назад.
- [ ] Номер и фото соответствуют активной карточке.
- [ ] Знак S собирается плавно и совпадает с логотипом.
- [ ] Статичная версия при reduced motion читаема.

## TODO(human)
- Ссылки «Learn more →» (страницы услуг?).
- Мобильная раскладка; параметры фаз вынести в атрибуты секции.
