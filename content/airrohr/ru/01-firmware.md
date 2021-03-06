---
title: Драйвер и прошивка
---

Мы уже подготовили прошивку. Достаточно установить драйверы и прошить ваш NodeMCU (ESP8266).

Для связи с NodeMCU (ESP8266) вам понадобятся драйверы для вашей операционной системы.

Набор микросхем для NocdeMCU v3 обычно составляет CH341, просто проверьте обратную сторону NodeMCU (ESP8266), чтобы найти некоторую техническую информацию.

Выберите ссылку, соответствующую операционной системе вашего компьютера.

### Windows

##### Драйвер для NodeMCU (ESP8266) V2 (чип CP2102) под Windows
* [Windows 10](https://www.silabs.com/documents/public/software/CP210x_Universal_Windows_Driver.zip) - Windows 10 должна автоматически их загружать.
* [Windows 7/8/8.1](https://www.silabs.com/documents/public/software/CP210x_Windows_Drivers.zip) - 32-битная версия без поддежки 64-битных ОС

##### Драйвер для NodeMCU (ESP8266) V3 (чип CH341) под Windows
* [Windows](http://www.wch.cn/downloads/file/5.html) - Windows 10 должна автоматически их загружать.
---

### MacOS

#####  Драйверы дя MacOS Drivers
* [NodeMCU V2](https://www.silabs.com/documents/public/software/Mac_OSX_VCP_Driver.zip )
* [NodeMCU V3](http://www.wch.cn/downloads/file/178.html)

---

### Linux
Дополнительные драйверы не нужны. Все чипы должны поддерживаться системой (можно проверить командой dmesg)

---
### Прошивка устройства

* Скачайте и запустите программу для прошивки процессора Flashing Tool:
  https://github.com/opendata-stuttgart/airrohr-firmware-flasher//releases
  выберите версию для вашей ОС в разделе Assets внизу страницы:

** Linux: после загрузки файла выдайте ему разрешение на исполнение командой: `chmod o+x <download filename>`

* Выберите из списка нужную прошивку. Обычно это файл latest_BME280_ru.bin который содержит русифицированную прошивку с поддержкой сенсора BME280.

* Подключите NodeMCU к компьютеру с помощью короткого кабеля micro-USB. Используйте кабель короче 1 метра, в противном случае соединение может быть нестабильно.

* После подключения должен определиться порт подключения. Если нет, то выберите порт вручную.

NB! Желательно прошивать процессор без подключенных датчиков или в устройстве, которое ранее уже исправно работало. Если какой-либо сенсор был неверно подключен, то программа может выдать ошибку подключения к процессору и прошить будет невозможно!

* Нажмите кнопку Upload. Должна произойти загрузка прошивки.

После того, как процесс загрузки прошивки завершится отсоедините процессор из порта USB и подсоедините снова. Тем самым вы перезагрузите его.
