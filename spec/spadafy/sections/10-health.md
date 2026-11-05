# spec/sections/10-health.md

figma: узел `996:3363` (3 кадра раскадровки), `TODO(human)`: id
section: NEW `steps / glide-in`
variants_to_show: []

## Задача секции
Продать бесплатный Health Check тремя простыми шагами.

## Контент
- h2: «Sometimes you just need another set of eyes.»
- Лид: «We've spent years working in VDI and infrastructure environments of all shapes and sizes. Our free Health Check puts that experience to work with a quick review of your environment and the challenges you're seeing.»
- 3 шага: 01 «Book a Free Consultation» · 02 «Review Your Environment» · 03 «Get a Clear View of What's Next» (тексты — в `index.html`).

## Раскладка
- Desktop: тёмная секция; шаги — строки со смещением; левый отступ каждой последующей больше.
- Mobile: `TODO(human)`.

## Состояния и интерактив
- Нет.

## Моушн
- Скролл: каждый шаг въезжает справа за ~0,8H скролла со сдвигом старта на 0,07H; сдвиг от `(1200 + i·120)·u` до 0; инерция lerp 0,12 в rAF.
- Раскадровка: 3 кадра.
- Reduced motion: шаги на месте.

## Переход из предыдущей / в следующую секцию
→ «Contact» в той же тёмной зоне.

## Критерии приёмки
- [ ] Шаги не уходят за экран в статике.
- [ ] Порядок шагов читается без анимации.

## TODO(human)
- Куда ведёт запись на Health Check (форма/ссылка/`mailto:`)? Сейчас CTA отдельной нет.
