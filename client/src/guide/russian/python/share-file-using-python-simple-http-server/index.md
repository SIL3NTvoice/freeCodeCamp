---
title: Share File Using Python SimpleHTTPserver
localeTitle: Совместное использование файла с помощью Python SimpleHTTPserver
---
## Для отправки файла необходимо выполнить шаги.

1.  Убедитесь, что оба компьютера подключены через одну сеть через LAN или WIFI.
2.  Откройте терминал в Ubuntu и убедитесь, что на вашем ПК установлен Python.
3.  Если он не установлен, установите его, набрав терминал «sudo apt-get install python» без кавычек.
4.  Перейдите в каталог, файл которого вы хотите поделиться, используя команду cd (change directory).
5.  Введите эту команду «python -m simpleHTTPserver» без кавычек.
6.  Откройте новый терминал и введите ifconfig и найдите свой IP-адрес.

## Теперь на втором компьютере

1.  Откройте браузер и введите ip-адрес первого.
2.  Не забудьте добавить номер порта в конце ip-адреса, который по умолчанию: 8000

Откроется страница, показывающая структуру типа Directory, и она отобразит все файлы с исходного ПК.  
Теперь вы можете получить доступ ко всем файлам.