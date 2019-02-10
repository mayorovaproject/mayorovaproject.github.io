# project EPMS
Проект EPMS (*Equipment Performance Monitoring System*) - это проект нацеленный на создание системы мониторинга функционирвания оборудования, созданный студентами Санкт-Петербургского Политехнического Университета в 2018 году.


## Команда

*Глава проекта* | *Ещё какой-то чел*
--------------- | ------------------
**Майорова Александра** | **Артур Ишмухаметов**
![alt text](images/1.jpg) | ![alt text](images/2.jpg)

### Контакты
**git**

@AlexandraMayorova

@ArthurIshmukhametov

**e-mail**

mayorova.alexandra83@gmail.com

stook1998@yandex.ru

## Программное обеспечение

Прошивка написана в среде **ArduinoIDE**. В ней реализованы: *инициализация модулей, считывание данных, обработка данных, отправка данных по HTTP*. Языка разработки С/С++. Подробнее с прошивком можно ознакомиться по ссылке [на наш git репозиторий](https://github.com/mayorovaproject/EPMS).

## О проекте
**Цель проекта** - разработать и вывести на рынок аппаратно-программный комплекс для контроля оборудования.

**Основная отличительная особенность** - платформа с интерфейсом беспроводного взаимодействия модуля с сервером и конструкторным принципом сборки. То есть можно адаптировать платформу под определённые нужды заказчика.

## Техническая реализация
### Используемые модули

Модуль | Описание
--------------- | ------------------
![alt text](images/3.jpg) | ESP8266 (ESP-12) - Микропроцессор с интерфейсом Wi-Fi
![alt text](images/4.jpg) | Ультразвуковой датчик расстояния - hc-sr04
![alt text](images/5.jpg) | RMD6300 - rfid считыватель для меток на частоте 125 кГц
![alt text](images/6.jpg) | SCT013 - инвазивный датчит тока
![alt text](images/7.JPG) | Преобразователь тока собственной разработки

### Схемы соединения

![alt text](images/9.jpg)
*Упрощенный вид*


![alt text](images/8.jpg)
*Подробная схема*


## Применение
Данный аппаратно-программный комплекс применим к оборудования без встроенных датчиков. Главная особенность данного решения - *его модульность*. Комбинируя различные датчики и дополняя под них прошивку мы можем решить различные задачи. На данном этапе разработки прописан сетевой протокол позволяющий взаимодействовать с любым сервером заказчика.

## Дополнительно
На основе разработок написана научная статья, с которой на неделе науки в 2018 году Майорова Александра заняла первое место в направлении **инноватика**. Статья опубликована на русском языке **в сборнике материалов научной конференции с
международным участием «Неделя науки СПбПУ»**
[Вы можете ознакомиться с данной статьей](mayorovaproject.github.io/docs/Mayorova_-_Sistema_funktsionirovania_oborudovania_na_proizvodstve.pdf)
      
