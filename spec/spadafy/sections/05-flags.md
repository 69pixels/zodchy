# spec/sections/05-flags.md

figma: узел `996:3363` (6 кадров раскадровки), `TODO(human)`: id
section: NEW `stack / cards-sticky` + `map / dotted-world`
variants_to_show: []

## Задача секции
Подтвердить масштаб пятью «зелёными флагами»; каждый — карточка с анимированной картой.

## Контент
- h2: «Our green flags».
- 5 карточек:
  1. Flag 001 — «40,000+ total number of desktops managed»; карта `desktops` (мерцающие точки).
  2. Flag 002 — «200+ customers»; карта `customers` (штаб-квартира + лучи).
  3. Flag 003 — «Global delivery experience»; карта `regions`.
  4. Flag 004 — «15 years of VDI experience»; карта `timeline` (2011 → 2026).
  5. Flag 005 — «Expertise across 30+ technology partners»; логотипы: Microsoft Azure, Citrix, Nerdio, Imprivata, Omnissa.
- Данные карт декоративные («representative locations»), реальные не нужны.

## Раскладка
- Desktop: карточки стопкой, у каждой видна шапка (шаг 88·u), последняя тоже закрепляется.
- Mobile: `TODO(human)`; черновик: шаг 100 px.

## Состояния и интерактив
- Карта проигрывается, пока карточка открыта (≥ 60 % высоты на экране); закрыли — пауза, открыли — продолжение, дошла — держит финал.

## Моушн
- Скролл: высота `H + (travel + 0,35H)·0,77`; карточки `translateY = max(stackTop + i·step, natural)`.
- Карта: `fm-twinkle`, `fm-draw`, `fm-pop`, `fm-light`, `fm-pulse`; при reduced motion — финальный кадр.
- Раскадровка: 6 кадров в Figma.

## Переход из предыдущей / в следующую секцию
Из «Break» → белая секция → «Services».

## Критерии приёмки
- [ ] Каждая карта играет только в открытом состоянии.
- [ ] При reduced motion показан финальный кадр.
- [ ] Alt-описания карт.

## TODO(human)
- Сохранить исходник генерации точек (`dotted-world-map.tsx`) в репозитории.
- Мобильная раскладка.
