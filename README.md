# Лабораторна робота №14: Перевірка логічних функцій та умов

## Мета роботи
Метою даної лабораторної роботи є реалізація та перевірка роботи різних логічних функцій та умов на мові Python.

## Опис завдання
Реалізувати наступні функції:
- `check_truth(a, b, c)`: Перевірка логічного виразу (a and b) or c.
- `logical_equivalence(a, b)`: Перевірка логічної еквівалентності a і b.
- `xor(a, b)`: Реалізація логічної операції XOR.
- `greet(condition)`: Повертає привітання в залежності від умови.
- `nested_condition(x, y, z)`: Перевіряє рівність або відмінність трьох значень.
- `parity(number)`: Перевірка парності числа.
- `majority_vote(a, b, c)`: Реалізація голосування більшістю.
- `switch(condition)`: Перемикає умову.
- `ternary_check(condition, if_true, if_false)`: Реалізація тернарної операції.
- `validate(x, y, z)`: Перевірка умови x або (y і z).
- `chain_check(a, b, c)`: Перевірка послідовності чисел.
- `filter_true(bool_list)`: Фільтрація істинних значень у списку.
- `multiplexer(a, b, c, integer)`: Реалізація мультиплексора.

## Виконання роботи
### Структура проекту
- `main.py`: Основний файл з реалізацією всіх функцій.

### Опис файлів
- `main.py`: Містить реалізацію функцій для перевірки логічних виразів та інших задач.

### Основні функції
- `check_truth(a, b, c)`: Перевіряє істинність виразу (a and b) or c.
- `logical_equivalence(a, b)`: Перевіряє логічну еквівалентність a і b.
- `xor(a, b)`: Реалізує операцію XOR.
- `greet(condition)`: Повертає привітання в залежності від умови.
- `nested_condition(x, y, z)`: Перевіряє умови на рівність та відмінність.
- `parity(number)`: Перевіряє парність числа.
- `majority_vote(a, b, c)`: Реалізує голосування більшістю.
- `switch(condition)`: Перемикає умову.
- `ternary_check(condition, if_true, if_false)`: Реалізує тернарну операцію.
- `validate(x, y, z)`: Перевіряє умови x або (y і z).
- `chain_check(a, b, c)`: Перевіряє послідовність чисел.
- `filter_true(bool_list)`: Фільтрує істинні значення в списку.
- `multiplexer(a, b, c, integer)`: Реалізує мультиплексор.

### Приклади використання
```python
print(check_truth(True, False, True))  # Output: True
print(logical_equivalence(True, False))  # Output: False
print(xor(True, False))  # Output: True
print(greet(True))  # Output: Hello, World!
print(nested_condition(1, 1, 1))  # Output: All same
print(parity(4))  # Output: True
print(majority_vote(True, False, True))  # Output: True
print(switch(False))  # Output: True
print(ternary_check(True, "Yes", "No"))  # Output: Yes
print(validate(False, True, True))  # Output: True
print(chain_check(1, 2, 3))  # Output: Increasing
print(filter_true([True, False, True]))  # Output: [True, True]
print(multiplexer(True, False, False, 5))  # Output: 10
