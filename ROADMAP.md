# ROADMAP — дорожная карта проекта

**Статус:** живой навигационный документ v0.8  
**Актуально на:** 2026-10-20  
**Точка:** v0.7.3 FROZEN FOR CORPUS A; D-071 разрешает одну последнюю синхронизацию manuscript v0.7 → v0.7.1 перед formal coding Work 2.

---

# 1. Канонические файлы — порядок чтения

## Статья №1

1. `OLGA_ARTICLE_PASSPORT.md` — краткая текущая постановка статьи.
2. `ARTICLE1_MANUSCRIPT.md` — текущий канонический manuscript v0.6; до Work 2 допускается одна точечная синхронизация внешнего draft v0.7 → v0.7.1 по D-071, после канонизации — MANUSCRIPT FREEZE.
3. `ARTICLE1_THEORETICAL_REVIEW.md` — ближайшие предшественники, research gap и риски.
4. `DECISIONS.md` — полный журнал решений; D-070 фиксирует frozen instrument v0.7.3, D-071 — однократную синхронизацию manuscript перед Corpus A.
5. `ARTICLE1_REDTEAM_DELTA.md` — актуальные исторические red-team решения D-037–D-049 и контекст раннего сужения claims.

## Инструмент / Corpus A

6. `ARTICLE1_CODING_MATRIX.md` — v0.7.3 FROZEN FOR CORPUS A.
7. `ARTICLE1_CODING_MANUAL.md` — полный операциональный manual v0.7.3.
8. `ARTICLE1_CORPUS_A_REQUIREMENTS.md` — frozen prompting map `Т / t⁰ / Т?`.
9. `ARTICLE1_CORPUS_A_PREDICTIONS.md` — dated internal pre-analysis registration до формального coding работ 2–6.
10. `ARTICLE1_CORPUS_A_PILOT_SIBERGY.md` — Sibergy / Work A, development case.
11. `ARTICLE1_FINANCIAL_ADAPTER_A.md` — optional prototype, outside frozen CORE.

## Школа / публикационный контур

12. `MASTER.md` — каноническая модель школы.
13. `DEFINITIONS.md` — понятийное ядро.
14. `ARTICLES.md` — архитектура публикационного корпуса.
15. `SOURCES.md` — внешняя верификация.
16. `README.md` — карта репозитория.

---

# 2. North Star

> **Экономика — среда; модель — инструмент; мышление — результат.**

Рабочая траектория:

`реальность → различение → понятие → модель → система → измерение → решение → действие → обратная связь`.

Принцип:

> **сначала сущность и уровень системы — затем число и метрика.**

Текущая исследовательская задача уже не расширять метасхему, а сделать её **воспроизводимой и опровержимой**.

---

# 3. Статья №1 — текущая постановка

> **«От категории к целостной экономической модели: архитектура когнитивных операций в экономическом образовании»**

Объект и предмет заморожены D-057–D-062.

## Центральный механизм

`O_profile = O_core ∪ O_repr ∪ O_practice`.

Задача / контекст актуализируют; педагогический дизайн выбирает / тренирует.

## Три продукта

1. теория — архитектура когнитивных операций;
2. метод — протокол реконструкции;
3. инструмент — coding matrix.

`теория → метод → инструмент → данные → проверка`.

## Model level

`M0 → проектируемое воздействие → Δ_project → M1`.

Проект — контекст интеграции, а не объект статьи.

---

# 4. Novelty — текущий статус

Рабочая заявка:

> **воспроизводимая процедура перехода от структуры экономического содержания к наблюдаемым следам когнитивных операций в целостной экономической модели учебного проекта.**

Целевой **novelty level 2** пока не достигнут.

Для него необходимы:

- теоретическая выводимость;
- применимость manual независимым кодировщиком;
- различимость профилей;
- inter-rater agreement;
- predictions, зафиксированные до формального анализа нового материала.

Corpus A даёт только internal prospective pilot после prior exposure; более сильный тест остаётся за Corpus B.

---

# 5. Freeze 1 — Corpus A

Исторический reproducibility freeze:

> **v0.7.2 — SHA `91b173464c6aec7d9f756f3dc5eb568ccf944457`**

Финальный patch перед formal coding:

> **v0.7.3 — FROZEN FOR CORPUS A**

v0.7.3 не меняет 14 строк CORE и теоретическую архитектуру. Изменены только reproducibility details:

- честный статус prior exposure;
- requirement map строк 1 / 8 / 11 → `Т?`;
- уникальные обозначения кодов;
- единое правило `О`;
- prediction A6 `prompting ≠ integration`;
- optional Financial Adapter A;
- восстановленный полнотекстовый `DECISIONS.md`.

После fixed SHA v0.7.3 никакие правила не меняются на работах 2–6.

Новая трудность:

`existing rule → код` **или** `НД` → Issue Log.

---

# 6. Corpus A

Шесть итоговых проектов одного курса / одной архитектуры:

1. Sibergy / Work A — development case;
2. Belobank;
3. Young Tourists;
4. Easy Stay;
5. FitBloom;
6. «Термоядерный синтез».

Sibergy участвовала в разработке инструмента. Работы 2–6 — **prospective internal pilot cases**.

### Prior exposure

Автор курса ранее знает работы; некоторые артефакты предварительно просматривались / извлекались в процессе подготовки корпуса. Поэтому Corpus A не является blind-unseen sample.

Корректная доказательная граница:

> **правила и predictions frozen до формального стандартизированного coding по v0.7.3.**

### Для каждой работы получить

- `Н / И / О / К / С`;
- дефициты с evidence;
- contradiction register;
- course-provenance;
- profile 3–5 предложений;
- новые Issue Log entries.

---

# 7. Cross-case analysis после шести работ

Проверить:

- discrimination между работами;
- floor / ceiling effects;
- устойчивость `Н` vs `И`;
- повторяемость переходных дефицитов;
- поведение строки 8 `Δ_project`;
- criterion vs alternative;
- жанровый эффект на `О`;
- строки с высокой интерпретативностью;
- что действительно объясняет frozen prompting map;
- A1–A6 vs результаты;
- какие результаты были ожидаемы из prior exposure, а какие реально появились в formal coding.

Только после этого решать о v0.8.

---

# 8. Возможная v0.8

v0.8 допустима **только после полного Corpus A**.

Кандидаты уже в Issue Log:

- temporal causality;
- value / using-system threshold;
- переходы между системными уровнями;
- M1-4 vs P2;
- функциональный contradiction register для cross-domain материала;
- technical finance / engineering adapters.

---

# 9. Freeze 2 — cross-domain

После решения Issue Log:

> **cross-domain freeze**

Перед ним проверить, что core не сводится к бизнес-плану:

- value → economic effect, а не только payment / revenue;
- resource provision / financing не сводится к investor;
- опорные величины реестра задаются функционально;
- engineering / tech project проходит core без изменения архитектуры.

---

# 10. Corpus B

Около 15 работ «Техностартапа».

Только после Freeze 2:

- independent human coders;
- заранее фиксированная инструкция;
- межэкспертное согласие по измерениям;
- при необходимости Krippendorff α / Cohen κ — статистика выбирается по реальной структуре кодов, не заранее ради вида;
- unseen-case test;
- проверка более сильной версии novelty level 2.

AI coding не считается доказательством reproducibility.

---

# 11. Параллельный теоретический трек

После MANUSCRIPT FREEZE v0.7.1 и во время Corpus A manuscript не переписывать, но можно продолжать source verification:

- Гальперин / Талызина / Давыдов — точные страницы;
- 4C/ID / Decoding / CTA — novelty audit;
- economics education — ближайшие аналоги;
- ISO / IFRS / SNA — первичные формулировки;
- требования Terra Economicus.

Новый внешний источник должен **уточнять / заменять / добавлять слой**, а не механически расширять литературу.

---

# 12. Следующий NEXT

> **Однократно выполнить разрешённую D-071 точечную редакцию external draft v0.7 → v0.7.1, канонизировать manuscript в GitHub и немедленно установить MANUSCRIPT FREEZE.**

До этой редакции **v0.7.1 не считается готовым manuscript**. После freeze следующий шаг — **формально кодировать Work 2 Corpus A строго по frozen instrument v0.7.3**, затем Work 3 → 4 → 5 → 6 → cross-case analysis. Manuscript после freeze не редактировать до завершения Works 2–6.

---

# 13. Milestones

- ✅ Object / subject / mechanism frozen.
- ✅ Manuscript v0.6.
- ✅ Three-product architecture.
- ✅ Sibergy development stress-test.
- ✅ CORE + adapters.
- ✅ Historical v0.7.2 freeze SHA.
- ✅ v0.7.3 reproducibility patch.
- ✅ Corpus A prompting map and dated pre-analysis predictions.
- ✅ v0.7.3 fixed SHA / freeze ref.
- ✅ D-071 one-time manuscript synchronization decision.
- ⏳ v0.7 → v0.7.1 point edit, canonicalization and MANUSCRIPT FREEZE.
- ⏳ Works 2–6 coded.
- ⏳ Corpus A cross-case analysis.
- ⏳ v0.8 decision.
- ⏳ Cross-domain freeze.
- ⏳ Corpus B human coding / reliability.
- ⏳ Post-Corpus manuscript revision.

Критерий зрелости проекта:

> **что является объектом → как определено → какое различение / отношение требуется → какой след мы наблюдаем → какое правило кодирования применяем → что могло бы опровергнуть вывод?**