# Prompt: interview debrief

Используй: `Примени prompts/interview-debrief.md к raw/interviews/<file>`

---

Это AJTBD-интервью (или switch/expert). Разбери его по методологии Замесина.

1. Прочитай транскрипт.
2. Вытащи (используй скилл `zamesin-pm:zamesin-interview-analyze` если установлен):
   - все работы (Jobs), их типы (Core / Big / Micro / Tax)
   - граф работ
   - consideration set
   - активирующее знание
   - триггеры свитча
   - барьеры
   - топ-5 рычагов с MVP-экспериментами
3. Создай `wiki/sources/summary-interview-<short-name>.md` по шаблону.
4. Если новый сегмент — создай/обнови `wiki/segments/<segment>.md`.
5. Обнови `wiki/customers/<company-or-person>.md`.
6. Обнови `wiki/index.md` и `wiki/log.md`.
7. В конце скажи Iar:
   - какое из 4 критериев PMF Замесина продвинулось этим интервью
   - какие новые гипотезы появились (RAT)
   - кого ещё интервьюировать следующим
