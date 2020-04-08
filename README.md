# Extas

`Extas` представляет собой набор библиотек и микросервисов, которые организуют платформу для разработки web-приложений различного уровня.

Подписывайтесь на новости в Telegram: [@extasplatform](https://t.me/extasplatform "Extas").

## Базовые пакеты

- [extas-foundation](https://github.com/jeyroik/extas-foundation "Базовый пакет") ![codecov.io](https://codecov.io/gh/jeyroik/extas-foundation/coverage.svg?branch=master)
  - `ru` Базовые сущности платформы.
  - `en` Basic entities.
- [extas-base](https://github.com/jeyroik/extas-base "Набор общий интерфейсов и их реализаций") ![codecov.io](https://codecov.io/gh/jeyroik/extas-base/coverage.svg?branch=master)
  - `ru` Базовые интерфейсы и их реализации (на базе трейтов).
  - `en` Basic interfaces and traits with it's implementations.
- [extas-installer](https://github.com/jeyroik/extas-installer "Установка extas-совместимых сущностей") ![codecov.io](https://codecov.io/gh/jeyroik/extas-installer/coverage.svg?branch=master)
  - `ru` пакет для установки extas-совместимых сущностей
  - `en` allow to install extas-compatable-entities.

## Прочие пакеты

- [extas-access](https://github.com/jeyroik/extas-access "RBAC доступ с чистой реализацией правила Всё, что не разрешено - запрещено") ![codecov.io](https://codecov.io/gh/jeyroik/extas-access/coverage.svg?branch=master)
  - `ru` Реализация RBAC доступа с чистым воплощением правила "Всё, что не разрешено - запрещено".
  - `en` RBAC with pure implementation of the rule "All that is not allowed is restricted".
- [extas-alice](https://github.com/jeyroik/extas-alice "Библиотека для создания навыков для Алисы Яндекса") ![codecov.io](https://codecov.io/gh/jeyroik/extas-alice/coverage.svg?branch=master)
  - `ru` Библиотека для создания навыков для Алисы Яндекса.
  - `en` Library for the Yandex Alice skills development.
- [extas-alice-example](https://github.com/jeyroik/extas-alice-example "Пример использования библиотеки для создания навыков для Алисы Яндекса") ![codecov.io](https://codecov.io/gh/jeyroik/extas-alice-example/coverage.svg?branch=master)
  - `ru` Пример использования библиотеки `extas-alice`.
  - `en` Example of `extas-alice` usage.
- [extas-bv](https://github.com/jeyroik/extas-bv "Бизнес ценность задач") ![codecov.io](https://codecov.io/gh/jeyroik/extas-bv/coverage.svg?branch=master)
  - `ru` Библиотека для расчёта бизнес ценности задач.
  - `en` Tasks business value calculating library.
- [extas-bv-profiles](https://github.com/jeyroik/extas-bv-profiles "Профили для бизнес ценности задач") ![codecov.io](https://codecov.io/gh/jeyroik/extas-bv-profiles/coverage.svg?branch=master)
  - `ru` Расширение для пакета `extas-bv`, позволяющее создавать "профили", т.е. наборы весов для БЦ.
  - `en` `extas-bv` extension for weight profiles constructing.
- [extas-bv-api](https://github.com/jeyroik/extas-bv-api "Микросервис для бизнес ценности задач") ![codecov.io](https://codecov.io/gh/jeyroik/extas-bv-api/coverage.svg?branch=master)
  - `ru` Микросервис для работы с БЦ задач.
  - `en` Microservice for working with issues BV.
- [extas-conditions](https://github.com/jeyroik/extas-conditions "Механизм условий и ограничений") ![codecov.io](https://codecov.io/gh/jeyroik/extas-conditions/coverage.svg?branch=master)
  - `ru` Механизм условий и ограничений.
  - `en` Conditions and restrictions engine.
- [extas-envs](https://github.com/jeyroik/extas-envs "Переменные окружения") ![codecov.io](https://codecov.io/gh/jeyroik/extas-envs/coverage.svg?branch=master)
  - `ru` Пакет для работы с переменными окружения и генерации `.env.dist` файла
  - `en` Allow to install environment parameters and to generate `.env.dist`.
- [extas-event-provider](https://github.com/jeyroik/extas-event-provider "Провайдер для league/event") ![codecov.io](https://codecov.io/gh/jeyroik/extas-event-provider/coverage.svg?branch=master)
  - `ru` Провайдер событий для [league/event](https://github.com/thephpleague/event), позволяющий использовать extas-стадии и плагины в качестве событий и слушателей
  - `en` Event provider for the [league/event](https://github.com/thephpleague/event), allows to use extas stages (and plugins) as events (and listeners).
- [extas-expands](https://github.com/jeyroik/extas-expands "Самораспаковывающиеся API") ![codecov.io](https://codecov.io/gh/jeyroik/extas-expands/coverage.svg?branch=master)
  - `ru` Позволяет реализовывать самораспаковывающиеся API (например, как у Jira).
  - `en` Allow to provide self-extracting API (ex. Jira).
- [extas-jsonrpc](https://github.com/jeyroik/extas-jsonrpc "Сервер JSON RPC") ![codecov.io](https://codecov.io/gh/jeyroik/extas-jsonrpc/coverage.svg?branch=master)
  - `ru` JSON RPC сервер, пакет позволяет создавать спецификации API на основе плагинов установки сущностей
  - `en` JSON RPC server, allow to generate specs upon to `PluginInstall` classes (see `extas-installer`).
- [extas-m](https://github.com/jeyroik/extas-m "Машина состояний") ![codecov.io](https://codecov.io/gh/jeyroik/extas-m/coverage.svg?branch=master)
  - `ru` Машина состояний
  - `en` State machine
- [extas-players](https://github.com/jeyroik/extas-players "Управление пользователями") ![codecov.io](https://codecov.io/gh/jeyroik/extas-players/coverage.svg?branch=master)
  - `ru` Пакет для работы с пользователями
  - `en` User extas package.
- [extas-repositories-mongo](https://github.com/jeyroik/extas-repositories-mongo "Реопзиторий для работы с MongoDB") ![codecov.io](https://codecov.io/gh/jeyroik/extas-repositories-mongo/coverage.svg?branch=master)
  - `ru` Extas-совместимый репозиторий MongoDB
  - `en` MongoDB extas-compatable repository.
- [extas-repositories-uuid-fields](https://github.com/jeyroik/extas-repositories-uuid-fields "Uuid для полей сущности") ![codecov.io](https://codecov.io/gh/jeyroik/extas-repositories-uuid-fields/coverage.svg?branch=master)
  - `ru` Пакет позволяет автоматически генерировать uuid-строки для полей при создании сущности.
  - `en` Package allow to generate uuid strings for an item fields on creating.
- [extas-workflow](https://github.com/jeyroik/extas-workflow "Workflow") ![codecov.io](https://codecov.io/gh/jeyroik/extas-workflow/coverage.svg?branch=master)
  - `ru` Workflow с поддержкой нескольких схем, ограничений и триггеров.
  - `en` Worklfow with multiple schemas, restrictions and triggers supply.
- [extas-workflow-dashboard](https://github.com/jeyroik/extas-workflow-dashboard "Микросервис Workflow") ![codecov.io](https://codecov.io/gh/jeyroik/extas-workflow-dashboard/coverage.svg?branch=master)
  - `ru` API для работы с Workflow
  - `en` Workflow JSON RPC api, based on `extas-worklfow`.
- [extas-workflow-dispatchers](https://github.com/jeyroik/extas-workflow-dispatchers "Обработчики переходов для Workflow") ![codecov.io](https://codecov.io/gh/jeyroik/extas-workflow-dispatchers/coverage.svg?branch=master)
  - `ru` Обработчики переходов для Workflow.
  - `en` Transitions dispatchers for Workflow.
- [extas-workflow-dashboard-svelte](https://github.com/jeyroik/extas-workflow-dashboard-svelte "Борд для управления Workflow") ![codecov.io](https://codecov.io/gh/jeyroik/extas-workflow-dashboard-svelte/coverage.svg?branch=master)
  - `ru` Svelte клиент для API для работы с Workflow
  - `en` Svelte client for Workflow API, based on `extas-worklfow-dashboard`.
- [extas-workflow-example](https://github.com/jeyroik/extas-workflow-example "Пример использования библиотеки Workflow") ![codecov.io](https://codecov.io/gh/jeyroik/extas-workflow-example/coverage.svg?branch=master)
  - `ru` Пример использования пакета workflow
  - `en` Example project, shows the workflow usage.
