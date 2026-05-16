# raw/ — immutable исходники

**LLM-агент сюда только читает. Никогда не модифицирует.**

## Подпапки

- `interviews/` — транскрипты AJTBD / switch / экспертных интервью. Имя: `YYYY-MM-DD-<тип>-<кто>.md`
- `meetings/` — записи команды, звонков с клиентами. Часто `.mp3/.m4a` (в gitignore) + транскрипт `.md`.
- `competitors/` — материалы конкурентов: скриншоты сайтов, фичи, цены. Каждому конкуренту — подпапка.
- `market-research/` — внешние отчёты, статьи о рынке инфлюенс-маркетинга.
- `customer-feedback/` — фидбэк, NPS, support-тикеты в виде экспортов.
- `strategy-docs/` — внешние стратегические документы (отчёты консультантов, инвестиционные дешборды).
- `product-feedback/` — отзывы пользователей Lauda (после запуска).
- `financial/` — сырые финансовые выгрузки (банк, бухгалтерия). Будь аккуратен с приватными данными.
- `assets/` — картинки, скриншоты, обложки.

## Правила нейминга

```
YYYY-MM-DD-короткое-описание.расширение
```

Примеры:
- `2026-05-16-interview-acme-cmo.md`
- `2026-05-20-competitor-hypeauditor-pricing.png`
- `2026-04-30-influencer-marketing-report-mckinsey.pdf`

## Что класть в frontmatter (если md)

```yaml
---
url: https://...
author: ...
date: 2026-05-16
type: interview | article | report | meeting-transcript
clipped_at: 2026-05-16
---
```
