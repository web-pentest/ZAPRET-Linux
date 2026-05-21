<p align="center">
  <img src="https://i1-c.pinimg.com/1200x/bc/a9/d6/bca9d647ce8df009e2e293e33c510dcc.jpg" width="500">
</p>

## 🛡️ Что такое ZAPRET?

**ZAPRET** — инструмент для обхода блокировок (YouTube, Discord, Telegram) на Linux. Работает без VPN.
## 🚀 Способ 1 (коротоко и ясно, вы разберетесь сами.)

```bash
sh -c "$(curl -fsSL https://raw.githubusercontent.com/Snowy-Fluffy/zapret.installer/refs/heads/main/installer.sh)"
```

## 🎛️ Способ 2 (если 1 способ не подходит, полная инструкция снизу.) РЕКОМЕНДУЕТСЯ!

### 1. Клонируй репозиторий

```bash
git clone https://github.com/Sergeydigl3/zapret-discord-youtube-linux.git
cd zapret-discord-youtube-linux
```
### 2. Установи зависимости

```bash
./service.sh download-deps --default
```
### 3. Запусти меню

```bash
./service.sh
```
### 4. Что выбирать в меню

| Вопрос | Что выбрать |
|--------|-------------|
| Выбор сетевого интерфейса | `eth0` (провод) или `wlan0` (Wi-Fi) |
| Режим фильтрации | `Full` |
| Включить IPv6? | `n` |
| Запустить сейчас? | `y` |
| Добавить в автозагрузку? | `y` |

### 5. Команды управления

| Команда | Действие |
|---------|----------|
| `./service.sh service start` | Запустить |
| `./service.sh service stop` | Остановить |
| `./service.sh service status` | Статус |
| `./service.sh service restart` | Перезапустить |
| `./service.sh config` | Настройки |

## 📋 Поддерживаемые дистрибутивы

- Arch Linux / Artix
- Debian / Ubuntu
- Fedora
- Alt Linux
- Void Linux
- Alpine Linux

## 🔗 Источники

- [zapret.installer](https://github.com/Snowy-Fluffy/zapret.installer)
- [zapret-discord-youtube-linux](https://github.com/Sergeydigl3/zapret-discord-youtube-linux)

## 📄 Лицензия

MIT

---

## 🔗 GitHub

<p align="center">
  <a href="https://github.com/web-pentest">
    <img src="https://img.shields.io/badge/Мой%20GitHub-web--pentest-0d1117?style=for-the-badge&logo=github&logoColor=white" />
  </a>
</p>
