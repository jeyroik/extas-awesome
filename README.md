# Extas

`Extas` представляет собой набор библиотек и микросервисов, которые организуют платформу для разработки web-приложений различного уровня.

- `extas-foundation`
  - ru: Базовые сущности платформы.
  - en: Basic entities.
- `extas-installer`
  - ru: пакет для установки extas-совместимых сущностей
  - en: allow to install extas-compatable-entities.
- `extas-envs`
  - ru: пакет для работы с переменными окружения и генерации `.env.dist` файла
  - en: allow to install environment parameters and to generate `.env.dist`.
- `extas-jsonrpc`
  - ru: JSON RPC сервер, пакет позволяет создавать спецификации API на основе плагинов установки сущностей
  - en: JSON RPC server, allow to generate specs upon to `PluginInstall` classes (see `extas-installer`).
- `extas-workflow-dashboard`
  - ru: API для работы с Workflow
  - en: Workflow JSON RPC api, based on `extas-worklfow`.
- `extas-workflow-example`
  - ru: Пример использования пакета workflow
  - en: Example project, shows the workflow usage.
- `extas-event-provider`
  - ru: Провайдер событий для [league/event](https://github.com/thephpleague/event), позволяющий использовать extas-стадии и плагины в качестве событий и слушателей
  - en: Event provider for the [league/event](https://github.com/thephpleague/event), allows to use extas stages (and plugins) as events (and listeners).
- `extas-repositories-mongo`
  - ru: Extas-совместимый репозиторий MongoDB
  - en: MongoDB extas-compatable repository.
- `extas-players`
  - ru: Пакет для работы с пользователями
  - en: User extas package.
