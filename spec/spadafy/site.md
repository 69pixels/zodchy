# spec/site.md — Spadafy (ретро-spec)

Ретро-spec по прототипу `prototype-v2` и аудиту `audit/spadafy.md`. Дизайн десктопа **не утверждён**, мобильных макетов нет: spec описывает текущее состояние и будет меняться вместе с дизайном. Пробелы помечены `TODO(human)`.

## О проекте
- Клиент / продукт: Spadafy — партнёр по VDI (виртуальные рабочие столы) и End User Computing, Сиэтл, США.
- Цель лендинга: показать экспертизу, масштаб и подход («Your First & Last VDI Partner»), подвести к разговору.
- Целевое действие (CTA): «Let's Talk» → `mailto:info@spadafy.com` (формы нет); вторичное — бесплатный Health Check.
- Аудитория: ИТ-директора и инфраструктурные команды (здравоохранение, корпорации).
- Тон и характер бренда: серьёзно о деле, но с юмором («we don't take ourselves too seriously»); плотная конденсированная типографика, графит + розовый + оранжевый, мощное движение.

## Источники
- Figma: `jgzJ9a3LPi61XRveiu2csk`; рабочая раскадровка главной — узел `996:3363` (страница «Main Design Pavel 🤝 Vadim», `599:2180`); страница «The tech» — `991:2713`. Остальные страницы: Website Anatomy, Prototype Exploration, Prototype WIP, Design.
- Код прототипа: `github.com/69pixels/spadafy`, `prototype-v2/`. Аудит: `audit/spadafy.md`. Скриншот: `design/spadafy/`.
- Бренд-материалы: логотип и знак S (SVG), фото команды, услуг, care.
- Тема Graphical: `zodchy-theme/` для атомов; бренд-токены — отдельный слой.

## Стадия
`hi-fi` (дизайн на согласовании, прототип = референс поведения).

## Языки
Только EN.

## Структура
Все секции — `NEW` (библиотеки ещё нет); имена — кандидаты из `audit/inventory.md`.

| # | Секция | Вариант из библиотеки | Варианты для сравнения | Файл |
|---|---|---|---|---|
| 01 | Навигация | NEW `nav / pill-collapse` | — | sections/01-nav.md |
| 02 | Hero + Intro | NEW `hero / mask-reveal` | — | sections/02-hero-intro.md |
| 03 | Команда | NEW `scroll-horizontal / track` | — | sections/03-team.md |
| 04 | Break («When we're in…») | NEW `statement / card-rise-fill` | — | sections/04-break.md |
| 05 | Green flags | NEW `stack / cards-sticky` + `map / dotted-world` | — | sections/05-flags.md |
| 06 | Services (break + сцена) | NEW `scroll-scene / frame-services` + `mark / s-draw` | — | sections/06-services.md |
| 07 | Break Care | NEW `statement / accent` | — | sections/07-breakcare.md |
| 08 | Care | NEW `scroll-pin / crossfade` | — | sections/08-care.md |
| 09 | Testimonials | NEW `carousel / testimonials-timer` | — | sections/09-testimonials.md |
| 10 | Health Check | NEW `steps / glide-in` | — | sections/10-health.md |
| 11 | Contact | NEW `cta / contact-mailto` | — | sections/11-contact.md |
| 12 | Next page («The Tech») | NEW `transition / next-page` | — | sections/12-next.md |

Страница «The Tech» (`tech.html`) — отдельная, нужна в первой версии, пока заглушка; её spec — `TODO(human)` после макета (см. `sections/12-next.md`).

## Навигация и переходы
- Меню на странице: Home (`#home`), Work (`#services`), About (`#team`), Health Check (`#healthcheck`); в раскрытом меню «Work» заменён на «Tech» → `tech.html`. `TODO(human)`: привести названия в порядок (в двух местах пункты различаются).
- Хедер: при `scrollY ≤ 24` полная панель; ниже — пилюля со знаком S и бургером; по клику раскрывается панель (Home, Tech, About, Health Check, Connect, адрес Сиэтла с часами, «Let's Talk», юр. ссылки).
- Плавный скролл/снэп: нет.
- Переходы между секциями: pinned-сцены; переход на «The Tech» — автонавигация по скроллу + ссылка-карточка (решение оставить автопереход, `DECISIONS.md`).

## Глобальный моушн
- Пресет появления по умолчанию: отдельного нет; движение управляется скроллом.
- Особые сцены: hero-маска, горизонтальная лента команды, карточка Break, стопка Green flags, сцена Services (самая сложная), Care crossfade, въезд шагов Health Check, рост карточки «The Tech».
- Reduced motion: у каждого пресета статичный фолбэк (в прототипе его нет у JS-сцен — исправить в проде); автопереход на «The Tech» отключается, остаётся клик.

## Адаптив
- Брейкпоинты: 1920 (макет), 1440 / 1024 / 768 / 375. Прототип: единственный брейкпоинт 820 px.
- Особые правила: мобильных макетов нет, мобильное поведение рисуется после утверждения десктопа.

## Вне рамок
- Форма обратной связи, CMS, аналитика, мультиязычность.
- Страницы кроме главной и «The Tech».

## TODO(human)
- Утвердить десктопный дизайн, затем нарисовать мобильные макеты.
- Статус макета «The Tech» (страница `991:2713`).
- Лицензии шрифтов (Review Condensed, Aeonik Pro Regular; Medium подставлен вместо 400).
- Названия пунктов меню (расхождение Work / Tech).
- Реальные ссылки соцсетей и юр. страницы (сейчас `#`).
- Найти исходник генератора точек карты (`dotted-world-map.tsx`).
