# spec/sections/02-hero-intro.md

figma: узел `996:3363` (две верхние строки раскадровки), `TODO(human)`: id
section: NEW `hero / mask-reveal`
variants_to_show: []

## Задача секции
Назвать позиционирование и по скроллу подвести к «кто мы» с эффектом раскрытия фонового изображения.

## Контент
- h1: «Your First & Last VDI Partner».
- Метка: «So, who are we?»; текст: «OK before we go any further there's something you should know.»
- Текст 1: «We're very serious about virtual desktop infrastructure {VDI} and End User Computing.»
- Текст 2: «We bring deep expertise and help companies figure out what technology they should use, how to implement it correctly, and then we help manage and support it all once it's in place.»
- Фон: изображение `hero-bg.jpg` (в прототипе), в Figma — коллаж/видео; в будущем `<video>`.

## Раскладка
- Desktop: фон неподвижен на весь экран; заголовок по центру; плашка с текстом поднимается снизу; окно-маска 409×234 раскрывается до размера плашки.
- Mobile: `TODO(human)`; в прототипе окно стартует с 40 % размера.

## Состояния и интерактив
- Нет.

## Моушн
- Скролл: текст 1 и 2 заливаются серый → белый по мере прохода (старт при `0,92·H − top`, длина `0,5·H`); маска — `clip-path: inset(...) round 32·u`, прогресс `easeOut((H − top)/(0,6·H))`; изображение в маске подогнано под фоновое.
- Раскадровка: две верхние строки в Figma.
- Reduced motion: текст залит, маска раскрыта, без анимации.

## Переход из предыдущей / в следующую секцию
В «Команду» через светлую зону.

## Критерии приёмки
- [ ] Маска и фон совпадают пиксель в пиксель при раскрытии.
- [ ] Текст читается при reduced motion.
- [ ] Hero с видео не ломает LCP (постер).

## TODO(human)
- Уточнить, что именно в hero по макету (фото / видео / коллаж).
