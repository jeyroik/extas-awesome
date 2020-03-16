# Extas

`Extas` представляет собой набор библиотек и микросервисов, которые организуют платформу для разработки web-приложений различного уровня.

## Базовые пакеты

- `extas-foundation`
  - `ru`: Базовые сущности платформы.
  - `en`: Basic entities.
- `extas-base`
  - `ru`: Базовые интерфейсы и их реализации (на базе трейтов).
  - `en`: Basic interfaces and traits with it's implementations.
- `extas-installer`
  - `ru`: пакет для установки extas-совместимых сущностей
  - `en`: allow to install extas-compatable-entities.

## Прочие пакеты

- `extas-access`
  - `ru`: Реализация RBAC доступа с чистым воплощением правила "Всё, что не разрешено - запрещено".
  - `en`: RBAC with pure implementation of the rule "All that is not allowed is restricted".
- `extas-bv`
  - `ru`: Библиотека для расчёта эффективности команды разработки.
  - `en`: Development efficiency calculating library.
- `extas-bv-profiles`
  - `ru`: Расширение для пакета `extas-bv`, позволяющее работать с профиля разработчиков.
  - `en`: `extas-bv` extension for working with developers profiles.
- `extas-bv-api`
  - `ru`: Микросервис для расчёта эффективности команды разработки.
  - `en`: Microservice for development efficiency calculating.
- `extas-conditions`
  - `ru`: Механизм условий и ограничений.
  - `en`: Conditions and restrictions engine.
- `extas-envs`
  - `ru`: пакет для работы с переменными окружения и генерации `.env.dist` файла
  - `en`: allow to install environment parameters and to generate `.env.dist`.
- `extas-event-provider`
  - `ru`: Провайдер событий для [league/event](https://github.com/thephpleague/event), позволяющий использовать extas-стадии и плагины в качестве событий и слушателей
  - `en`: Event provider for the [league/event](https://github.com/thephpleague/event), allows to use extas stages (and plugins) as events (and listeners).
- `extas-expands`
  - `ru`: Позволяет реализовывать самораспаковывающиеся API (например, как у Jira).
  - `en`: Allow to provide self-extracting API (ex. Jira).
- `extas-jsonrpc`
  - `ru`: JSON RPC сервер, пакет позволяет создавать спецификации API на основе плагинов установки сущностей
  - `en`: JSON RPC server, allow to generate specs upon to `PluginInstall` classes (see `extas-installer`).
- `extas-m`
  - `ru`: Машина состояний
  - `en`: State machine
- `extas-players`
  - `ru`: Пакет для работы с пользователями
  - `en`: User extas package.
- `extas-repositories-mongo`
  - `ru`: Extas-совместимый репозиторий MongoDB
  - `en`: MongoDB extas-compatable repository.
- `extas-workflow`
  - `ru`: Workflow с поддержкой нескольких схем, ограничений и триггеров.
  - `en`: Worklfow with multiple schemas, restrictions and triggers supply.
- `extas-workflow-dashboard`
  - `ru`: API для работы с Workflow
  - `en`: Workflow JSON RPC api, based on `extas-worklfow`.
- `extas-workflow-example`
  - `ru`: Пример использования пакета workflow
  - `en`: Example project, shows the workflow usage.
