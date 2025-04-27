# Генплан Броварів

Сайт для громадського обговорення Генерального плану міста Бровари.

## Структура проекту

- `index.md` - головна сторінка
- `_pages/` - директорія зі сторінками сайту:
  - `proekt-henplanu-2015.md` - проект генплану 2015 року
  - `diiuchyi-henplan-1999.md` - діючий генплан 1999 року
  - `stari-karty-brovariv.md` - старі карти Броварів
  - `rishennia-ta-dokumenty.md` - рішення та документи
  - `zapytannia-po-henplanu.md` - запитання по генплану
  - `propozytsii-vid-hromadskosti.md` - пропозиції від громадськості
  - `pro-nas.md` - інформація про проект
- `_includes/` - шаблони для включення в сторінки
- `_layouts/` - шаблони сторінок
- `assets/` - статичні файли (CSS, JavaScript, зображення)

## Встановлення

1. Клонуйте репозиторій:
```bash
git clone https://github.com/sergilliukhin/genplan.brovary.org.git
```

2. Встановіть Ruby (якщо ще не встановлено):
```bash
# Для macOS (через Homebrew)
brew install ruby

# Для Ubuntu/Debian
sudo apt-get install ruby-full
```

3. Встановіть залежності:
```bash
bundle install
```

4. Запустіть проект локально:
```bash
bundle exec jekyll serve
```

Сайт буде доступний за адресою `http://localhost:4000`

## Розробка

Проект розроблено з використанням:
- Markdown для контенту
- Jekyll для генерації статичного сайту
- GitHub Pages для хостингу

## Ліцензія

MIT 