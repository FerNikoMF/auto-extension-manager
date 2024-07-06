# Менеджер Расширений

[![release](https://img.shields.io/github/v/release/JasonGrass/auto-extension-manager?style=for-the-badge)](https://github.com/JasonGrass/auto-extension-manager/releases)

[![chrome-web-store](https://img.shields.io/chrome-web-store/v/efajbgpnlnobnkgdcgcnclngeolnmggp?style=for-the-badge)](https://chrome.google.com/webstore/detail/extension-manager/efajbgpnlnobnkgdcgcnclngeolnmggp)
[![users](https://img.shields.io/chrome-web-store/users/efajbgpnlnobnkgdcgcnclngeolnmggp.svg?style=for-the-badge)](https://chrome.google.com/webstore/detail/extension-manager/efajbgpnlnobnkgdcgcnclngeolnmggp)
[![stars](https://img.shields.io/chrome-web-store/stars/efajbgpnlnobnkgdcgcnclngeolnmggp?style=for-the-badge)](https://chrome.google.com/webstore/detail/extension-manager/efajbgpnlnobnkgdcgcnclngeolnmggp)

[![edge-web-store](https://img.shields.io/badge/dynamic/json?style=for-the-badge&label=EDGE%20WEB%20STORE&color=ffba08&prefix=v&query=$.version&url=https://microsoftedge.microsoft.com/addons/getproductdetailsbycrxid/pifijhmfdnkanlcnecpifkmjbfoopokf)](https://microsoftedge.microsoft.com/addons/detail/extension-manager/pifijhmfdnkanlcnecpifkmjbfoopokf)
[![users](https://img.shields.io/badge/dynamic/json?style=for-the-badge&label=USERS&color=81bc06&query=$.activeInstallCount&url=https://microsoftedge.microsoft.com/addons/getproductdetailsbycrxid/pifijhmfdnkanlcnecpifkmjbfoopokf)](https://microsoftedge.microsoft.com/addons/detail/extension-manager/pifijhmfdnkanlcnecpifkmjbfoopokf)
[![stars](https://img.shields.io/badge/dynamic/json?style=for-the-badge&label=RATING&color=81bc06&query=$.averageRating&url=https://microsoftedge.microsoft.com/addons/getproductdetailsbycrxid/pifijhmfdnkanlcnecpifkmjbfoopokf)](https://microsoftedge.microsoft.com/addons/detail/extension-manager/pifijhmfdnkanlcnecpifkmjbfoopokf)

[中文](./README.md)

## 🍉 Особенности

Простой способ управления расширениями Chrome.

🍕 **Особые функции**

* Гибкая настройка правил для автоматического включения или отключения браузерных расширений.

Условия совпадения: URL / Профиль / Операционная система / Время.

Действия: Включить при совпадении, Закрыть при совпадении, Включить только при совпадении, Отключить только при совпадении, Пользовательское; Поддержка автоматического обновления страницы после включения или отключения расширений.

* Массовый экспорт/импорт и обмен расширениями

Массовый экспорт информации о расширениях, поддержка обмена текстом, json, пользовательским форматом markdown; делитесь или записывайте информацию об установке ваших расширений.

Массовый импорт расширений из общего текста или json, упрощая процесс миграции или установки нескольких расширений.

🍕 **Базовые функции**

* Включение или отключение расширений в один клик.
* Массовое включение или отключение расширений через группировку.
* Быстрый поиск расширений по имени, описанию, псевдониму или заметке.
* Управление расширениями: Быстрый переход на страницу настроек, домашнюю страницу, удаление расширений.
* Отображение в виде списка и сетки.
* Запуск расширений типа приложения в один клик.
* Установка пользовательских псевдонимов и заметок.
* История: Установка, обновление, удаление, включение и отключение расширений.

🍕 **Прочее**

* Богатые настраиваемые параметры для настройки стиля и функциональности.
* Открытый исходный код без сбора каких-либо данных пользователей.

## 🍉 Загрузка

Chrome Web Store
<https://chrome.google.com/webstore/detail/extension-manager/efajbgpnlnobnkgdcgcnclngeolnmggp>

Edge Web Store  
<https://microsoftedge.microsoft.com/addons/detail/pifijhmfdnkanlcnecpifkmjbfoopokf>

> Процесс проверки в Edge занимает больше времени, поэтому версия может отставать от Chrome Store.

## 🍉 ЛОГО

|                           Старый                           |                           Новый-Легкий                           |                           Новый-Темный                           |
|:-------------------------------------------------------:|:-------------------------------------------------------------:|:------------------------------------------------------------:|
| <img src="src/assets/img/old/icon-128.png" width="64"/> | <img src="src/assets/img/design-devin/Light.svg" width="64"/> | <img src="src/assets/img/design-devin/Dark.svg" width="64"/> |

Благодарим [0xe8nicebot](https://github.com/0xe8nicebot) за вклад в проект по дизайну логотипа.
О авторе: <https://devinwang.com/>, Вот инструмент ИИ, который он создал: [不管是现在还是未来，你的全能Ai小助手](https://chatboy.io/r/spi6jpul)

## 🍉 Помощь

Документация (на китайском): <https://ext.jgrass.cc/docs/intro>  
Блог (на китайском): <https://ext.jgrass.cc/blog>

Обратная связь может быть предоставлена через [issue](https://github.com/JasonGrass/auto-extension-manager/issues/new?body=%0A%0A%0A%0A---%0A%3C!--+%E2%86%91Please%20write%20the%20details%20of%20the%20question/suggestion%20at%20the%20top%20of%20this%20line%E2%86%91+--%3E%0AFrom+readme+%0A)

**🎃 Часто задаваемые вопросы**

🔖 Почему нет версии для Firefox?

Firefox не предоставляет важный API для включения и отключения расширений, см. [#5](https://github.com/JasonGrass/auto-extension-manager/issues/5)

🔖 Почему нельзя запускать другие расширения прямо из Менеджера Расширений или закреплять другие расширения на панели инструментов браузера?

Браузер не предоставляет соответствующие API, и эти операции должны выполняться пользователем вручную.

🔖 О расширениях типа APP

Расширения типа APP устаревают, PWA-приложения не входят в рамки браузерных расширений (поэтому некоторые браузерные приложения не видны в менеджере расширений). Сейчас редко можно встретить рабочее расширение типа APP.

Если вы включите `Отображать расширения типа APP`, вы можете обнаружить, что многие расширения типа APP не могут запуститься.
Вы можете открыть <chrome://apps>, чтобы увидеть детали.

ссылка: <https://chromium.googlesource.com/chromium/src/+/HEAD/extensions/docs/extension_and_app_types.md>

## 🍉 Интернационализация

[chrome.i18n - Chrome for Developers](https://developer.chrome.com/docs/extensions/reference/i18n/)

Языковые файлы находятся в папке `src/_locales`.
Если вы обнаружите проблемы с переводом, вы можете предоставить обратную связь в разделе issues или напрямую отправить PR для исправления.

Спасибо [Ruri-1973](https://github.com/Blank-1973) за японский перевод. [#79](https://github.com/JasonGrass/auto-extension-manager/pull/79)

## 🍉 Прочее

Этот проект создан на основе [lxieyang/chrome-extension-boilerplate-react](https://github.com/lxieyang/chrome-extension-boilerplate-react)

---

[<img src="src/assets/img/buymeacoffee.svg" width="128" alt="buy me a coffee"/>](https://www.buymeacoffee.com/jgrass/extension-manager?utm_source=readmeen)
