# SUNBOYS Platform Documentation

Документация проекта SUNBOYS: системы автопроверки решений студентов в формате Online Judge / Code Runner.

## Разделы

| Документ | Назначение |
| --- | --- |
| [SRE Architecture](sre-architecture.md) | Инфраструктурная спецификация, Kubernetes, очереди, мониторинг, логирование, безопасность запуска кода, CI/CD и SLO. |

## Локальный запуск

```powershell
pip install -r requirements.txt
mkdocs serve
```

## Проверка сборки

```powershell
mkdocs build --strict
```
