# BACKLOG — развитие Zodchy

Статусы: `[ ]` открыта · `[~]` в работе · `[x]` готова. Когда подключим GitHub Issues, задачи переедут туда.

## Этап 0 — запуск
- [x] Z-001 Создать репозиторий `zodchy` в GitHub студии, запушить этот каркас
- [x] Z-002 Подключить репозитории Ular и Spadafy (read) к сессии — клоны в `../ular` (последняя версия: `home-v8/`) и `../spadafy` (последняя версия: `prototype-v2/`); репозитории: github.com/69pixels/ular, github.com/69pixels/spadafy
- [x] Z-003 Закрыть открытые вопросы из `docs/HANDOFF.md` — решено: GitHub Issues, GSAP + ScrollTrigger, GitHub Pages → Cloudflare Pages к пилоту. Осталось: авторизовать Figma MCP

## Этап 1 — аудит
- [x] Z-010 Аудит Ular: код прототипа + Figma → `audit/ular.md` (секции, варианты, анимации, атомы, костыли). Остались открытые вопросы в конце файла и выгрузка оставшихся фреймов Figma
- [x] Z-011 Аудит Spadafy → `audit/spadafy.md` (остались открытые вопросы и выгрузка раскадровки по подузлам Figma)
- [x] Z-012 Сводный инвентарь: что совпадает, что кандидат в библиотеку → `audit/inventory.md`

## Этап 2 — spec
- [ ] Z-020 Ретро-spec Ular по шаблонам `templates/spec/`
- [ ] Z-021 Ретро-spec Spadafy
- [ ] Z-022 Уточнить шаблоны spec по итогам двух проектов

## Этап 3 — стартер v0
- [ ] Z-030 Astro-каркас `starter/`: токены wireframe + brand, подключение темы Graphical
- [ ] Z-031 Первые секции библиотеки из инвентаря (с README и preview)
- [ ] Z-032 Первые пресеты анимаций + reduced motion
- [ ] Z-033 Каталог `/library`
- [ ] Z-034 Review-панель для переключения вариантов секций

## Этап 4 — пилот
- [ ] Z-040 Вёрстка пилотного проекта на стартере, preview-деплой на ветку
- [ ] Z-041 Роли Extractor и QA (`.claude/agents/` + описание для Codex)
- [ ] Z-042 Ретро пилота → `docs/process.md`
