# SUNBOYS Platform Documentation

Документация проекта SUNBOYS: системы автопроверки решений студентов в формате Online Judge / Code Runner.

## Разделы

| Документ | Назначение |
| --- | --- |
| [Main Service](main-service.md) | Описание монолита для классрумов, задач и отправок решений, включая Mermaid-диаграммы и поток данных через RabbitMQ. |
| [Main Service OpenAPI](main-service.openapi.yaml) | OpenAPI 3.0 спецификация всех HTTP endpoint-ов Main Service. |
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
