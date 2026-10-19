# ROADMAP — дорожная карта проекта

**Статус:** живой навигационный документ v0.7  
**Актуально на:** 2026-10-19  
**Точка:** Sync II — Reproducibility Freeze перед работами 2–6 Corpus A.

---

# 1. Канонические файлы — порядок чтения

## Статья №1

1. `OLGA_ARTICLE_PASSPORT.md` — краткая текущая постановка статьи.
2. `ARTICLE1_MANUSCRIPT.md` — полный manuscript v0.6, заморожен на период Corpus A.
3. `ARTICLE1_THEORETICAL_REVIEW.md` — ближайшие предшественники, research gap и риски.
4. `DECISIONS.md` — решения; D-063–D-069 фиксируют reproducibility freeze.
5. `ARTICLE1_REDTEAM_DELTA.md` — актуальные исторические red-team решения D-037–D-049 и контекст раннего сужения claims.

## Инструмент / Corpus A

6. `ARTICLE1_CODING_MATRIX.md` — v0.7.2 FROZEN FOR CORPUS A.
7. `ARTICLE1_CODING_MANUAL.md` — полный операциональный manual v0.7.2.
8. `ARTICLE1_CORPUS_A_REQUIREMENTS.md` — frozen prompting map `Т / t⁰ / Т?`.
9. `ARTICLE1_CORPUS_A_PREDICTIONS.md` — dated preregistration до работ 2–6.
10. `ARTICLE1_CORPUS_A_PILOT_SIBERGY.md` — обезличенный Work A / development case.

## Школа / публикационный контур

11. `MASTER.md` — каноническая модель школы.
12. `DEFINITIONS.md` — понятийное ядро.
13. `ARTICLES.md` — архитектура публикационного корпуса.
14. `SOURCES.md` — внешняя верификация.
15. `README.md` — карта репозитория.

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
- predictions, зафиксированные до новых данных.

---

# 5. Freeze 1 — Corpus A

Каноническая версия инструмента:

> **v0.7.2 — FROZEN FOR CORPUS A**

Freeze package:

- matrix;
- full manual;
- requirements map;
- preregistered predictions;
- anonymized Work A pilot;
- full Issue Log;
- decisions D-063–D-069;
- fixed commit SHA.

После фиксированного SHA никакие правила не меняются на работах 2–6.

Новая трудность:

`existing rule → код` **или** `НД` → Issue Log.

---

# 6. Corpus A

Шесть итоговых проектов одного курса / одной архитектуры:

1. Work A / Sibergy — development case;
2. Belobank;
3. Young Tourists;
4. Easy Stay;
5. FitBloom;
6. «Термоядерный синтез».

Work A участвовала в разработке инструмента. Работы 2–6 — **prospective internal pilot cases**. Они сильнее ретроспективного описания, но слабее независимой валидации.

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
- preregistered predictions vs результаты.

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
- opornye variables реестра задаются функционально;
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

Во время Corpus A не переписывать manuscript, но можно продолжать source verification:

- Гальперин / Талызина / Давыдов — точные страницы;
- 4C/ID / Decoding / CTA — novelty audit;
- economics education — ближайшие аналоги;
- ISO / IFRS / SNA — первичные формулировки;
- требования Terra Economicus.

Новый внешний источник должен **уточнять / заменять / добавлять слой**, а не механически расширять литературу.

---

# 12. Следующий NEXT

После завершения Sync II и фиксации commit SHA:

> **кодировать Work 2 Corpus A строго по v0.7.2.**

Затем Work 3 → 4 → 5 → 6. Никакого cross-case переписывания до завершения всех пяти новых кодирований.

---

# 13. Milestones

- ✅ Object / subject / mechanism frozen.
- ✅ Manuscript v0.6.
- ✅ Three-product architecture.
- ✅ Work A development stress-test.
- ✅ CORE + adapters.
- ✅ v0.7.2 frozen core/manual.
- ✅ Corpus A prompting map and preregistered predictions.
- ⏳ Works 2–6 coded.
- ⏳ Corpus A cross-case analysis.
- ⏳ v0.8 decision.
- ⏳ Cross-domain freeze.
- ⏳ Corpus B human coding / reliability.
- ⏳ Manuscript next version.

Критерий зрелости проекта:

> **что является объектом → как определено → какое различение / отношение требуется → какой след мы наблюдаем → какое правило кодирования применяем → что могло бы опровергнуть вывод?**