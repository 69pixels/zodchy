# spec/sections/08-care.md

figma: узел `996:3363` (2 кадра раскадровки), `TODO(human)`: id
section: NEW `scroll-pin / crossfade`
variants_to_show: []

## Задача секции
Показать, для кого работает технология: врачи, сотрудники, ИТ.

## Контент
3 сцены (фото, заголовок, текст):
1. «Giving doctors more time with patients.» — «A clinician needs access to the applications their work depends on.»
2. «Work from anywhere. Stay connected everywhere» — «Give employees seamless access to their familiar desktop and applications from virtually anywhere.»
3. «Less time fixing. More time improving and building» — «IT needs a manageable way to support people, desktops and access, focusing on what's next, not what's broken.»

## Раскладка
- Desktop: sticky-сцена на весь экран, текст внизу поверх затемнения.
- Mobile: `TODO(human)`.

## Состояния и интерактив
- Нет; неактивные тексты `aria-hidden`.

## Моушн
- Скролл: высота `3,4H`; `x = clamp(s/range)·2·1,15 − 0,075`; фото кроссфейдом (ширина перехода 0,32) со `scale 1,08→1`; текст — fade + сдвиг 60·u.
- Раскадровка: 2 кадра в Figma (сцены 2 и 3).
- Reduced motion: три блока подряд.

## Переход из предыдущей / в следующую секцию
Из «Break Care» (белая) → «Testimonials».

## Критерии приёмки
- [ ] Один активный текст в любой момент.
- [ ] Alt у фото.
- [ ] Статика при reduced motion.

## TODO(human)
- Мобильное поведение.
