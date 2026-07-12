# Андрей Скворцов — автоматизация и интеграции

Собираю прикладные инструменты на Python, API, Google Sheets, Apps Script и AI-сервисах.

Мой фокус — не код ради кода, а решения, которые сокращают ручную работу: поиск и обработка данных, внутренние интерфейсы, CRM-прототипы, уведомления и автоматизация повторяющихся процессов.

![Python](https://img.shields.io/badge/Python-Automation-3776AB)
![API](https://img.shields.io/badge/API-Integrations-6f42c1)
![AI](https://img.shields.io/badge/AI-Tools-blue)
![Google Apps Script](https://img.shields.io/badge/Google-Apps%20Script-34A853)

## Основные проекты

### [DocuFind Local](https://github.com/CheMpoKaRoKee/DocuFind)

Windows-приложение для локального индексирования и поиска по файлам без отправки данных во внешние сервисы.

Что показывает проект:

- Python-приложение с desktop-интерфейсом на PySide6;
- SQLite и FTS5 для полнотекстового поиска;
- поиск по имени, пути и содержимому файлов;
- русскую морфологию через `pymorphy3`;
- fuzzy-поиск по опечаткам через RapidFuzz;
- фоновые задачи для индексации и поиска;
- безопасное редактирование с backup и atomic save;
- unit/integration tests и сборку Windows `.exe` через PyInstaller.

**Стек:** Python, PySide6, SQLite, FTS5, RapidFuzz, pymorphy3, PyInstaller.

---

### [MiniCRM](https://github.com/CheMpoKaRoKee/MiniCRM)

Тестовое задание: рабочий прототип мини-CRM для юридической команды.

Что реализовано:

- Web App для добавления и ведения клиентов;
- Google Sheets как база данных;
- статусы, комментарии и счётчики;
- журнал действий;
- email-уведомления;
- backend-логика на Google Apps Script;
- простой интерфейс на HTML, CSS и JavaScript.

Проект показывает, как быстро собрать MVP внутреннего инструмента без отдельного сервера и сложной инфраструктуры.

**Стек:** Google Sheets, Google Apps Script, HTML, CSS, JavaScript.

---

### [Learning Mentor](https://github.com/CheMpoKaRoKee/Mentor)

Desktop-приложение для самостоятельного изучения разработки с AI-наставником.

Что показывает проект:

- интеграцию с OpenRouter API;
- AI-генерацию теории и заданий;
- проверку ответов и контекстный чат;
- desktop-приложение на Electron и React;
- локальное сохранение прогресса и настроек;
- portable-сборку для Windows.

**Стек:** Electron, React, Vite, Tailwind CSS, OpenRouter API, electron-builder.

## Чем могу быть полезен

- автоматизация повторяющихся рабочих процессов;
- интеграции через REST API и webhooks;
- внутренние инструменты на Python;
- прототипы на Google Sheets и Apps Script;
- AI-помощники для обучения, анализа и операционных задач;
- оформление MVP: документация, тесты, сборка и инструкции по запуску.

## Стек и инструменты

**Python / Data:** Python, SQLite, SQL, FTS5, PySide6  
**Integrations:** REST API, Webhooks, Postman  
**Automation:** Google Sheets, Google Apps Script, NocoDB  
**AI:** OpenRouter API, LLM, prompt engineering  
**Desktop / Frontend:** Electron, React, Vite, HTML, CSS, JavaScript  
**Dev tools:** Git, GitHub, Linux, PyInstaller

## Бэкграунд

До разработки я работал в клиентском сервисе, поддержке, маркетинге и координации проектов. Этот опыт помогает мне смотреть на автоматизацию как на улучшение реального процесса: понять, где теряются данные и время, собрать простой рабочий сценарий и сделать его понятным пользователю.

## Контакты

GitHub: [`CheMpoKaRoKee`](https://github.com/CheMpoKaRoKee)  
Email: `alister.173@gmail.com`
