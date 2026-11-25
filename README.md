<div align="center">

# Lazygram

**Неофициальный клиент Telegram для Android**

Написан полностью на Rust · Интерфейс на Makepad · Нативные плагины на Rust

<br>

[![Rust](https://img.shields.io/badge/Rust-000000?style=for-the-badge&logo=rust&logoColor=white)](https://www.rust-lang.org/)
[![Makepad](https://img.shields.io/badge/UI-Makepad-0f172a?style=for-the-badge)](https://github.com/makepad/makepad)
[![Android](https://img.shields.io/badge/Android-8.0%2B-3DDC84?style=for-the-badge&logo=android&logoColor=white)](https://www.android.com/)
[![License](https://img.shields.io/badge/License-GPL%20v2-blue?style=for-the-badge)](LICENSE)

<br>

[Скачать](https://t.me/LazygramClient) · [Чат](https://t.me/LazygramChat) · [Сообщить о проблеме](https://github.com/corerudo/Lazygram/issues)

</div>

---

## О проекте

**Lazygram** — независимый неофициальный клиент Telegram для Android.

Он создан с нуля на современном стеке и **не является** форком или модификацией каких-либо существующих сторонних клиентов (ExteraGram, OpexGram, CherryGram, или иных *Gram и не только).

Основа — только официальные исходники Telegram.

### Почему Lazygram

- Полностью нативный код на **Rust** — высокая производительность и низкое потребление ресурсов
- Современный интерфейс на **Makepad**
- Нативная система плагинов на Rust
- Расширенные возможности настройки внешнего вида и поведения
- Уникальный интерфейс и фишки, которые не «пусть будет», а которые действительно имеют цель

---

## Системные требования

| Параметр              | Значение                   |
|-----------------------|----------------------------|
| Минимальная версия ОС | Android 8.0 (API 26)       |
| Рекомендуемая версия  | Android 12 и новее         |
| Архитектуры           | `arm64-v8a`, `armeabi-v7a` |

---

## Возможности

- Быстрый и отзывчивый интерфейс
- Гибкая настройка внешнего вида и поведения чатов
- Система плагинов на Rust
- Поддержка альтернативных иконок приложения
- Дополнительные функции, которых нет в официальном клиенте

---

## Установка

1. Перейди в канал релизов: [**@LazygramClient**](https://t.me/LazygramClient)
2. Скачай последнюю версию APK
3. Установи приложение
4. Войди в свой аккаунт Telegram

Все чаты и данные останутся на месте.

---

## Плагины

Lazygram поддерживает плагины, написанные полностью на Rust.

Это даёт:
- безопасность памяти
- высокую производительность
- чето еще

Сами плагины позволяют добавлять новые функции/элементы интерфейса или менять уже существующие.

Документация и SDK для разработчиков плагинов появятся позже.

---

## Часто задаваемые вопросы

<details>
<summary><b>С какой версии Android работает?</b></summary>
<br>
Минимально поддерживается Android 8.0. Рекомендуется Android 12 и новее, т.к. разраб (я) тестирует на Android 15.
</details>

<details>
<summary><b>Это безопасно?</b></summary>
<br>
Lazygram использует официальный протокол Telegram — весь трафик идёт напрямую к серверам Telegram, без посредников. Исходный код открыт под GPL v2 и может быть проверен.
</details>

<details>
<summary><b>Это форк другого клиента?</b></summary>
<br>
Нет. Lazygram написан с нуля и не содержит кода других сторонних клиентов.
</details>

<details>
<summary><b>Мои чаты и сообщения сохранятся?</b></summary>
<br>
Да. Все данные привязаны к аккаунту Telegram, а не к клиенту.
</details>

<details>
<summary><b>Как сообщить об ошибке или предложить идею?</b></summary>
<br>
Напиши в чат <a href="https://t.me/LazygramChat">@LazygramChat</a> или создай issue на GitHub.
</details>

---

## Лицензия

Проект распространяется под лицензией **GNU GPL v2**. Подробности в файле [LICENSE](LICENSE).
