# Samsung Galaxy Note 10 (SM-N9700) GSI Name Fix

[Русский](#русский) | [English](#english)

---

## Русский

Magisk-модуль для исправления названия модели на **Samsung Galaxy Note 10 (SM-N9700)**.

### Установка
1. Скачайте ZIP-архив из [Releases](https://github.com/mog30/note10-gsi-name-fix/releases) под ваше устройство.
2. Как обычно прошиваете через Magisk.

### Примечания

1. Я могу сделать модуль специально под ваше устройство, для этого можете оставить [Issue](https://github.com/mog30/note10-gsi-name-fix/issues/new?labels=add-device).
2. Если имя в настройках не обновилось, вставьте в терминал:
```
su
settings put global device_name "Galaxy Note 10"
settings put global device_name_internal "Galaxy Note 10"
```

---

## English

A Magisk module to fix the device name on **Samsung Galaxy Note 10 (SM-N9700)**.

### Installation
1. Download ZIP archive from [Releases](https://github.com/mog30/note10-gsi-name-fix/releases) for your devices.
2. Flash as a Magisk module as usual.

### Additions

1. I can make a module for your specific device, just leave an [Issue](https://github.com/mog30/note10-gsi-name-fix/issues/new?labels=add-device).
2. If the name in settings did not change, run the following in a terminal:
```
su
settings put global device_name "Galaxy Note 10"
settings put global device_name_internal "Galaxy Note 10"
```
