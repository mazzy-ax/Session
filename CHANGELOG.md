# Session Changelog

see also [Releases on GitHub](https://github.com/mazzy-ax/Session/releases) and [Unreleased](https://github.com/mazzy-ax/Session/compare/1.1.0...main) on GitHub.

## [1.1.0](https://github.com/mazzy-ax/Session/tree/1.0.0...1.1.0) - 2021-02-26

* Изменен метод `isInRoleAdmin` так, что теперь он обращается к кэшу или к методу `isInRoleAdminImpl`
* Добавлен protected метод `isInRoleAdminImpl`, который выполняет основную работу
* Добавлен класс `SessionPerfTest` для тестирования производительности с кэшем и без кэша

## [1.0.0](https://github.com/mazzy-ax/Session/tree/1.0.0) - 2021-01-10

* Initial release
