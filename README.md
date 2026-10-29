# City of Shadows

> Public source preview: see [PUBLICATION.md](PUBLICATION.md) for actual checks, known failures and runtime limits.

Игра-головоломка от первого лица: игрок исследует тёмный город и ищет скрытые объекты по теням от движущегося источника света.

## Особенности

- процедурная генерация скрытых объектов;
- динамический свет и тени Three.js;
- механика поиска объектов по силуэтам;
- уровни сложности на 7, 10 и 13 объектов;
- временная остановка света с cooldown;
- управление от первого лица через Pointer Lock.

## Запуск

```bash
npm install
npm run dev
```

Сборка:

```bash
npm run build
npm run preview
```

## Управление

- клик — захват мыши;
- WASD — движение;
- Space — прыжок;
- Ctrl — приседание;
- ЛКМ — пометка объекта;
- Shift — остановка света на 3 секунды;
- Esc — меню.

## Стек

TypeScript, Vite, Three.js r158 и PointerLockControls.

## Консолидация

`4d3dcave` — каноническая копия. `4d3dcave-archive` совпадает по README и package manifest на уровне Git blob SHA и предназначен для удаления.

Рекомендуемое имя репозитория: `city-of-shadows`.

См. [CHANGELOG.md](CHANGELOG.md).

## Лицензия

Для публичного релиза рекомендуется MIT после проверки лицензий всех аудио- и графических ассетов.


## Public source status — 2026-10-29

See [PUBLICATION.md](PUBLICATION.md) for the current verification scope, prototype limitations and runtime boundaries. Earlier audit checklists describe historical work.
