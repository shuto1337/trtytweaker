<div align="center">

<!-- Пульсирующий логотип с молнией -->
<svg width="160" height="160" viewBox="0 0 160 160" xmlns="http://www.w3.org/2000/svg">
  <defs>
    <radialGradient id="glow" cx="50%" cy="50%" r="50%">
      <stop offset="0%" stop-color="#6c5ce7" stop-opacity="0.9"/>
      <stop offset="100%" stop-color="#6c5ce7" stop-opacity="0"/>
    </radialGradient>
    <linearGradient id="bolt" x1="0%" y1="0%" x2="100%" y2="100%">
      <stop offset="0%" stop-color="#a29bfe"/>
      <stop offset="50%" stop-color="#6c5ce7"/>
      <stop offset="100%" stop-color="#00d68f"/>
    </linearGradient>
  </defs>
  <circle cx="80" cy="80" r="70" fill="url(#glow)">
    <animate attributeName="r" values="70;80;70" dur="3s" repeatCount="indefinite"/>
    <animate attributeName="opacity" values="0.6;1;0.6" dur="3s" repeatCount="indefinite"/>
  </circle>
  <polygon points="85,25 45,85 72,85 66,135 112,70 85,70" fill="url(#bolt)">
    <animate attributeName="opacity" values="1;0.75;1" dur="1.8s" repeatCount="indefinite"/>
  </polygon>
</svg>

# ⚡ TRTY Tweaker

<svg width="500" height="40" viewBox="0 0 500 40" xmlns="http://www.w3.org/2000/svg">
  <text x="0" y="25к" font-family="-apple-system, BlinkMacSystemFont, Segoe UI, sans-serif" 
        font-size="18" fill="#a0a0b8">
    Твиер для Windows 10 / 11 на чистом C
  </text>
  <rect x="350" y="10" width="2" height="20" fill="#6c5ce7">
    <animate attributeName="opacity" values="1;0;1" dur="1s" repeatCount="indefinite"/>
  </rect>
</svg>

<!-- Плашки -->
[![Version](https://img.shields.io/badge/version-1.0%20beta%2011-6c5ce7?style=for-the-badge)](https://github.com/shuto1337/trtytweaker/releases)
[![Platform](https://img.shields.io/badge/platform-Windows%2010%20%7C%2011-00d68f?style=for-the-badge)](https://github.com/shuto1337/trtytweaker/releases)
[![Language](https://img.shields.io/badge/language-C%20%2F%20WinAPI-a29bfe?style=for-the-badge)](https://github.com/shuto1337/trtytweaker)
[![License](https://img.shields.io/badge/license-Open%20Source-ffa502?style=for-the-badge)](https://github.com/shuto1337/trtytweaker)

<br>

<!-- Кнопки -->
<a href="https://github.com/shuto1337/trtytweaker/releases/download/trtytweaker/trty_tweaker.exe">
  <img src="https://img.shields.io/badge/⬇️_Скачать_.exe-6c5ce7?style=for-the-badge&logo=windows&logoColor=white" alt="Скачать .exe" height="40">
</a>
&nbsp;
<a href="https://github.com/shuto1337/trtytweaker/releases/download/trtytweaker/trty_tweaker.c">
  <img src="https://img.shields.io/badge/📄_Исходник_.c-a29bfe?style=for-the-badge&logo=c&logoColor=white" alt="Скачать .c" height="40">
</a>

<br><br>

<a href="https://tretiy1337.ru"><b>🌐 Сайт</b></a> · 
<a href="https://github.com/shuto1337/trtytweaker/releases"><b>📦 Все релизы</b></a> · 
<a href="https://github.com/shuto1337/trtytweaker/issues"><b>🐛 Баг-репорт</b></a>

</div>

---

<!-- Анимированная разделительная линия -->
<div align="center">
<svg width="100%" height="30" viewBox="0 0 1200 30" preserveAspectRatio="none" xmlns="http://www.w3.org/2000/svg">
  <line x1="0" y1="15" x2="1200" y2="15" stroke="#2a2a40" stroke-width="2"/>
  <circle cx="0" cy="15" r="4" fill="#6c5ce7">
    <animate attributeName="cx" values="0;1200;0" dur="6s" repeatCount="indefinite"/>
    <animate attributeName="fill" values="#6c5ce7;#00d68f;#6c5ce7" dur="6s" repeatCount="indefinite"/>
  </circle>
</svg>
</div>

## 📖 О программе

**TRTY Tweaker** — это утилита для тонкой настройки Windows 10 и Windows 11. Написана на **чистом C** с использованием **WinAPI** — без .NET, без зависимостей, без установщика. Один `.exe` — запустил и пользуешься.

Программа собрана как **один файл**, работает в портативном режиме, запускается даже в среде восстановления (WinRE). Позволяет в пару кликов применить десятки полезных твиков: от персонализации интерфейса до отключения телеметрии и оптимизации производительности.

> ⚠️ **Перед использованием обязательно создай точку восстановления системы!**

---

## ✨ Возможности

### 🎨 Персонализация — 29 твиков

| Твик | Описание |
|------|----------|
| Кастомный цвет акцента | HEX-цвет для всей системы |
| Прозрачность панели задач | Эффект Acrylic / Mica |
| Маленькие иконки | Компактная панель задач |
| Убрать корзину | Скрыть иконку с рабочего стола |
| Расширения файлов | Показывать `.exe`, `.txt` и т.д. |
| Скрытые файлы | Показать системные и скрытые файлы |
| Классическое меню | ⚠️ *Перезапускает Проводник* |
| Реклама в Пуске | Убрать рекомендованные приложения |
| Bing в поиске | Отключить веб-поиск |
| Тёмная тема | Для системы и приложений отдельно |
| Отключить анимации | Ускорить интерфейс |
| Иконки «Мой компьютер» | Вернуть на рабочий стол |
| «Панель управления» | Вернуть на рабочий стол |
| Секунды в трее | Показывать в часах |
| Snap Assist | Отключить подсказки при перетаскивании |
| Стрелки с ярлыков | ⚠️ *Перезапускает Проводник* |
| Уведомления | Отключить всплывашки |
| «Люди», «Cortana», «Task View» | Убрать с панели задач |
| Полный путь | Показывать в заголовке проводника |
| «Этот компьютер» | Открывать вместо «Быстрого доступа» |
| Недавние файлы | Убрать из проводника |
| Предпросмотр | Отключить в проводнике |
| Поиск-иконка | Компактный вид поиска |
| Центрировать панель | Для Win 11 |
| Виджеты | Убрать из Win 11 |
| Версия Windows | Показать на рабочем столе |
| Компактный режим | Проводник в компактном виде |

### ⚡ Производительность — 8 твиков

- **Телеметрия** — отключить сбор данных
- **Cortana** — отключить ассистента
- **Xbox Game Bar** — отключить игровую панель
- **Superfetch (SysMain)** — отключить службу
- **Windows Search** — отключить индексирование
- **Гибернация** — освободить несколько ГБ на диске
- **AutoEndTasks** — быстрое завершение работы
- **Фоновые приложения** — отключить

### 🔒 Приватность — 12 твиков

- Реклама в проводнике
- Советы Windows
- Timeline (история действий)
- Wi-Fi Sense
- Авто-установка приложений из Store
- Сбор рукописного ввода
- Отзывы (Feedback)
- Геолокация
- Shared Experiences
- Синхронизация настроек
- **OneDrive из проводника** — ⚠️ *Перезапускает Проводник*
- Доступ к камере

### 💻 Система — 4 твика

- SmartScreen
- UAC (с подтверждением)
- Открыть точки восстановления
- Создать точку восстановления одним кликом

### 🧹 Очистка — 7 твиков

- Временные файлы
- Prefetch
- Корзина
- DNS-кэш
- Стек сети (winsock)
- Удаление OneDrive
- Удаление приложений Microsoft Store

### 📝 Реестр — 17 твиков + редактор

- **Открыть regedit** — одной кнопкой
- Bing в поиске
- Виджеты (Win 11)
- AutoEndTasks
- **Классическое контекстное меню** — ⚠️ *Перезапускает Проводник*
- Недавние и частые файлы
- **Моментальное меню** (MenuShowDelay = 0)
- Ядро в RAM (DisablePagingExecutive)
- Телеметрия через политики
- **Убрать папки из «Этот компьютер»** — ⚠️ *Перезапускает Проводник*
- Экран блокировки
- Ускорить запуск приложений
- Приоритет переднего плана
- Отключить визуальные эффекты
- Оптимизация сети
- Не перезагружать при BSoD
- NumLock при загрузке

### 😈 Троллинг — 5 функций

- **Баннер входа в систему** — legalnoticecaption / legalnoticetext
- **Удалить баннер**
- **Добавить в автозагрузку**
- **Удалить из автозагрузки**
- **Открыть папку автозагрузки**

---

<!-- Анимированная разделительная линия -->
<div align="center">
<svg width="100%" height="30" viewBox="0 0 1200 30" preserveAspectRatio="none" xmlns="http://www.w3.org/2000/svg">
  <line x1="0" y1="15" x2="1200" y2="15" stroke="#2a2a40" stroke-width="2"/>
  <circle cx="1200" cy="15" r="4" fill="#00d68f">
    <animate attributeName="cx" values="1200;0;1200" dur="6s" repeatCount="indefinite"/>
    <animate attributeName="fill" values="#00d68f;#6c5ce7;#00d68f" dur="6s" repeatCount="indefinite"/>
  </circle>
</svg>
</div>

## 🖥️ Интерфейс

- 🌙 **Тёмная тема** в стиле современных IDE (фон `#12121f`, акцент `#6c5ce7`)
- 📋 **Боковое меню** с 8 разделами — как в VS Code
- 🎚️ **iOS-тумблеры** — плавная анимация включения/выключения
- 🔴 **Плашка «NEW»** на разделе «Реестр» — исчезает после первого захода
- 🟢 **Кнопки-индикаторы** — серая точка = не применено, зелёная = применено
- 📌 **Нижняя панель** — 4 кнопки, всегда видны:
  - `✓ Применить всё` — базовый набор твиков одним кликом
  - `✗ Выключить все твики` — сброс всех изменений
  - `↻ Перезапустить Explorer`
  - `▶ Включить Explorer` — если проводник упал
- 🖱️ **Прокрутка колёсиком** — плавный скролл длинных разделов
- ✨ **Анимация переключения** — контент «въезжает» с лёгким сдвигом
- 🔲 **Скруглённые углы** — через DWM API (работает на Win 11)
- 🔐 **Требует прав администратора**

---

## 🚀 Установка и запуск

### Вариант 1: Скачать готовый .exe

[![Скачать trty_tweaker.exe](https://img.shields.io/badge/⬇️_Скачать_trty__tweaker.exe-6c5ce7?style=for-the-badge&logo=windows&logoColor=white)](https://github.com/shuto1337/trtytweaker/releases/download/trtytweaker/trty_tweaker.exe)

1. Нажми кнопку выше, скачай `trty_tweaker.exe`
2. Правой кнопкой → **«Запуск от имени администратора»**
3. Создай точку восстановления (раздел «Система» → кнопка)
4. Применяй твики

### Вариант 2: Скачать исходник

[![Скачать trty_tweaker.c](https://img.shields.io/badge/📄_Скачать_trty__tweaker.c-a29bfe?style=for-the-badge&logo=c&logoColor=white)](https://github.com/shuto1337/trtytweaker/releases/download/trtytweaker/trty_tweaker.c)

### Вариант 3: Собрать из исходника

Требуется **MinGW-w64** (gcc 15.2.0 или новее).

```bash
git clone https://github.com/shuto1337/trtytweaker.git
cd trtytweaker
gcc trty_tweaker.c -o trty_tweaker.exe -mwindows -municode -lcomctl32 -ladvapi32 -lole32 -luuid -ldwmapi -lshell32 -s
