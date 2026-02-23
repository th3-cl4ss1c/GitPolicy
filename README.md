# GitPolicy

Универсальные рабочие файлы git-политики для AI-агентов.

## Состав

- `AGENTS.md` — обязательства агента по commit/push.
- `CONTRIBUTING.md` — формат commit message и pre-push правило.

## Использование из любого репозитория

Скачать готовые файлы и положить в корень целевого репозитория:

```bash
curl -fsSL https://raw.githubusercontent.com/<OWNER>/<REPO>/main/AGENTS.md -o AGENTS.md
curl -fsSL https://raw.githubusercontent.com/<OWNER>/<REPO>/main/CONTRIBUTING.md -o CONTRIBUTING.md
```

## Что обычно правят под проект

- в `CONTRIBUTING.md` строку с pre-push проверкой;
- в `AGENTS.md` список файлов/директорий для критерия "значимое изменение".
