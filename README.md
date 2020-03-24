# Extas

`Extas` представляет собой набор библиотек и микросервисов, которые организуют платформу для разработки web-приложений различного уровня.

## Базовые пакеты

- [extas-foundation](https://github.com/jeyroik/extas-foundation)
  - `ru` Базовые сущности платформы.
  - `en` Basic entities.
- [extas-base](https://github.com/jeyroik/extas-base)
  - `ru` Базовые интерфейсы и их реализации (на базе трейтов).
  - `en` Basic interfaces and traits with it's implementations.
- [extas-installer](https://github.com/jeyroik/extas-installer)
  - `ru` пакет для установки extas-совместимых сущностей
  - `en` allow to install extas-compatable-entities.

## Прочие пакеты

- [extas-access](https://github.com/jeyroik/extas-access)
  - `ru` Реализация RBAC доступа с чистым воплощением правила "Всё, что не разрешено - запрещено".
  - `en` RBAC with pure implementation of the rule "All that is not allowed is restricted".
- [extas-alice](https://github.com/jeyroik/extas-alice)
  - `ru` Библиотека для создания навыков для Алисы Яндекса.
  - `en` Library for the Yandex Alice skills development.
- [extas-alice-example](https://github.com/jeyroik/extas-alice-example)
  - `ru` Пример использования библиотеки `extas-alice`.
  - `en` Example of `extas-alice` usage.
- [extas-bv](https://github.com/jeyroik/extas-bv)
  - `ru` Библиотека для расчёта бизнес ценности задач.
  - `en` Tasks business value calculating library.
- [extas-bv-profiles](https://github.com/jeyroik/extas-bv-profiles)
  - `ru` Расширение для пакета `extas-bv`, позволяющее создавать "профили", т.е. наборы весов для БЦ.
  - `en` `extas-bv` extension for weight profiles constructing.
- [extas-bv-api](https://github.com/jeyroik/extas-bv-api)
  - `ru` Микросервис для работы с БЦ задач.
  - `en` Microservice for working with issues BV.
- [extas-conditions](https://github.com/jeyroik/extas-conditions)
  - `ru` Механизм условий и ограничений.
  - `en` Conditions and restrictions engine.
- [extas-envs](https://github.com/jeyroik/extas-envs)
  - `ru` пакет для работы с переменными окружения и генерации `.env.dist` файла
  - `en` allow to install environment parameters and to generate `.env.dist`.
- [extas-event-provider](https://github.com/jeyroik/extas-event-provider)
  - `ru` Провайдер событий для [league/event](https://github.com/thephpleague/event), позволяющий использовать extas-стадии и плагины в качестве событий и слушателей
  - `en` Event provider for the [league/event](https://github.com/thephpleague/event), allows to use extas stages (and plugins) as events (and listeners).
- [extas-expands](https://github.com/jeyroik/extas-expands)
  - `ru` Позволяет реализовывать самораспаковывающиеся API (например, как у Jira).
  - `en` Allow to provide self-extracting API (ex. Jira).
- [extas-jsonrpc](https://github.com/jeyroik/extas-jsonrpc)
  - `ru` JSON RPC сервер, пакет позволяет создавать спецификации API на основе плагинов установки сущностей
  - `en` JSON RPC server, allow to generate specs upon to `PluginInstall` classes (see `extas-installer`).
- [extas-m](https://github.com/jeyroik/extas-m)
  - `ru` Машина состояний
  - `en` State machine
- [extas-players](https://github.com/jeyroik/extas-players)
  - `ru` Пакет для работы с пользователями
  - `en` User extas package.
- [extas-repositories-mongo](https://github.com/jeyroik/extas-repositories-mongo)
  - `ru` Extas-совместимый репозиторий MongoDB
  - `en` MongoDB extas-compatable repository.
- [extas-repositories-uuid-field](https://github.com/jeyroik/extas-repositories-uuid-fields "Uuid in fields")
  - `ru` Пакет позволяет автоматически генерировать uuid-строки для полей при создании сущности.
  - `en` Package allow to generate uuid strings for an item fields on creating.
- [extas-workflow](https://github.com/jeyroik/extas-workflow)
  - `ru` Workflow с поддержкой нескольких схем, ограничений и триггеров.
  - `en` Worklfow with multiple schemas, restrictions and triggers supply.
- [extas-workflow-dashboard](https://github.com/jeyroik/extas-workflow-dashboard)
  - `ru` API для работы с Workflow
  - `en` Workflow JSON RPC api, based on `extas-worklfow`.
- [extas-workflow-dashboard-svelte](https://github.com/jeyroik/extas-workflow-dashboard-svelte)
  - `ru` Svelte клиент для API для работы с Workflow
  - `en` Svelte client for Workflow API, based on `extas-worklfow-dashboard`.
- [extas-workflow-example](https://github.com/jeyroik/extas-workflow-example)
  - `ru` Пример использования пакета workflow
  - `en` Example project, shows the workflow usage.
