# Jadlis Advisor — MAKE (Indie Maker)

Советник по созданию бутстрэпных интернет-продуктов на основе методологии MAKE (Pieter Levels).

## Что это

Claude Code skill, который превращает знания из книги "MAKE: The Indie Maker Blueprint" в процедурные навыки. Advisor проводит через 7 стадий: Idea → Build → Launch → Grow → Monetize → Automate → Exit.

## Что даёт Claude, чего у него нет

- Product Hunt: тайминг запуска (00:00:01 PST), формат thumbnails, скриншоты
- Hacker News: формула "Show HN:", порог 5 upvotes/час, фильтр controversy
- Reddit: подготовка статических страниц, выбор subreddit
- Пресса: 2-sentence email template с примерами хорошего и плохого
- Монетизация: community pricing ladder ($1→$50), fake checkout validation
- Подписки: формулы с конкретными числами (25% рост + 7% churn)
- Exit: 5 типов покупателей, breakup fee, valuation multiples, FIRE 4% rule
- Автоматизация: autonomous org checklist, bus test

## Индивидуализация

Advisor НЕ даёт абстрактных советов. Каждая рекомендация:
1. Называет продукт и аудиторию пользователя
2. Генерирует конкретный контент (заголовки, письма, ценовые тиры)
3. Рассчитывает числовые проекции на основе реальных данных пользователя
4. Выдаёт конкретные action items, не общие чеклисты
5. Явно называет антипаттерны, если подход пользователя совпадает

## Установка

```bash
claude --plugin-dir "/path/to/Jadlis-Advisor-Make"
```

## Использование

Skill активируется автоматически при запросах об инди-разработке, MVP, запуске продуктов, монетизации.

Ручной вызов: `/jadlis-advisor-make:indie-maker`

## Тестовые запросы

1. "Хочу создать продукт, но не знаю какой" → Idea stage
2. "У меня есть идея, как собрать MVP за неделю?" → Build stage
3. "Как запустить мой продукт на Product Hunt?" → Launch stage
4. "Трафик упал после запуска, что делать?" → Grow stage
5. "У меня 5000 пользователей но нет дохода" → Monetize stage
6. "Хочу меньше заниматься операционкой" → Automate stage
7. "Мне написали с предложением купить мой проект" → Exit stage

## Структура

```
Jadlis-Advisor-Make/
├── .claude-plugin/
│   └── plugin.json
├── skills/
│   └── indie-maker/
│       ├── SKILL.md
│       └── references/
│           ├── idea-validation.md
│           ├── build-fast.md
│           ├── launch-playbooks.md
│           ├── press-outreach.md
│           ├── organic-growth.md
│           ├── monetization-models.md
│           ├── automation-exit.md
│           └── examples.md
└── README.md
```

## Источник

MAKE: The Indie Maker Blueprint — Pieter Levels (@levelsio)

## Лицензия

Частный плагин. Знания извлечены и переработаны в процедурный формат.
