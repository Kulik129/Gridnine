# Фильтрация набора перелётов.

#### Консольное приложение выполняющие функции фильтрации набора перелётов согласно различным правилам, а именно:

1. Исключением рейсов с вылетом до текущего момента времени.
2. Исключением рейсов с имеющимся сегментом датой прилёта раньше даты вылета.
3. Исключением рейсов с общим временем, проведённым на земле превышающим два часа.

---

### Структура Проекта:

> * `src/main/java/com/gridnine/testing/Main.java` - результаты обработки тестового набора перелётов.
> * `src/main/java/com/gridnine/testing/modules/filters` - методы, отвечающие за фильтрацию данных.
> * `src/main/java/com/gridnine/testing/modules/flights` - методы отвечающие за создание полетов.
> * `src/test/java/com/gridnine/testing/modules/filters` - тесты которыми покрыты методы фильтрации.

---

### Запуск Приложения

Для запуска этого приложения, выполните следующие действия:

1. Убедитесь, что у вас установлена Java версии 17.
2. Клонируйте репозиторий командой:

```bash
   git clone https://github.com/Kulik129/GridNine.git
```

3. Запустите программу любым удобным для вас способом.
