# Debian Security Tracker Auto-Backup

Автоматический ежедневный бэкап базы уязвимостей Debian Security Tracker:  
`https://security-tracker.debian.org/tracker/data/json`

Сбор данных выполняется ежедневно в **03:00 UTC**. Архив упаковывается в `tar.gz` и загружается в Releases. Ротация настроена на сохранение последних **60 копий**.

---

## 📥 Скачивание последней версии (Latest)

### Прямая ссылка: 
> `https://github.com/abram1ms/dts-mirro/releases/latest/download/debian-security-tracker.tar.gz`

### Через curl:
```bash
curl -L -o debian-security-tracker.tar.gz \
  https://github.com/abram1ms/dts-mirro/releases/latest/download/debian-security-tracker.tar.gz