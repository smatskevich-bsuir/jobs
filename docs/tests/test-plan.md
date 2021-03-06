### Содержание
  1. [Введение](#1)
  2. [Объект тестирования](#2)
  3. [Риски](#3)
  4. [Аспекты тестирования](#4)
  5. [Подходы к тестированию](#5)
  6. [Представление результатов](#6)
  7. [Выводы](#7)

<a name="1"></a>
### 1. Введение
  Данный файл содержит тест-план приложения **jobs**. Основной целью тестирования является
  проверка приложения на соответствие требованиям SRS.

<a name="2"></a>
### 2. Объект тестирования
Объект тестирования -  приложение **jobs**.  
Функция, которую выполняет данное приложение:  
позволяет шифровать/дешифровать данные.  
Приложение обязано обладать определенными атрибутами качества: 
   
   1. Функциональность:
+ функциональная полнота: приложение обязано выполнять все заявленные функции в соответствии с SRS;
+ функциональная корректность: приложение должно выполнять все заявленные функции;
+ функциональная целесообразность: отсутствуют незаявленные функции, которые бы мешали приложению выполнять первоначально поставленные задачи.

2. Удобство использования:   
+ адаптивный UX-дизайн: элементы управления эргономично располагаются на экране;  
+ минималистичность: приложение выполняет только конкретные задачи пользователя.  


<a name="3"></a>
### 3. Риски
К рискам можно отнести следующие пункты:
* Возможность некорректной загрузки файла для дальнейшей работы с ним
* Особенности внешнего вида на разных экранах рабочих устройств;

<a name="4"></a>
### 4. Аспекты тестирования
К аспектам тестирования относится реализация основных функций приложения:
* вход в систему по номеру телефона
* создание задач на платформе
* создание заявок на задачи
* выбор исполнителя по задаче

#### Функциональные требования:

##### Вход в систему
Этот вариант использования небходимо протестировать на:
1. Отправку СМС с кодом
2. Корректность проверки номера телефона и кода
3. Работа капчи

##### Создание задачи
Этот вариант использования небходимо протестировать на:
1. Верификация введенной информации
2. Обновление списка задач
3. Кликабельность кнопок

##### Создание заяки
Этот вариант использования небходимо протестировать на:
1. Верификация введенной информации
2. Обновление списка заявок
3. Отображение оповещения о завяке у заказчика
4. Кликабельность кнопок

##### Выбор исполнителя
Этот вариант использования небходимо протестировать на:
1. Обновление статуса задачи
2. Отображение оповещения об утверждении заявки у исполнителя
3. Кликабельность кнопок

#### Нефункциональные требования:
1. Интуитивно понятный интерфейс
2. Приятная гамма цветов в приложении  

<a name="5"></a>
### 5. Подходы к тестированию
Каждый аспект тестирования был произведен с помощью системного тестирования.  
Системное тестирование - это тестирование программы в целом.  
Каждый тест производится вручную.  
Такой метод подходит для небольших проектов.

<a name="6"></a>
### 6. Представление результатов
Результаты тестирования представлены в [таблице](./test-results.md).

<a name="7"></a>
### 7. Выводы
Данный тестовый план позволяет протестировать основной функционал приложения.  
Успешное прохождение всех тестов может свидетельствовать тому, что приложение  
соответствует всем заявленным требованиям и стабильно работает.
