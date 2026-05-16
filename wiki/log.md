# Activity Log

Append-only хронологический лог. Каждая запись — ingest, query, lint, update или decision.

Формат заголовка: `## [YYYY-MM-DD HH:MM] <type> | <короткое название>`

Парсится через `grep "^## \[" log.md | tail -10`.

---

## [2026-05-16 09:00] update | initial schema and structure

**Source:** ручная инициализация (Iar + Claude)
**Pages created:**
- `CLAUDE.md` — schema-файл по методу Karpathy
- `README.md` — описание репо для команды
- `.gitignore`
- `wiki/index.md` — пустой каталог
- `wiki/log.md` — этот файл
- `wiki/overview.md` — стартовая высокоуровневая страница Lauda
- Структура папок `raw/` и `wiki/`

**Notes:**
- Wiki организована по 3-слойной архитектуре Karpathy: `raw/` (immutable) → `wiki/` (LLM-owned) → `CLAUDE.md` (schema).
- Используется методология AJTBD (Замесин) как основная продуктовая рамка.
- Связан с отдельным репо `lauda-web` для разработки сайта/веб-приложения.
- Следующий шаг: первый ingest — целевой сегмент или конкурент.
