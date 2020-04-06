# Extas

`Extas` представляет собой набор библиотек и микросервисов, которые организуют платформу для разработки web-приложений различного уровня.

Подписывайтесь на новости в Telegram: [@extas-awesome](https://t.me/extasplatform "Extas").

## Базовые пакеты

- [extas-foundation](https://github.com/jeyroik/extas-foundation "Базовый пакет")
  - `ru` Базовые сущности платформы.
  - `en` Basic entities.
- [extas-base](https://github.com/jeyroik/extas-base "Набор общий интерфейсов и их реализаций")
  - `ru` Базовые интерфейсы и их реализации (на базе трейтов).
  - `en` Basic interfaces and traits with it's implementations.
- [extas-installer](https://github.com/jeyroik/extas-installer "Установка extas-совместимых сущностей")
  - `ru` пакет для установки extas-совместимых сущностей
  - `en` allow to install extas-compatable-entities.

## Прочие пакеты

- [extas-access](https://github.com/jeyroik/extas-access "RBAC доступ с чистой реализацией правила Всё, что не разрешено - запрещено")
  - `ru` Реализация RBAC доступа с чистым воплощением правила "Всё, что не разрешено - запрещено".
  - `en` RBAC with pure implementation of the rule "All that is not allowed is restricted".
- [extas-alice](https://github.com/jeyroik/extas-alice "Библиотека для создания навыков для Алисы Яндекса")
  - `ru` Библиотека для создания навыков для Алисы Яндекса.
  - `en` Library for the Yandex Alice skills development.
- [extas-alice-example](https://github.com/jeyroik/extas-alice-example "Пример использования библиотеки для создания навыков для Алисы Яндекса")
  - `ru` Пример использования библиотеки `extas-alice`.
  - `en` Example of `extas-alice` usage.
- [extas-bv](https://github.com/jeyroik/extas-bv "Бизнес ценность задач")
  - `ru` Библиотека для расчёта бизнес ценности задач.
  - `en` Tasks business value calculating library.
- [extas-bv-profiles](https://github.com/jeyroik/extas-bv-profiles "Профили для бизнес ценности задач")
  - `ru` Расширение для пакета `extas-bv`, позволяющее создавать "профили", т.е. наборы весов для БЦ.
  - `en` `extas-bv` extension for weight profiles constructing.
- [extas-bv-api](https://github.com/jeyroik/extas-bv-api "Микросервис для бизнес ценности задач")
  - `ru` Микросервис для работы с БЦ задач.
  - `en` Microservice for working with issues BV.
- [extas-conditions](https://github.com/jeyroik/extas-conditions "Механизм условий и ограничений")
  - `ru` Механизм условий и ограничений.
  - `en` Conditions and restrictions engine.
- [extas-envs](https://github.com/jeyroik/extas-envs "Переменные окружения")
  - `ru` Пакет для работы с переменными окружения и генерации `.env.dist` файла
  - `en` Allow to install environment parameters and to generate `.env.dist`.
- [extas-event-provider](https://github.com/jeyroik/extas-event-provider "Провайдер для league/event")
  - `ru` Провайдер событий для [league/event](https://github.com/thephpleague/event), позволяющий использовать extas-стадии и плагины в качестве событий и слушателей
  - `en` Event provider for the [league/event](https://github.com/thephpleague/event), allows to use extas stages (and plugins) as events (and listeners).
- [extas-expands](https://github.com/jeyroik/extas-expands "Самораспаковывающиеся API")
  - `ru` Позволяет реализовывать самораспаковывающиеся API (например, как у Jira).
  - `en` Allow to provide self-extracting API (ex. Jira).
- [extas-jsonrpc](https://github.com/jeyroik/extas-jsonrpc "Сервер JSON RPC")
  - `ru` JSON RPC сервер, пакет позволяет создавать спецификации API на основе плагинов установки сущностей
  - `en` JSON RPC server, allow to generate specs upon to `PluginInstall` classes (see `extas-installer`).
- [extas-m](https://github.com/jeyroik/extas-m "Машина состояний")
  - `ru` Машина состояний
  - `en` State machine
- [extas-players](https://github.com/jeyroik/extas-players "Управление пользователями")
  - `ru` Пакет для работы с пользователями
  - `en` User extas package.
- [extas-repositories-mongo](https://github.com/jeyroik/extas-repositories-mongo "Реопзиторий для работы с MongoDB")
  - `ru` Extas-совместимый репозиторий MongoDB
  - `en` MongoDB extas-compatable repository.
- [extas-repositories-uuid-field](https://github.com/jeyroik/extas-repositories-uuid-fields "Uuid для полей сущности")
  - `ru` Пакет позволяет автоматически генерировать uuid-строки для полей при создании сущности.
  - `en` Package allow to generate uuid strings for an item fields on creating.
- [extas-workflow](https://github.com/jeyroik/extas-workflow "Workflow")
  - `ru` Workflow с поддержкой нескольких схем, ограничений и триггеров.
  - `en` Worklfow with multiple schemas, restrictions and triggers supply.
- [extas-workflow-dashboard](https://github.com/jeyroik/extas-workflow-dashboard "Микросервис Workflow")
  - `ru` API для работы с Workflow
  - `en` Workflow JSON RPC api, based on `extas-worklfow`.
- [extas-workflow-dispatchers](https://github.com/jeyroik/extas-workflow-dispatchers "Обработчики переходов для Workflow")
  - `ru` Обработчики переходов для Workflow.
  - `en` Transitions dispatchers for Workflow.
- [extas-workflow-dashboard-svelte](https://github.com/jeyroik/extas-workflow-dashboard-svelte "Борд для управления Workflow")
  - `ru` Svelte клиент для API для работы с Workflow
  - `en` Svelte client for Workflow API, based on `extas-worklfow-dashboard`.
- [extas-workflow-example](https://github.com/jeyroik/extas-workflow-example "Пример использования библиотеки Workflow")
  - `ru` Пример использования пакета workflow
  - `en` Example project, shows the workflow usage.
