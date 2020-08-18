# Python interview questions

## Useful links

https://towardsdatascience.com/53-python-interview-questions-and-answers-91fa311eec3f
https://www.youtube.com/watch?v=PxIqLgjtQ5Y&list=PLQC2_0cDcSKBHamFYA6ncnc_fYuEQUy0s&index=1


## Python

- Главные особенности питона. Чем он отличается от плюсов?
- Как питон работает памятью
- Анонимные функции
- Примитивные типы данных в питоне
- Чем список отличается от кортежа
- Изменяемые и неизменяемые структуры в питоне
- Структуры данных списка, кортежа, набора и словаря
- Дополнительные структуры данных в стандартной библиотеке
- with и context_manageer
- Объекты-контейнеры
- что такое *args и **kwargs?
- try,except,finally
- Транзакционен ли try блок?
- итераторы, итерируемые и генераторы
- is vs ==
- декораторы. Зачем, и как они работают
- Static methods vs class methods
- Почему нельзя передавать пустой список в качестве аргумента по умолчанию?
- Type hinting
- оператор декомпозиции в питоне
- Что есть Pickling?
- Как сгенерировать многомерный массив в чистом питоне и сделать слайс по нему? А как numpy?
- String formatting. F-strings, % operator and .format()
- Как создать класс без class?
- Мета-классы
- Regex
- map, reduce, filter
- copy, deepcopy, `[:]` and list multiplication
- Множественное наследование, проблемы, MRO

- What is GIL? Why GIL is still exist?
  - [RealPython article](https://realpython.com/python-gil/). tl;dr GIL is a mutex, one per Python
    interpreter. It allows to avoid race conditions while dealing with object references in a
    multi-threaded environment. GIL is kinda hard to remove, as C extensions used by Python are 
    tightly coupled with GIL mechanism. Main outcome of the GIL - CPU-bound tasks are slower in
    Python when decoupled into several threads.

- What does [[…]] mean in python?
  - [StackOverflow question](https://stackoverflow.com/questions/15849399/self-referencing-lists).
  tl;dr `[...]` is a notation for self-referencing. For instance, 
  ```
  >>> data = ['foo', 'bar']
  >>> data.append(data)
  >>> data
  ['foo', 'bar', [...]]
  ```
- Yield in generators. Send()
- `__str__` vs `__repr__`
- Dict preserving order of keys
- Function and class decorators
- Closures
- properties
- slots

## Numpy, Scipy

- Slicing
- Broadcasting
- Dimensions: squeezing, adding new ones and reshaping
- `np.dot` vs `np.matmul` vs `@`

## Pandas

## Scikit-learn

## Pytorch, TensorFlow

- Pytorch vs Tensorflow. Dynamic vs Static calc graph
