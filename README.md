# Extas

`Extas` представляет собой набор библиотек и микросервисов, которые организуют платформу для разработки web-приложений различного уровня.

Подписывайтесь на новости в Telegram: [@extasplatform](https://t.me/extasplatform "Extas").

## Базовые пакеты

- [extas-foundation](https://github.com/jeyroik/extas-foundation "Базовый пакет") 
  - `ru` Базовые сущности платформы.
  - `en` Basic entities.
  - `tests` ![codecov.io](https://codecov.io/gh/jeyroik/extas-foundation/coverage.svg?branch=master)
- [extas-base](https://github.com/jeyroik/extas-base "Набор общий интерфейсов и их реализаций") 
  - `ru` Базовые интерфейсы и их реализации (на базе трейтов).
  - `en` Basic interfaces and traits with it's implementations.
  - `tests` ![codecov.io](https://codecov.io/gh/jeyroik/extas-base/coverage.svg?branch=master)
- [extas-installer](https://github.com/jeyroik/extas-installer "Установка extas-совместимых сущностей") 
  - `ru` пакет для установки extas-совместимых сущностей
  - `en` allow to install extas-compatable-entities.
  - `tests` ![codecov.io](https://codecov.io/gh/jeyroik/extas-installer/coverage.svg?branch=master)

## Прочие пакеты

- [extas-access](https://github.com/jeyroik/extas-access "RBAC доступ с чистой реализацией правила Всё, что не разрешено - запрещено") 
  - `ru` Реализация RBAC доступа с чистым воплощением правила "Всё, что не разрешено - запрещено".
  - `en` RBAC with pure implementation of the rule "All that is not allowed is restricted".
  - `tests` ![codecov.io](https://codecov.io/gh/jeyroik/extas-access/coverage.svg?branch=master)
- [extas-alice](https://github.com/jeyroik/extas-alice "Библиотека для создания навыков для Алисы Яндекса") 
  - `ru` Библиотека для создания навыков для Алисы Яндекса.
  - `en` Library for the Yandex Alice skills development.
  - `tests` ![codecov.io](https://codecov.io/gh/jeyroik/extas-alice/coverage.svg?branch=master)
- [extas-alice-example](https://github.com/jeyroik/extas-alice-example "Пример использования библиотеки для создания навыков для Алисы Яндекса") 
  - `ru` Пример использования библиотеки `extas-alice`.
  - `en` Example of `extas-alice` usage.
  - `tests` ![codecov.io](https://codecov.io/gh/jeyroik/extas-alice-example/coverage.svg?branch=master)
- [extas-bv](https://github.com/jeyroik/extas-bv "Бизнес ценность задач") 
  - `ru` Библиотека для расчёта бизнес ценности задач.
  - `en` Tasks business value calculating library.
  - `tests` ![codecov.io](https://codecov.io/gh/jeyroik/extas-bv/coverage.svg?branch=master)
- [extas-bv-profiles](https://github.com/jeyroik/extas-bv-profiles "Профили для бизнес ценности задач") 
  - `ru` Расширение для пакета `extas-bv`, позволяющее создавать "профили", т.е. наборы весов для БЦ.
  - `en` `extas-bv` extension for weight profiles constructing.
  - `tests` ![codecov.io](https://codecov.io/gh/jeyroik/extas-bv-profiles/coverage.svg?branch=master)
- [extas-bv-api](https://github.com/jeyroik/extas-bv-api "Микросервис для бизнес ценности задач") 
  - `ru` Микросервис для работы с БЦ задач.
  - `en` Microservice for working with issues BV.
  - `tests` ![codecov.io](https://codecov.io/gh/jeyroik/extas-bv-api/coverage.svg?branch=master)
- [extas-conditions](https://github.com/jeyroik/extas-conditions "Механизм условий и ограничений") 
  - `ru` Механизм условий и ограничений.
  - `en` Conditions and restrictions engine.
  - `tests` ![codecov.io](https://codecov.io/gh/jeyroik/extas-conditions/coverage.svg?branch=master)
  - `climate` <a href="https://codeclimate.com/github/jeyroik/extas-conditions/maintainability"><img src="https://api.codeclimate.com/v1/badges/75161f4b9667f6a7d3d6/maintainability" /></a>
- [extas-envs](https://github.com/jeyroik/extas-envs "Переменные окружения") 
  - `ru` Пакет для работы с переменными окружения и генерации `.env.dist` файла
  - `en` Allow to install environment parameters and to generate `.env.dist`.
  - `tests` ![codecov.io](https://codecov.io/gh/jeyroik/extas-envs/coverage.svg?branch=master)
  - `climate` <a href="https://codeclimate.com/github/jeyroik/extas-envs/maintainability"><img src="https://api.codeclimate.com/v1/badges/e7617f4804b8eab2390b/maintainability" /></a>
- [extas-event-provider](https://github.com/jeyroik/extas-event-provider "Провайдер для league/event") 
  - `ru` Провайдер событий для [league/event](https://github.com/thephpleague/event), позволяющий использовать extas-стадии и плагины в качестве событий и слушателей
  - `en` Event provider for the [league/event](https://github.com/thephpleague/event), allows to use extas stages (and plugins) as events (and listeners).
  - `tests` ![codecov.io](https://codecov.io/gh/jeyroik/extas-event-provider/coverage.svg?branch=master)
- [extas-expands](https://github.com/jeyroik/extas-expands "Самораспаковывающиеся API") 
  - `ru` Позволяет реализовывать самораспаковывающиеся API (например, как у Jira).
  - `en` Allow to provide self-extracting API (ex. Jira).
  - `tests` ![codecov.io](https://codecov.io/gh/jeyroik/extas-expands/coverage.svg?branch=master)
- [extas-jsonrpc](https://github.com/jeyroik/extas-jsonrpc "Сервер JSON RPC") 
  - `ru` JSON RPC сервер, пакет позволяет создавать спецификации API на основе плагинов установки сущностей
  - `en` JSON RPC server, allow to generate specs upon to `PluginInstall` classes (see `extas-installer`).
  - `tests` ![codecov.io](https://codecov.io/gh/jeyroik/extas-jsonrpc/coverage.svg?branch=master)
- [extas-m](https://github.com/jeyroik/extas-m "Машина состояний") 
  - `ru` Машина состояний
  - `en` State machine
  - `tests` ![codecov.io](https://codecov.io/gh/jeyroik/extas-m/coverage.svg?branch=master)
- [extas-parsers](https://github.com/jeyroik/extas-parsers "Парсеры") 
  - `ru` Пакет для парсинга и замены строк.
  - `en` Package for parsing and replacing strings.
  - `tests` ![codecov.io](https://codecov.io/gh/jeyroik/extas-parsers/coverage.svg?branch=master)
- [extas-players](https://github.com/jeyroik/extas-players "Управление пользователями") 
  - `ru` Пакет для работы с пользователями
  - `en` User extas package.
  - `tests` ![codecov.io](https://codecov.io/gh/jeyroik/extas-players/coverage.svg?branch=master)
- [extas-player-current](https://github.com/jeyroik/extas-player-current "Текущий пользователь") 
  - `ru` Пакет предоставляет обёртку для получения текущего авторизованного пользователя.
  - `en` package provide wrapper for the current authorized user.
  - `tests` ![codecov.io](https://codecov.io/gh/jeyroik/extas-player-current/coverage.svg?branch=master)
- [extas-repositories-mongo](https://github.com/jeyroik/extas-repositories-mongo "Реопзиторий для работы с MongoDB") 
  - `ru` Extas-совместимый репозиторий MongoDB
  - `en` MongoDB extas-compatable repository.
  - `tests` ![codecov.io](https://codecov.io/gh/jeyroik/extas-repositories-mongo/coverage.svg?branch=master)
- [extas-repositories-fields](https://github.com/jeyroik/extas-repositories-fields "Адапторы для полей сущности") 
  - `ru` Пакет позволяет создавать адапторы для полей при создании сущности.
  - `en` Package allow to create fields-adaprots for an item fields on creating.
  - `tests` ![codecov.io](https://codecov.io/gh/jeyroik/extas-repositories-fields/coverage.svg?branch=master)
- [extas-repositories-fields-aliases](https://github.com/jeyroik/extas-repositories-fields-aliases "Имя в качестве алиса для полей сущности") 
  - `ru` Пакет позволяет автоматически подставлять имя сущности в качестве её же алиаса.
  - `en` Package allow to self-aliasing an item by it's name on creating.
  - `tests` ![codecov.io](https://codecov.io/gh/jeyroik/extas-repositories-fields-aliases/coverage.svg?branch=master)
- [extas-repositories-fields-sample-names](https://github.com/jeyroik/extas-repositories-fields-sample-names "Имя шаблона в имя сущности") 
  - `ru` Пакет позволяет автоматически подставлять имя сэмпла (шаблона) в имя сущности, поддерживаются суффиксы.
  - `en` Package allow to put sample name into entity name field. package supports different suffixes.
  - `tests` ![codecov.io](https://codecov.io/gh/jeyroik/extas-repositories-fields-sample-names/coverage.svg?branch=master)
- [extas-repositories-fields-sha1](https://github.com/jeyroik/extas-repositories-fields-sha1 "SHA1 для полей сущности") 
  - `ru` Пакет позволяет автоматически генерировать sha1-хеши для полей при создании сущности.
  - `en` Package allow to generate sha1 hash strings for an item fields on creating.
  - `tests` ![codecov.io](https://codecov.io/gh/jeyroik/extas-repositories-fields-sha1/coverage.svg?branch=master)
- [extas-repositories-fields-uuid](https://github.com/jeyroik/extas-repositories-fields-uuid "Uuid для полей сущности") 
  - `ru` Пакет позволяет автоматически генерировать uuid-строки для полей при создании сущности.
  - `en` Package allow to generate uuid strings for an item fields on creating.
  - `tests` ![codecov.io](https://codecov.io/gh/jeyroik/extas-repositories-fields-uuid/coverage.svg?branch=master)
- [extas-samples](https://github.com/jeyroik/extas-samples "Шаблоны, сэмплы для сущностей") 
  - `ru` Пакет предоставляет реализацию семплов (шаблонов) для сущностей.
  - `en` Package provide entities samples (templates) implementation.
  - `tests` ![codecov.io](https://codecov.io/gh/jeyroik/extas-samples/coverage.svg?branch=master)
  - `climate` <a href="https://codeclimate.com/github/jeyroik/extas-samples/maintainability"><img src="https://api.codeclimate.com/v1/badges/240007322d019d2f6222/maintainability" /></a>
- [extas-templates](https://github.com/jeyroik/extas-templates "Шаблоны, устаревший пакет") 
  - `ru` УСТАРЕВШИЙ ПАКЕТ - предпочтительнее использовать `extas-samples`.
  - `en` DEPRECATED - Prefer to use `extas-samples`.
  - `tests` ![codecov.io](https://codecov.io/gh/jeyroik/extas-templates/coverage.svg?branch=master)
  - `climate` <a href="https://codeclimate.com/github/jeyroik/extas-templates/maintainability"><img src="https://api.codeclimate.com/v1/badges/2d0f94b2ae161e58bc50/maintainability" /></a>
- [extas-workflow](https://github.com/jeyroik/extas-workflow "Workflow") 
  - `ru` Workflow с поддержкой нескольких схем, ограничений и триггеров.
  - `en` Worklfow with multiple schemas, restrictions and triggers supply.
  - `tests` ![codecov.io](https://codecov.io/gh/jeyroik/extas-workflow/coverage.svg?branch=master)
- [extas-workflow-dashboard](https://github.com/jeyroik/extas-workflow-dashboard "Микросервис Workflow") 
  - `ru` API для работы с Workflow
  - `en` Workflow JSON RPC api, based on `extas-worklfow`.
  - `tests` ![codecov.io](https://codecov.io/gh/jeyroik/extas-workflow-dashboard/coverage.svg?branch=master)
- [extas-workflow-dispatchers](https://github.com/jeyroik/extas-workflow-dispatchers "Обработчики переходов для Workflow") 
  - `ru` Обработчики переходов для Workflow.
  - `en` Transitions dispatchers for Workflow.
  - `tests` ![codecov.io](https://codecov.io/gh/jeyroik/extas-workflow-dispatchers/coverage.svg?branch=master)
- [extas-workflow-dashboard-svelte](https://github.com/jeyroik/extas-workflow-dashboard-svelte "Борд для управления Workflow") 
  - `ru` Svelte клиент для API для работы с Workflow
  - `en` Svelte client for Workflow API, based on `extas-worklfow-dashboard`.
  - `tests` ![codecov.io](https://codecov.io/gh/jeyroik/extas-workflow-dashboard-svelte/coverage.svg?branch=master)
- [extas-workflow-example](https://github.com/jeyroik/extas-workflow-example "Пример использования библиотеки Workflow") 
  - `ru` Пример использования пакета workflow
  - `en` Example project, shows the workflow usage.
  - `tests` ![codecov.io](https://codecov.io/gh/jeyroik/extas-workflow-example/coverage.svg?branch=master)
