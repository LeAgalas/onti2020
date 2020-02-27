# ОНТИ 2020 Командный этап (Команда 9)

## 1. Анализ внутренней сети

Исследование сетевой инфраструктуры 
Уязвимые устройства ( все OS: Linux; CPE: cpe:/o:linux:linux_kernel )

```
1) 10.0.9.13-- MAC Address: 00:50:56:03:17:D2 (VMware) – есть открытый 80 порт
2) 10.0.9.14 -- MAC Address: 00:50:56:03:17:D2 (VMware) – есть открытый 999 порт
3) 10.0.9.12  --  MAC Address: 00:50:56:03:17:D2 (VMware)
```

**Все три сервиса общаются с сервером 192.168.1.2**
  

## 2. Вредоносный код на архитектере MIPS

Анализ работы вируса, заразившего первый роутер.

```
1)При первом подключении клиента программа генерирует ключ, используя данные в памяти. 
2)При последующем общении с программой, ключи обновляются. 
3)Сидом рандома является timestamp.
4)Шифрование ключей происходит при помощи операции xor.
```

## 3. Поднимаем IDS на основе snort

Выполняем установку и настройку нашей IDS по [гайду](http://c-sec.ru/snort/Snort-Part-2-Installing-Snort/
).

**Запуск IDS на интерфейсе ens224: snort -i ens224**


## Состав команды

* **Платон Щербинин** - *Реверс-инженер*

* **Иван Краснопольский** - *Реверс-инженер* 

* **Кирилл Цыбров** - *Ответственный за IDS* 

* **Воронков Андрей** - *Администрирование/Аналитика уязвимостей* 

