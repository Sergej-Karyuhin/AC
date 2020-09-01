### Assessment 4 (Semen)
- [Символ](https://learn.javascript.ru/symbol)
- [Сборка мусора](https://learn.javascript.ru/garbage-collection)
- Примитивы и объеты отличия
  - Объекты по ссылке, примитивы по значению
  - [Все типы данных в JavaScript, кроме объектов, являются иммутабельными](https://developer.mozilla.org/ru/docs/Web/JavaScript/Data_structures)
- [Методы у примитивов](https://learn.javascript.ru/primitives-methods)
- [Перебираемые объекты](https://learn.javascript.ru/iterable#:~:text=%D0%9F%D0%B5%D1%80%D0%B5%D0%B1%D0%B8%D1%80%D0%B0%D0%B5%D0%BC%D1%8B%D0%B5%20(%D0%B8%D0%BB%D0%B8%20%D0%B8%D1%82%D0%B5%D1%80%D0%B8%D1%80%D1%83%D0%B5%D0%BC%D1%8B%D0%B5)%20%D0%BE%D0%B1%D1%8A%D0%B5%D0%BA%D1%82%D1%8B%20%E2%80%93,%D0%BF%D0%B5%D1%80%D0%B5%D0%B1%D0%B8%D1%80%D0%B0%D0%B5%D0%BC%D1%8B%D1%85%20%D0%BE%D0%B1%D1%8A%D0%B5%D0%BA%D1%82%D0%BE%D0%B2%2C%20%D0%BD%D0%B0%D0%BF%D1%80%D0%B8%D0%BC%D0%B5%D1%80%2C%20%D1%81%D1%82%D1%80%D0%BE%D0%BA%D0%B8.)
- [Spread](https://developer.mozilla.org/ru/docs/Web/JavaScript/Reference/Operators/Spread_syntax)
- [Rest](https://developer.mozilla.org/ru/docs/Web/JavaScript/Reference/Functions/Rest_parameters)
- [new Function, замыкание](https://learn.javascript.ru/new-function)
- [Флаги и дескрипторы свойств](https://learn.javascript.ru/property-descriptors)
- [for in (наследуемые п)](https://developer.mozilla.org/ru/docs/Web/JavaScript/Reference/Statements/for...in)
- [for of](https://developer.mozilla.org/ru/docs/Web/JavaScript/Reference/Statements/for...of)
- [Event loop](https://www.youtube.com/watch?v=8cV4ZvHXQL4)
- встроенные методы прототипов
- главы 8 и 9
- [Object.prototype.constructor](https://developer.mozilla.org/ru/docs/Web/JavaScript/Reference/Global_Objects/Object/constructor)
```
    let a = { ss: "123"};
    let b = a;
    console.log(a.ss, b.ss); // 123 123
    a.ss = 12;
    console.log(a.ss, b.ss); // 12 12
    a = {m: "5"};
    console.log(a.ss, b.ss); // undefined 12
```
