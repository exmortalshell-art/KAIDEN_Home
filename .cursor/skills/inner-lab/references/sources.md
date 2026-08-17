# Откуда что взято

Исследование под сборку Inner Lab (август 2026). Это не научный обзор на 80 страниц — карта, чтобы не тащить в репо токсичный зоопарк «AI therapist».

## GitHub / скиллы агентов — что смотрели

| Репозиторий | Что полезного | Что не тащим |
|-------------|---------------|--------------|
| [ironyjk/counsel-frameworks](https://github.com/ironyjk/counsel-frameworks) | Роутер 14 рамок, кризис первым, честный дисклеймер «это не терапия», CBT/ACT/MI/SFBT/DBT skills | IFS и Gottman как полноценные протоколы ИИ; 14 рамок сразу (перегруз); корейский слой не нужен |
| [glebis/claude-cognitive-toolkit](https://github.com/glebis/claude-cognitive-toolkit) | Thought record по Беку/Бёрнсу, opposite action, локальные markdown-файлы, «не терапевт» | HRV/геном как якобы контекст настроения (спекулятивно); копирование их skill.md |
| [arktnld/cbt-llm-kit](https://github.com/arktnld/cbt-llm-kit) | Пошаговая запись мысли, локальные records, анализ паттернов, работа в Cursor | 12 шагов слишком длинно для каждого захода; JSON-обвязка не нужна |
| OpenClaw / TheSethRose **therapy-mode** (каталоги skills) | CBT+ACT+DBT+MI в одном скилле, кризис | Поза «comprehensive therapist»; CLI notes чужого стека |
| [Wrendered/journaling-with-claude](https://github.com/Wrendered/journaling-with-claude) | Журнал + ритуалы дня, ценности | Enneagram/MBTI в assessments — сознательно выкинули |
| [KatherineGuoGuo/bigfive-open](https://github.com/Katherine-guoguoboss/bigfive-open), [Alheimsins/b5-50-ipip-neo-pi-r](https://github.com/Alheimsins/b5-50-ipip-neo-pi-r), IPIP | Публичный Big Five | Тяжёлые 120/300 пунктов в чат без запроса |
| Awesome-списки Cursor/Claude skills | Почти нет качественных psy-скиллов; много инженерии | Не раздувать репо чужими нерелевантными skills |

Чужие `SKILL.md` **не копировались**. Каркас, границы и тексты — свои, под KAIDEN_Home (русский, один вопрос, файлы в `psy/`, тон прямого консультанта).

## Тексты и модели (ориентиры)

- Beck, J. S. — CBT basics (треугольник, запись мысли, эксперимент).
- Burns — популярная практика искажений; используем список явлений, не копируем бланки.
- Hayes — ACT (гибкость, ценности, defusion).
- Linehan — DBT *skills training* (навыки, не обещание терапии).
- Miller & Rollnick — MI.
- de Shazer & Berg — SFBT (шкалы, исключения) точечно.
- Segal, Williams, Teasdale — MBCT (децентация).
- Kabat-Zinn — MBSR как внимание, не бренд просветления.
- Donnellan et al. (2006) Mini-IPIP; Goldberg IPIP public domain; ключ https://ipip.ori.org/MiniIPIPKey.htm
- Kroenke / Spitzer / Williams — PHQ-2, GAD-2 (скрининг).
- Oettingen — WOOP; Gollwitzer — implementation intentions.
- Neff — self-compassion как *точность*, с оговоркой на силу данных.
- NICE/APA как ориентир «что вообще первая линия при тревоге/депрессии в живой клинике» — ИИ это не воспроизводит, только не противоречит.

## Почему не «поставь все 14 терапий»

Wampold: вклад конкретной школы меньше, чем думает маркетинг; в чате без человека-терапевта вклад «альянса» ещё слабее. Лучше **мало методов, жёсткие границы, измеримое действие**, чем карнавал IFS+нарратив+горе+пары за один вечер.
