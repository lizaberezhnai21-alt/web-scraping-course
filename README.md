# Веб-скрейпінг: збір, обробка та аналіз даних

Навчальний онлайн-курс для учнів 10–11 класів (рівень стандарту).

## Перегляд локально

Потрібен Python 3.10 або новіший.

```bash
python -m venv .venv
# Windows:
.venv\Scripts\activate
# macOS / Linux:
source .venv/bin/activate

pip install -r requirements.txt
mkdocs serve
```

Відкрийте адресу, яку покаже команда (зазвичай http://127.0.0.1:8000).

## Публікація на GitHub Pages

1. Створіть репозиторій `web-scraping-course` на GitHub.
2. Завантажте в нього всі файли цього проєкту.
3. Відкрийте **Settings → Pages**.
4. У полі **Build and deployment → Source** оберіть **GitHub Actions**.
5. Дочекайтеся завершення workflow `Deploy documentation`.
6. Адреса сайту матиме вигляд `https://USERNAME.github.io/web-scraping-course/`.

## Важливо перед публікацією

- У `mkdocs.yml` за потреби додайте `site_url` та `repo_url`.
- Перевірте авторство, посилання, ліцензії зображень і навчальних даних.
- Не збирайте персональні, закриті або захищені дані.
- Дотримуйтеся умов використання сайтів та правил доступу до їхніх сторінок.

## Структура

- `docs/` — матеріали сайту;
- `docs/modules/` — навчальні модулі;
- `docs/practical/` — практичні роботи та файли;
- `docs/quizzes/` — тести;
- `docs/playground/` — браузерна Python-пісочниця на Pyodide;
- `.github/workflows/` — автоматичне розгортання.
