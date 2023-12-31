# Проект №4 – Web+API+Мобильное тестирование

---

## План тестирования

Продукт – [Веб-приложение](https://vimbox.skyeng.ru/video) Skyeng для преподавателей<br>
Продукт – Мобильное приложение Skyeng для iOS и Android<br>

Заказчик – Skyeng

### Используемое оборудование
- Macbook Pro M1 Pro macOS Ventura 13.2.1
- Apple iPhone 14 Pro iOS 16.5
- Pixel 3 XL API 31 Android 12.0

### Окружение
- Google Chrome Версия 114.0.5735.133,
- Safari Версия 16.3 (18614.4.6.1.6),
- Яндекс.Браузер Версия 23.5.1.762 (64-bit)
- Skyeng для iOS версия 9.90 (6145)
- Skyeng для Android v.9.71.0; SDK 6.4

### Функции и описание тестируемой системы

В рамках текущего тестирования осуществляется только основной сценарий использования раздела:<br>

- Преподаватель в работе использует только веб-интерфейс;
- Ученик использует только интерфейс мобильного приложения.

### Основные [требования](https://skyengpublic.notion.site/516dbc7548664b92895387b4c2033260)
 - Преподаватель и ученик осуществляют взаимодействие в одной веб-комнате;
 - Преподаватель использует веб-интерфейс на различных ОС при помощи браузеров Safari, Google Chrome и Яндекс.Браузер;
 - Ученик использует мобильное предложение на операционных системах iOS и Android.

### Виды тестирования
- Функциональное тестирование
- Интеграционное тестирование
- Тестирование API
- Нефункциональное тестирование (тестирование установки, совместимости, доступности, тестирование прерываний)

---

## Отчет по тестированию
### Тестирование мобильного приложения
Мобильное приложение в версии 9.90 (6145) на iOS и Android (v.9.71.0; SDK 6.4) работает нестабильно и потребляет большое количество ресурсов устройства – при участии в веб-уроке устройство может перегреваться и быстро расходовать заряд аккумулятора, не отображать информацию и материалы по уроку в тестируемом разделе. Вместе с тем, нестабильная работа приложения провоцирует появление незначительных дефектов, которые трудно уловить. Выпуск приложения в текущем виде негативно отразится как на пользовательском опыте ученика, так и на репутации компании вследствие наличия серьезных дефектов.

### Решение о готовности веб-раздела “Видеопрактика“:

На текущем этапе раздел не готов для полноценного релиза – веб-комната не поддерживает все доступные функции во всех браузерах, в которых это необходимо. Кроме того имеется несколько дефектов, которые негативно поввлияют на пользовательский опыт как преподавателя, так и ученика. 
