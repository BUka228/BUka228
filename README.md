<div align="center">

# Никита Маначинский

**Android Developer** · Kotlin · Jetpack Compose · Clean Architecture

Студент 4 курса ЮФУ (выпуск 2026) · Ростов-на-Дону
Открыт к предложениям (офис / удалённо / гибрид)

<p>
  <img alt="Kotlin" src="https://img.shields.io/badge/Kotlin-7F52FF?style=flat&logo=kotlin&logoColor=white" />
  <img alt="Jetpack Compose" src="https://img.shields.io/badge/Jetpack%20Compose-4285F4?style=flat&logo=jetpackcompose&logoColor=white" />
  <img alt="Android" src="https://img.shields.io/badge/Android-3DDC84?style=flat&logo=android&logoColor=white" />
  <img alt="Gradle" src="https://img.shields.io/badge/Gradle-02303A?style=flat&logo=gradle&logoColor=white" />
  <img alt="Room" src="https://img.shields.io/badge/Room-4285F4?style=flat&logo=android&logoColor=white" />
  <img alt="BLE" src="https://img.shields.io/badge/BLE-0082FC?style=flat&logo=bluetooth&logoColor=white" />
  <img alt="KMP" src="https://img.shields.io/badge/KMP-7F52FF?style=flat&logo=kotlin&logoColor=white" />
  <img alt="Docker" src="https://img.shields.io/badge/Docker-2496ED?style=flat&logo=docker&logoColor=white" />
</p>

[![Telegram](https://img.shields.io/badge/Telegram-2CA5E0?style=for-the-badge&logo=telegram)](https://t.me/nikirO1)
[![Email](https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail)](mailto:manachinsky88@gmail.com)

</div>

---

## О себе

Android-разработчик с практическим опытом на Kotlin. Проектирую приложения с фокусом на масштабируемость и надёжность: многомодульная архитектура, Gradle Convention Plugins, архитектурные тесты (ArchUnit), статический анализ (Detekt).

Реализовал BLE-протокол для IoT-устройства с очередью команд и механизмом ретраев. В одиночку запустил IoT-экосистему — от прошивки на ESP32 до Android-приложения и бэкенда. Выпускник **Tinkoff Fintech School** (Android), сертификат **Samsung IT Academy** с отличием.

---

## Стек

| Область | Технологии |
|---|---|
| **Язык** | Kotlin, Java |
| **UI** | Jetpack Compose, Material 3, Custom Composables |
| **Архитектура** | Clean Architecture, MVVM, MVI, UDF |
| **DI** | Hilt, Dagger 2 |
| **Асинхронность** | Coroutines, Flow, StateFlow, SharedFlow |
| **Хранение** | Room, DataStore, SharedPreferences |
| **Сеть** | Retrofit, OkHttp, Ktor Client |
| **Навигация** | Jetpack Navigation Compose |
| **Мультимодульность** | Gradle Convention Plugins, ArchUnit, Version Catalog |
| **IoT** | Bluetooth Low Energy, Command Queue, Foreground Service |
| **KMP** | Kotlin Multiplatform (shared domain logic) |
| **Фон** | WorkManager, Foreground Services |
| **Тесты** | JUnit 5, MockK, Turbine, Testcontainers |
| **CI/CD** | GitHub Actions, Detekt, ktlint |
| **Backend** | Supabase, PostgreSQL, Docker |

---

## Проекты

### [`Amulet`](https://github.com/nmanachinsky/amulet_android_app) — IoT-экосистема для парных устройств
> Companion-приложение для умного украшения: тактильные "объятия" через BLE, практики осознанности, редактор вибрационных паттернов.

**Стек:** Kotlin, Jetpack Compose, KMP, Room, BLE, WorkManager, Supabase, Hilt

- **36+ модулей** — строгие правила зависимостей, проверяемые ArchUnit-тестами
- **Offline-first** — Room + WorkManager + двусторонняя синхронизация с Supabase
- **BLE-протокол v2** — Command Queue с ретраями, потеря команд снижена на 40%
- **Доменный слой** вынесен в KMP shared-модуль
- Единственный разработчик: архитектура, приоритеты, сроки — всё самостоятельно

<sub>Также: [`Amulet Firmware`](https://github.com/nmanachinsky/Amulet_Firmware) (ESP32, C++) · [`Amulet Backend`](https://github.com/nmanachinsky/amulet_backend) (Supabase, Edge Functions)</sub>

---

### [`ProgressQuest`](https://github.com/nmanachinsky/ProgressQuest) — геймифицированный планировщик
> ToDo-приложение с RPG-элементами: опыт за задачи, Pomodoro-таймер, система достижений.

**Стек:** Kotlin, Jetpack Compose, Firebase, Hilt, Room, Material 3

- Clean Architecture + MVVM с UDF (Unidirectional Data Flow)
- Hilt DI с разделением на Core/Feature скоупы
- Реактивный UI на StateFlow + Jetpack Compose
- Firebase Auth + Firestore для облачной синхронизации

---

### [`ProjectQuest`](https://github.com/nmanachinsky/ProjectQuestOnJava) — планировщик на Java
> Расширенная версия планировщика: календарь, GTD/Eisenhower матрицы, аналитика продуктивности.

**Стек:** Java, Android SDK, Clean Architecture, MVVM, Hilt, Room, MPAndroidChart

- Три методологии продуктивности в одном приложении
- Pomodoro-таймер с гибкой настройкой интервалов
- Визуализация статистики через MPAndroidChart

---

### [`LinguaQuest`](https://github.com/nmanachinsky/LinguaQuest) — квиз для изучения языков
> Android-приложение с адаптивными викторинами и отслеживанием прогресса.

**Стек:** Kotlin, Jetpack Compose, Hilt, Room, MVVM

---

### [`P2P Analytics Platform`](https://github.com/nmanachinsky/p2p-analytics-platform) — дата-платформа
> Учебный проект Samsung IT Academy (сертификат с отличием). Полный ETL-пайплайн по Medallion Architecture.

**Стек:** Docker, Airflow, Spark, Delta Lake, PostgreSQL, MLflow

---

## Образование и сертификаты

| | |
|---|---|
| **ЮФУ** | Прикладная информатика, бакалавр (выпуск 2026) |
| **Tinkoff Fintech School** | Android-разработка на Kotlin — [сертификат](https://github.com/nmanachinsky/nmanachinsky/blob/main/certificates/Tinkoff%20Fintech%20School%20Android%20(Kotlin).pdf) |
| **Samsung IT Academy** | Большие данные — с отличием — [сертификат](https://github.com/nmanachinsky/nmanachinsky/blob/main/certificates/Сертификат_с_отличием_выпускника_трека_Большие_данные.pdf) |
| **Samsung IT Academy** | Мобильная разработка на Java — [сертификат](https://github.com/nmanachinsky/nmanachinsky/blob/main/certificates/Сертификат_выпускника_курса_Мобильная_разработка_на_Java_IT_Академии_Samsung.pdf) |
