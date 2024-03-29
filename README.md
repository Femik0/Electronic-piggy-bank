# Схема питания копилки от USB
![scheme1](https://user-images.githubusercontent.com/70974259/119266800-dda62680-bbf4-11eb-8db4-04f16a3c2d17.jpg)

## Описание проекта
Электронный распознаватель монет (по размеру) для копилки со счётчиком суммы и статистикой по каждому типу монет.
Функционал:

* Распознавание размера монет с высокой точностью и его привязка к стоимости каждой монеты
* Вычисление общей суммы монет в копилке
* Статистика по числу монет каждого типа
* Все настройки сохраняются в энергонезависимую память и не сбрасываются при питании
* Накопленная сумма тоже хранится в энергонезависимой памяти и не боится сбоев питания
* Режим глубокого энергосбережения: в спящем режиме потребляется 0.07 мА, в схеме без преобразователя 0.02 мА
* Поддержка любого числа монет разного размера
* Автоматическая калибровка типов монет
* Сброс накопленного количества
