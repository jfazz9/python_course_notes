# python_course_notes

Fundamentals teaching;
Good reminders for me were the values in dictionaries and a simple for loop to look through each value

##Dictionary FUN
fruits = {1:'banana', 2: 'apple', 3: 'pear', 4: 'orange'}

for fruit in fruits.values():
    print(fruit)
-- banana, apple, pear, orange
keys, values = [], []
for k, v in fruits.items():
    keys.append(k)
    values.append(v)

--keys = [1,2,3]
--values = ['banana', 'apple', 'pear', 'orange']


list comprehension:
[fruit for fruit in fruits]
--['banana', 'apple', 'pear', 'orange']