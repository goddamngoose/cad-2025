# Лабораторная работа: Таблица продуктов

## Описание
Консольное Spring-приложение, которое считывает данные о товарах из CSV-файла и отображает их в виде таблицы.

## Структура
- Java 17
- Gradle 8.12 (Kotlin DSL)
- Spring Context (6.2.2)
- CSV-файл в `src/main/resources`

## Запуск
```
gradle run
```

## Вопросы для защиты

**Spring. Определение, назначение, особенности**  
Spring — фреймворк для упрощения разработки корпоративных Java-приложений. Обеспечивает Inversion of Control, поддержку AOP, DI, модульность.

**Проблемы ручной сборки приложений**  
Ошибки зависимости, долгий процесс, сложности в поддержке версий.

**Системы автоматической сборки**  
Maven, Gradle, Ant. Gradle — современный, поддерживает DSL, инкрементные сборки.

**Типовая структура Java проекта**  
- `src/main/java` — исходный код  
- `src/main/resources` — ресурсы  
- `src/test/java` — тесты  

**Типы зависимостей в Gradle**  
- `implementation` — для кода
- `api` — доступно внешним модулям
- `testImplementation` — для тестов

**Что такое принцип инверсии управления**  
Контроль создания объектов передаётся контейнеру (Spring), а не создаётся вручную.

**Разница между IoC и DI**  
IoC — общий принцип, DI — его реализация через внедрение зависимостей.

**Принципы IoC**
- Dependency Injection
- Event-driven programming
- Service locator

**Сцепление и связность**  
Сцепление — степень зависимости модулей. Связность — насколько тесно связаны части внутри модуля. Хорошо: низкое сцепление, высокая связность.

**Предпочтительный способ внедрения**  
Через конструктор — упрощает тестирование и делает зависимости обязательными.
