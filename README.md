# GitPolicy

Универсальные рабочие файлы git-политики для AI-агентов.

## Состав

- `AGENTS.md` — единая политика: обязательства агента по commit/push, формат commit message и pre-push правило.

## Использование из любого репозитория

Скачать готовый файл и положить в корень целевого репозитория:

```bash
curl -fsSL https://raw.githubusercontent.com/th3-cl4ss1c/GitPolicy/main/AGENTS.md -o AGENTS.md
```

## Что обычно правят под проект

- в `AGENTS.md` строку с pre-push проверкой;
- в `AGENTS.md` список файлов/директорий для критерия "значимое изменение".
