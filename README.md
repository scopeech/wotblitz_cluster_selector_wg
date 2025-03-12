# 🚀 WOT Blitz Cluster Tuner | Лагам — нет! 🎮

**Эта программа создана для выбора оптимального кластера в игре [World Of Tanks Blitz](https://wotblitz.com/), который напрямую влияет на ваш пинг в игре.**  
Если игра выбирает плохой сервер, вы можете легко выбрать лучший кластер с помощью этой программы!

---

### 🔧 Функционал программы:

1. **Выбор кластера** — Вы можете выбрать несколько кластеров, разделённых запятой (например, "EU_C0, EU_C3").
2. **Разблокировать все кластера** — Просто нажмите одну кнопку, чтобы разблокировать все серверы.
3. **Проверка пинга** — Тестирование пинга для каждого сервера в реальном времени.

Программа **редактирует файл `hosts`**, чтобы перенаправить соединение на нужные кластера. Обратите внимание, что некоторые анти-вирусы могут восстановить стандартные настройки файла `hosts` после использования программы.

---

### 📥 Установка:

1. Скачайте программу через [ссылку на репозиторий GitHub](https://github.com/scopeech/wotblitz_cluster_selector_WG).
2. Запустите `.exe` файл (он находится в папке релиза).
3. Если при запуске появляется ошибка доступа, программа попросит запуститься с правами администратора.

---

### 🧑‍💻 Как проверить работоспособность:

1. Откройте командную строку и введите:
   ```sh
   notepad C:\Windows\System32\drivers\etc\hosts
