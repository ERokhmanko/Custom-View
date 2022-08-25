# Custom Views - разработка собственных элементов интерфейса»

## Задача
 1. Создать Custom View, которая принимает на вход данные и рассчитывает проценты заполнения. Каждые 25% должны быть заполнены цветом, отличающимся от других. Незаполненные данные должны отображаться серым цветом.
 2. Дополнить Custom View анимацией с паралелльным заполнением данных.
 3. Дополнить Custom View анимацией с последовательным заполнением данных.
 4. Сделайте так, чтобы тип заполнения можно было выбирать через XML.
## Входные данные
 
 ```sh
 findViewById<StatsView>(R.id.stats).data = listOf(
    500F,
    500F,
    500F,
    500F,
)
```

## Результаты
 [![Результат 1](https://raw.githubusercontent.com/ERokhmanko/Custom-View-Animations-/120049c12323eece62e73b9caef8db632d2e1f51/CustomView.jpg)]
 
  [![Результат 2](https://raw.githubusercontent.com/ERokhmanko/Custom-View-Animations-/b16d091386cadcac25c8dfac53b49e1752705102/gif.gif)]
 
  [![Результат 3](https://raw.githubusercontent.com/ERokhmanko/Custom-View-Animations-/b16d091386cadcac25c8dfac53b49e1752705102/sequential.png)]
