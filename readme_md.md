<!-- STREAMING_CHUNK:Writing project header and overview... -->
# 🎮 Wild Rift Pocket Guide & Counter Sheet

Интерактивный веб-справочник и контрпик-гид для игроков **League of Legends: Wild Rift**. Позволяет быстро находить сильные и слабые стороны чемпионов, оптимизировать руны, билды предметов и сохранять персональные заметки по геймплею.

![Wild Rift Guide Preview](https://placehold.co/1200x600/091428/C8AA6E?text=Wild+Rift+Pocket+Guide)

---

<!-- STREAMING_CHUNK:Listing key features of the application... -->
## ✨ Основные возможности

* **База чемпионов:** Подробные карточки с ролями, тир-листами и контрпиками.
* **Руны и Сборки:** Рекомендованные кешстоуны, сборки предметов и микро-советы по игре.
* **Фильтрация и Поиск:** Поиск по имени героя (на русском и английском) и фильтрация по позициям (Top, Jungle, Mid, ADC, Support).
* **Кастомизация (CRUD):** Возможность добавлять новых чемпионов и редактировать существующие билды.
* **Импорт / Экспорт JSON:** Быстрое сохранение и перенос всех ваших данных между устройствами.
* **Локальное сохранение:** Автоматическое сохранение изменений в `localStorage` браузера.

---

<!-- STREAMING_CHUNK:Detailing step-by-step instructions for GitHub Pages deployment... -->
## 🚀 Как опубликовать проект на GitHub Pages

Вы можете выложить этот справочник в сеть абсолютно бесплатно за пару минут:

### Шаг 1: Создание репозитория
1. Зайдите на [GitHub](https://github.com/) и войдите в свой аккаунт.
2. Нажмите кнопку **New** (Создать новый репозиторий).
3. Назовите репозиторий, например: `wild-rift-guide`.
4. Сделайте его **Public** (Публичным) и нажмите **Create repository**.

### Шаг 2: Загрузка файлов
1. На странице созданного репозитория нажмите **uploading an existing file**.
2. Перетащите в окно загрузки два файла:
   * `index.html` (основной код приложения)
   * `README.md` (этот файл описания)
3. Нажмите **Commit changes**.

### Шаг 3: Включение GitHub Pages
1. Перейдите в раздел **Settings** (Настройки) вашего репозитория.
2. В левом меню выберите пункт **Pages**.
3. В блоке **Build and deployment**:
   * **Source**: Выберите `Deploy from a branch`.
   * **Branch**: Выберите `main` (или `master`) и папку `/ (root)`.
4. Нажмите **Save**.

Спустя 1–2 минуты ваша страница станет доступна по адресу:
`https://<ваш-username>.github.io/wild-rift-guide/`

---

<!-- STREAMING_CHUNK:Adding technological tech stack overview... -->
## 🛠️ Технологии

* **HTML5 / JavaScript (ES6+)**
* **Tailwind CSS CDN** — стилизация и адаптивный интерфейс
* **FontAwesome 6** — иконки
* **LocalStorage API** — сохранение данных