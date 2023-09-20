## template — средство языка C++, предназначенное для кодирования обобщённых алгоритмов, без привязки к некоторым параметрам (например, типам данных, размерам буферов, значениям по умолчанию). В C++ возможно создание шаблонов функций и классов. Шаблоны позволяют создавать параметризованные классы и функции.

##  AUTO - это слово переопределено в новом стандарте и говорит компилятору: «Компилятор, возьми и угадай тип этой переменной!». Компилятор в многих случаях это может сам прекрасно сделать. Это удобно в шаблонах и для итераторов.

## Константный метод(преписка const  после метода), это такой метод, который не меняет свойств/членов класса. При попытке откомпилировать код, который содержит константный метод изменяющий класс - компилятор выдаст ошибку. У константных объектов, могут быть вызваны только константные методы.
