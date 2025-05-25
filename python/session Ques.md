
# Python Basics Questions (Session)

**Instructions:** Choose the best answer for each question.

---

<!-- ## 1. Introduction to Python & Basic Syntax -->

**Question 1:** What is the primary purpose of comments in Python code?

a) To execute specific parts of the code faster.

b) To disable lines of code temporarily.

c) To provide explanations and make the code more readable for humans.

d) To define variables and functions.

---
<!-- ## 2. Variables and Data Types -->

**Question 2:** Which of the following is NOT a valid Python variable name?

a) my_variable

b) _variable2

c) 2nd_variable

d) variableName

---
**Question 3:** What is the data type of the variable `temperature = 25.5`?

a) int

b) str

c) float

d) bool

---
**Question 4:** What will be the output of the following code?

```python
message = "Python"
year = 2023
print(message + " " + str(year))
```


a) Python 2023

b) Python2023

c) Python + 2023

d) TypeError


<!-- --- -->

<!-- ## 3. Lists -->
---

**Question 5:** How do you correctly access the element `"cherry"` from the list `fruits = ["apple", "banana", "cherry", "date"]`?

a) fruits[4]

b) fruits(3)

c) fruits[2]

d) fruits.get(2)

---

**Question 6:** Which method is used to add an element to the end of an existing list?

a) insert()

b) append()

c) add()

d) put()

---

**Question 7:** What is the result of `len(my_list)` if `my_list = ['red', 'green', 'blue', 'yellow']`?

a) 3

b) 4

c) 5

d) Error


<!-- --- -->

<!-- ## 4. Tuples -->
---

**Question 8:** Which of the following best describes a Python tuple?

a) A mutable, ordered collection of items.

b) An immutable, unordered collection of unique items.

c) An immutable, ordered collection of items.

d) A mutable, unordered collection of key-value pairs.

---

**Question 9:** If `coords = (10, 20, 30)`, what will happen if you try to execute `coords[0] = 15`?

a) The tuple will become (15, 20, 30).

b) A TypeError will occur.

c) The value of coords will remain (10, 20, 30) without an error.

d) It will convert coords into a list.


<!-- --- -->

<!-- ## 5. Dictionaries -->
---

**Question 10:** How do you retrieve the value associated with the key `'price'` from the dictionary `product = {'name': 'Laptop', 'price': 1200, 'brand': 'XYZ'}`?

a) product.value('price')

b) product['price']

c) product.get(1)

d) product.price

---

**Question 11:** What does `my_dict.keys()` return for `my_dict = {'city': 'London', 'country': 'UK'}`?

a) A list containing ['London', 'UK'].

b) A dictionary view object containing `dict_keys(['city', 'country'])`.

c) A tuple containing ('city', 'country').

d) The number of keys in the dictionary.

---

**Question 12:** How would you add a new entry `'material': 'plastic'` to the dictionary `item = {'type': 'pen'}`?

a) item.add('material', 'plastic')

b) item['material'] = 'plastic'

c) item.update('material'='plastic')

d) item.insert('material', 'plastic')


<!-- --- -->

<!-- ## 6. Conditional Statements (if-elif-else) -->
---

**Question 13:** What is the output of the following code if `temp = 28`?

```python
temp = 28
if temp > 30:
    print("Hot")
elif temp >= 20:
    print("Warm")
else:
    print("Cold")
```


a) Hot

b) Warm

c) Cold

d) Nothing is printed.

---

**Question 14:** Which logical operator returns `True` if at least one of the conditions is `True`?

a) and

b) not

c) or

d) is


<!-- --- -->

<!-- ## 7. Loops (for and while) -->
---

**Question 15:** How many times will the message `"Coding is fun!"` be printed?

```python
for i in range(4):
    print("Coding is fun!")
```


a) 3

b) 4

c) 5

d) 0

---

**Question 16:** What is the value of `count` after this `while` loop finishes?

```python
count = 0
while count < 3:
    count += 1
print(count)
```


a) 0

b) 2

c) 3

d) 4


<!-- --- -->

<!-- ## 8. Functions -->
---

**Question 17:** Which keyword is used to define a function in Python?

a) function

b) define

c) func

d) def

---

**Question 18:** What is the purpose of the `return` statement in a Python function?

a) To print a value to the console.

b) To stop the function's execution and send a value back to the caller.

c) To define a new variable inside the function.

d) To call another function.


<!-- --- -->

<!-- ## 9. Classes and Objects (Basic Understanding) -->
---

**Question 19:** In Object-Oriented Programming (OOP), what is an "object"?

a) A blueprint for creating data types.

b) An instance of a class.

c) A function defined inside a class.

d) A variable that holds only integer values.

---

**Question 20:** If you have a class `Dog` and you want to create a new instance of it, which line of code is correct?

a) my_dog = Dog.create()

b) my_dog = Dog()

c) new_dog_instance = Dog.object()

d) Dog.new_instance()

