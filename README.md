<p align="center">
  <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&size=22&duration=3000&pause=500&color=00E0FF&center=true&vCenter=true&width=500&lines=ZAPRET+Linux;обход+блокировок+без+VPN" alt="Typing">
</p>
<p align="center">
  <img src="https://64.media.tumblr.com/0c9f2a428b3d004a2c739778c92a0979/tumblr_nyoo6esu1X1t19jpho1_500.gif" width="500">
</p>
## 🛡️ Что такое ZAPRET?

**ZAPRET** — инструмент для обхода блокировок (YouTube, Discord, Telegram) на Linux. Работает без VPN.
## 🚀 Способ 1 (одна команда)

```bash
sh -c "$(curl -fsSL https://raw.githubusercontent.com/Snowy-Fluffy/zapret.installer/refs/heads/main/installer.sh)"
```
## 🎛️ Способ 2 (с меню)

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

## 🔗 Связь со мной

[github.com/web-pentest](https://github.com/web-pentest)

<p align="center">
  <img src="https://i.pinimg.com/originals/ed/7c/d7/ed7cd734a851a1b78694bb1ac67e8332.gif" width="300">
</p>
