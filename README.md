# EconomyAssetsGoods / Когнитивное обучение экономике

> **Граница репозитория после создания School Canon**  
> `School_Canon` владеет **живой методологической архитектурой Школы управленческого мышления**.  
> `EconomyAssetsGoods` сохраняет **научную реализацию, frozen-инструменты, corpus-specific правила, manuscript и датированные исследовательские снимки понятий**.  
> Развитие School Canon не является основанием для ретроспективного изменения frozen research instruments этого репозитория.

Исследовательский репозиторий проекта **«Когнитивное обучение экономике»**, исторически также содержавший методологические материалы, из которых часть переносится в School Canon по правилам provenance и reconciliation.

Для межрепозиторных ссылок решения этого репозитория обозначаются `EAG-D-xxx`; решения School Canon — `SC-D-xxx`. Исторические номера внутри файлов не перенумеровываются.

## Текущий статус — 2026-10-20

Статья №1:

> **«От категории к целостной экономической модели: архитектура когнитивных операций в экономическом образовании»**

Текущий канонический manuscript: **v0.6**. По EAG-D-071 до formal coding Work 2 допускается одна точечная синхронизация external draft `v0.7 → v0.7.1`; после канонизации v0.7.1 — **MANUSCRIPT FREEZE / STOP EDITING THE PAPER** до завершения Works 2–6.

Кодировочный инструмент:

> **v0.7.3 — FROZEN FOR CORPUS A**

Fixed SHA: `5f905c7a15e558bb2fff34c52ee4597e296a4a90`.  
Исторический freeze v0.7.2: SHA `91b173464c6aec7d9f756f3dc5eb568ccf944457`.

Текущая стадия:

> **Однократная manuscript synchronization по EAG-D-071; frozen instrument v0.7.3 не меняется. После MANUSCRIPT FREEZE v0.7.1 следующий шаг — formal coding Work 2.**

---

# North Star исследовательского снимка

> **Экономика — среда; модель — инструмент; мышление — результат.**

> **Сначала сущность и уровень системы — затем число и метрика.**

Историческая рабочая траектория EAG:

`реальность → различение → понятие → модель → система → измерение → решение → действие → обратная связь`.

Эта запись сохраняется как контекст исследовательской разработки. Актуальная типизация последовательностей и живые школьные определения находятся в `School_Canon`.

---

# Три исследовательских продукта статьи №1

1. **Архитектура когнитивных операций** — теория / исследовательская модель статьи.
2. **Протокол реконструкции** — метод.
3. **Кодировочная матрица** — инструмент анализа учебных артефактов.

`теория → метод → инструмент → данные → проверка`.

Статус этих продуктов определяется исследовательскими решениями EAG и не повышается автоматически до канона школы.

---

# Текущая модель проектной интеграции

`M0 → проектируемое воздействие → Δ_project → M1`

Не смешивать:

- система ≠ модель системы;
- проектная деятельность ≠ представление проектируемого изменения;
- результат всей компании ≠ эффект проекта;
- критерий ≠ альтернатива;
- воспроизводимость расчёта ≠ экономическая корректность.

---

# Навигация

## Начать здесь

- [`RESEARCH_HANDOFF.md`](RESEARCH_HANDOFF.md) — навигационный handoff между методологией школы и научным проектом.
- [`ROADMAP.md`](ROADMAP.md) — текущая точка, NEXT и milestones исследовательского контура.
- [`OLGA_ARTICLE_PASSPORT.md`](OLGA_ARTICLE_PASSPORT.md) — паспорт статьи №1.
- [`DECISIONS.md`](DECISIONS.md) — журнал решений EAG; при внешней ссылке использовать префикс `EAG-D-`.
- [`School_Canon`](https://github.com/dimasez/School_Canon) — текущий живой канон школы.

## Статья №1

- [`ARTICLE1_MANUSCRIPT.md`](ARTICLE1_MANUSCRIPT.md) — текущий канонический manuscript v0.6; v0.7.1 ещё не канонизирован.
- [`ARTICLE1_THEORETICAL_REVIEW.md`](ARTICLE1_THEORETICAL_REVIEW.md) — ближайшие предшественники / research gap.
- [`ARTICLE1_REDTEAM_DELTA.md`](ARTICLE1_REDTEAM_DELTA.md) — история red-team решений.

## Coding / Corpus A

- [`ARTICLE1_CODING_MATRIX.md`](ARTICLE1_CODING_MATRIX.md) — frozen core v0.7.3.
- [`ARTICLE1_CODING_MANUAL.md`](ARTICLE1_CODING_MANUAL.md) — полный coding manual v0.7.3.
- [`ARTICLE1_CORPUS_A_REQUIREMENTS.md`](ARTICLE1_CORPUS_A_REQUIREMENTS.md) — frozen requirement map `Т / t⁰ / Т?`.
- [`ARTICLE1_CORPUS_A_PREDICTIONS.md`](ARTICLE1_CORPUS_A_PREDICTIONS.md) — dated internal pre-analysis registration до formal coding.
- [`ARTICLE1_CORPUS_A_PILOT_SIBERGY.md`](ARTICLE1_CORPUS_A_PILOT_SIBERGY.md) — development case Sibergy / Work A.
- [`ARTICLE1_FINANCIAL_ADAPTER_A.md`](ARTICLE1_FINANCIAL_ADAPTER_A.md) — optional prototype financial adapter; вне frozen CORE.

## Исторический методологический / исследовательский snapshot

- [`MASTER.md`](MASTER.md) — историческая модель школы v0.2 до School Canon; сохраняется как исследовательский снимок.
- [`DEFINITIONS.md`](DEFINITIONS.md) — датированные определения / различения исследовательского контура.
- [`ARTICLES.md`](ARTICLES.md) — архитектура публикаций.
- [`SOURCES.md`](SOURCES.md) — источники / внешняя верификация.
- `methodology/` — поздняя методология курса v0.1; источник для School Canon, но не текущий single source of truth школы.

`DRAFT.md` и `STRUCTURE.md` относятся к более раннему методологическому тексту «актив — благо — ценность» и не являются текущим manuscript статьи №1.

---

# Corpus A / B

### Corpus A

Шесть школьных работ одного курса. Sibergy / Work A использована как development case. Остальные пять после fixed SHA v0.7.3 — prospective internal pilot cases. Инструмент на них не меняется.

**Prior exposure:** автор курса ранее знаком с работами; некоторые артефакты предварительно просматривались / извлекались при подготовке корпуса. Поэтому Corpus A не является blind validation sample. Доказательная граница — **до стандартизированного coding по v0.7.3**, а не до первого знакомства с работами.

### Corpus B

Около 15 работ «Техностартапа». Held-out до решения о v0.8 / cross-domain freeze. Затем — независимые human coders и inter-rater reliability.

---

# CORE + adapters

> **CORE coding matrix** описывает структуру экономического моделирования в исследовательском дизайне статьи №1.  
> **Domain-specific adapters** проверяют конкретные дисциплинарные техники.

Financial adapter не определяет core и имеет статус prototype / optional / not validated.

---

# Научная заявка — текущий статус

Рабочий candidate contribution:

> **воспроизводимая процедура перехода от структуры экономического содержания к наблюдаемым следам когнитивных операций в целостной экономической модели учебного проекта.**

Целевой novelty level 2 **ещё не доказан**. Для него нужны различимые профили, independent coding, inter-rater agreement и prospective predictions на новом материале.

Предметно-специфический механизм `O_profile` остаётся исследовательской моделью EAG; School Canon может ссылаться на него как на `HYPOTHESIS / RESEARCH-DERIVED`, но не превращает его автоматически в канон.

---

# Протокол нескольких ИИ

`GitHub → независимый read-only анализ / red-team → решение автора → единая синхронизация GitHub`.

Пользователь — окончательное решение. ChatGPT — интегратор / контур записи. Claude и другие модели — независимые критики / readers.

Уточнение после создания School Canon:

- `School_Canon` — каноническая память живой архитектуры школы;
- `EconomyAssetsGoods` — каноническая память конкретного научного контура и его frozen history.

Ни один read-only критик не изменяет канон напрямую.