# Prompt: competitor research

Используй: `Примени prompts/competitor-research.md к <имя конкурента>`

---

Исследуй конкурента и добавь его в Lauda wiki.

1. Через WebSearch / WebFetch собери:
   - официальный сайт (главная, pricing, features, about)
   - блог / changelog (что выпускали последние 6 месяцев)
   - отзывы на G2 / Capterra / Trustpilot
   - LinkedIn (размер команды, рост)
   - последние новости (раунды, партнёрства, продукты)
2. Скачай ключевые скриншоты в `raw/competitors/<name>/` (или сохрани md с текстом, если изображений нет).
3. Создай страницу `wiki/competitors/<name>.md` по шаблону `wiki/_templates/competitor.md`.
4. Обнови `wiki/index.md` и `wiki/log.md`.
5. Если этот конкурент бьёт нас в каком-то сегменте — отметь это и предложи зафайлить ADR "как мы отвечаем на X".
6. В конце дай Iar 3 коротких инсайта, что значит этот конкурент для Lauda.
