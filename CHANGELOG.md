# simter-dependencies changelog

## 1.3.0-M10 - 2019-12-18

- Upgrade to simter-build-1.3.0-M10
- Upgrade to jxls-2.7.2

## 1.3.0-M9 - 2019-12-10

- Upgrade to simter-build-1.3.0-M9
- Upgrade to simter-kotlin-1.4.0-M2
- Upgrade to simter-r2dbc-ext-1.4.0-M2
- Upgrade to simter-reactive-web-1.2.0-M4
- Upgrade to Upgrade to simter-embedded-database-ext-1.1.0-M2
- Add r2dbc-client dependencManagement - because [r2dbc-client/issue#63](https://github.com/r2dbc/r2dbc-client/issues/63)

## 1.3.0-M8 - 2019-12-03

- Upgrade to simter-build-1.3.0-M8
- Upgrade to simter-kotlin-1.3.0-M1
- Remove junit4 dependency from spring-boot-starter-test

## 1.3.0-M7 - 2019-11-28

- Upgrade to simter-build-1.3.0-M7
- Upgrade to simter-reactive-web-1.2.0-M3
- Add org.jetbrains.kotlinx:kotlinx-coroutines-bom dependencyManagement
- Add org.jetbrains.kotlinx:kotlinx-serialization-runtime dependencyManagement

## 1.3.0-M6 - 2019-11-20

- Upgrade to simter-build-1.3.0-M6
- Upgrade to simter-reactive-web-1.2.0-M2

## 1.3.0-M5 - 2019-11-16

- Upgrade to simter-build-1.3.0-M5
- Upgrade to simter-reactive-web-1.2.0-M1

## 1.3.0-M4 - 2019-11-07

- Upgrade to simter-build-1.3.0-M4
- Upgrade to simter-reactive-test-0.2.0

## 1.3.0-M3 - 2019-10-18

- Upgrade to simter-build-1.3.0-M3
- Upgrade to Upgrade to simter-embedded-database-ext-1.1.0-M1
- Upgrade to simter-reactive-web-1.1.2
- Change groupId com.nhaarman to com.nhaarman.mockitokotlin2
- Upgrade to commons-dbcp2-2.7.0
- Upgrade to HikariCP-3.4.1
- Upgrade to wix-embedded-mysql-4.6.0
- Upgrade to quartz-2.3.1
- Upgrade to rxjava-2.2.13
- Upgrade to genson-1.6
- Upgrade to lombok-1.18.10
- Upgrade to assertj-core-3.13.2
- Upgrade to auto-value-1.7.0
- Upgrade to value-2.8.0
- Upgrade to json-unit-assertj-2.10.0
- Upgrade to commons-lang3-3.9
- Upgrade to xmlbeans-3.1.0
- Upgrade to okhttp-4.2.2
- Upgrade to modelmapper-2.3.5
- Upgrade to hamcrest-date-2.0.7
- Upgrade to javaee-api-8.0.1
- Upgrade to johnzon-jsonb-1.2.0
- Upgrade to yasson-1.0.5
- Upgrade to jakarta.json.bind-api-1.0.2
- Upgrade to commons-compress-1.19

## 1.3.0-M2 - 2019-10-08

- Upgrade to simter-build-1.3.0-M2
- Upgrade to simter-r2dbc-ext-1.4.0-M1

## 1.3.0-M1 - 2019-09-27

- Upgrade to simter-build-1.3.0-M1

## 1.2.1 - 2019-09-27

- Upgrade to simter-rest-jaxrs-1.1.1
- Upgrade to simter-reactive-security-1.1.1
- Upgrade to simter-reactive-web-1.1.1
- Upgrade to simter-kotlin-1.3.1
- Upgrade to simter-build-1.2.1

## 1.2.0 - 2019-07-02

- Upgrade to simter-build-1.2.0

## 1.1.2 - 2019-01-16 16:30

- Upgrade to simter-kotlin-1.1.0

## 1.1.1 - 2019-01-16 14:13

- Add simter-kotlin-1.0.0

## 1.1.0 - 2019-01-14

- Upgrade maven parent to simter-build-1.1.0
- Upgrade to simter-r2dbc-ext-1.1.1

## 1.0.1 - 2019-01-10

- Upgrade to simter-r2dbc-ext-1.1.0 (from kotlin module to java module)

## 1.0.0 - 2019-01-07 (spring-boot-2.1.1, spring-5.1.3, maven-3.6.0)

- Initial with simter modules :
    | SN | Module                   | Version | Type
    |----|--------------------------|---------|------
    |  1 | simter-dependencies      | 1.0.0   | pom
    |  2 | simter-parent            | 1.0.0   | pom
    |  3 | simter-context           | 1.0.0   | java
    |  4 | simter-jwt               | 1.0.0   | java
    |  5 | simter-test              | 1.0.0   | java
    |  6 | simter-core              | 1.0.0   | java
    |  7 | simter-json              | 1.0.0   | java
    |  8 | simter-genson-ext        | 1.0.0   | java
    |  9 | simter-jpa-ext           | 1.0.0   | java
    | 10 | simter-jxls-ext          | 1.0.0   | java
    | 11 | simter-mongo-ext         | 1.0.0   | kotlin
    | 12 | simter-jackson-ext       | 1.0.0   | kotlin
    | 13 | simter-http              | 1.0.0   | java
    | 14 | simter-security          | 1.0.0   | java
    | 15 | simter-rest-jaxrs        | 1.0.0   | java
    | 16 | simter-rest-jaxrs-jersey | 1.0.0   | java
    | 17 | simter-util              | 1.0.0   | kotlin
    | 18 | simter-template          | 1.0.0   | java
    | 19 | simter-scheduling        | 1.0.0   | java
    | 20 | simter-exception         | 1.0.0   | java
    | 21 | simter-reactive-context  | 1.0.0   | kotlin
    | 22 | simter-reactive-web      | 1.0.0   | kotlin
    | 23 | simter-reactive-security | 1.0.0   | kotlin
    | 24 | simter-query             | 1.0.0   | kotlin
    | 25 | simter-r2dbc-ext         | 1.0.0   | kotlin