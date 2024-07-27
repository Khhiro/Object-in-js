# ЧТО ТАКОЕ `Object in JavaScript?`.

![](https://cdn.educba.com/academy/wp-content/uploads/2020/05/Object-in-JavaScript.jpg)


В JavaScript Object представляет собой один из базовых типов данных, который позволяет хранить коллекцию ключей и значений. Это фундаментальная структура данных в языке, которая используется для хранения данных в виде пар "ключ-значение". Вот несколько ключевых моментов о Object:

```cs
// Использование литерала объекта
const person = {
    name: 'John',
    age: 30,
    greet() {
        console.log('Hello!');
    }
};

// Использование конструктора Object
const car = new Object();
car.brand = 'Toyota';
car.model = 'Camry';
car.year = 2020;

// Использование функции-конструктора
function Person(name, age) {
    this.name = name;
    this.age = age;
}
const person1 = new Person('Alice', 25);

```



<br>

### 1. `create object` 
В JavaScript метод Object.create() используется для создания нового объекта с указанным прототипом и, опционально, с дополнительными свойствами. Это позволяет создать объект, который наследует свойства и методы от другого объекта, который указывается как прототип.

![](https://i.ytimg.com/vi/VLAvr-xh7OU/maxresdefault.jpg)


```cs
const obj = Object.create(null);
obj.someProperty = 'value';

console.log(obj.someProperty); // 'value'

```

<br>




### 2. Metod `Object`

В JavaScript объект Object предоставляет ряд встроенных методов, которые можно использовать для работы с объектами. Вот обзор наиболее часто используемых методов объекта Object:

![alt text](https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcSfzZAfNHZ0hgtB-3_rD-SSJ-_OtMnEWiUpog&s)


```cs
const proto = { greet() { console.log('Hello'); } };
const obj = Object.create(proto);
obj.greet(); // 'Hello'

``` 
<br>

