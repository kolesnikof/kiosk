# Установщик режима киоска для дистрибутивов Linux на основе Debian

Простой скрипт для настройки режима киоска с браузером Chromium для дистрибутивов Linux на основе Debian.

## Установка
* Установите Debian без графической оболочки.
* Войдите в систему как `root` или с правами `root`.
* Загрузите этот установщик и запустите его:

  ```shell
  wget https://raw.githubusercontent.com/kolesnikof/debian-kiosk-installer/main/kiosk-installer.sh; chmod +x kiosk-installer.sh; ./kiosk-installer.sh
  ```

## Описание работы
Установщик создает пользователя с именем `kiosk`, установливает необходимое программное обеспечение и настраивает конфигурации, так что после перезагрузки пользователь `kiosk` войдет в систему автоматически и запустит Chromium в режиме киоска с заданым URL. Он также скроет курсор мыши.

## Копирайт
Основан на [скрипте](https://github.com/josfaber/debian-kiosk-installer) Jos Faber.
