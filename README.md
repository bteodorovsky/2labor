# Звіт до роботи
## Тема: Основи програмування на Python
### Мета роботи: Вивчити основні конструкції в Python
---
### Виконання роботи
- Результати виконання завдання 1;
    - i. Попракитикувався з простими змінними, списками list, наборами set та словниками dict
    - ii. Виведів вбудовані константи
    - iii. Вивів результат роботи вбудованих функцій
    - iv. Познайомився з циклами. Написав код який демонструє роботу циклів
    - v. Познайомився з розгалуженнями
    - vi. Написав свій варіант коду з помилкою
- вставлені рисунки (скріншоти екрана або фотографії виконаного завдання у зошиті);

![alt text](https://github.com/bteodorovsky/2labor/blob/main/images/code1.PNG)
![alt text](https://github.com/bteodorovsky/2labor/blob/main/images/code2.PNG)
![alt text](https://github.com/bteodorovsky/2labor/blob/main/images/result.PNG)

 - Результати виконання завдання 2:
 ![alt text](https://github.com/bteodorovsky/2labor/blob/main/images/result2.PNG)
 ![alt text](https://github.com/bteodorovsky/2labor/blob/main/images/result3.PNG)
 ![alt text](https://github.com/bteodorovsky/2labor/blob/main/images/result4.PNG)

- вставлений код / текстовий або числовий результат / інші результати:
- код першого завдання:
- #i. 
my_list = [1, 2, 3, 4, 5]
print (my_list)

my_set = {1, 2, 3}
my_set.add(4)
print(my_set) # виведе {1, 2, 3, 4}

#ii. 
print("Константа нуля:", 0)
print("Константа значення True:", True)
#iii.
lst = [1, 2, 3, 4, 5]
print(len(lst))
print(round(2.1941, 2))
#iv.
for i in range(1, 5):
    print(i)

fruits = ["apple", "banana", "cherry"]
for fruit in fruits:
    print(fruit)
#v.
num = -10
if num > 0:
    print("Число є додатнім")
elif num == 0:
    print("Число дорівнює нулю")
else:
    print("Число є від'ємним")

x = 5
y = 10
result = x < y
print(result)
#vi.
a = 10
b = 0
try:
    c = a / b
    print(c)
except:
    print("Помилка: Ділення на нуль!")
finally:
    print("Кінець програми")
#vii.
with open("file.txt", "w") as f:
    f.write("Hello, World!")
#viii.
square = lambda x: x**2
print(square(5))
### Висновок: Завдяки цій програмі я оволодів основами програмування на Python
