# spec/sections/04-break.md

figma: узел `996:3363`, `TODO(human)`: id
section: NEW `statement / card-rise-fill`
variants_to_show: []

## Задача секции
Заявить подход «We're in, we're all in» поверх фото.

## Контент
- h2: «When We're In, We're All In.»
- Текст: «That means helping your organization design, implement, operate and modernize the environments that your employees rely on every day, from A to Z, improving end-user experience so that everything simply works as it should.»
- Фон: фото `break-bg.jpg`.

## Раскладка
- Desktop: фото на весь экран; розовая карточка поднимается и закрепляется в нижней половине.
- Mobile: `TODO(human)`.

## Состояния и интерактив
- Нет.

## Моушн
- Скролл: высота `H·(1 + 0,63 + 0,12)`; карточка стартует на `H`, поднимается до `min(0,5H, H − высота содержимого)`, `easeOut`; заголовок заливается при подъёме на 25–75 %, текст — 45–100 %.
- Раскадровка: 5 кадров в Figma.
- Reduced motion: карточка на финальной позиции, текст залит.

## Переход из предыдущей / в следующую секцию
Из «Команды» (светлая) → фото → «Green flags» (белая).

## Критерии приёмки
- [ ] Карточка не перекрывает лицо на фото.
- [ ] Заливка совпадает с подъёмом.

## TODO(human)
- Мобильная раскладка.
