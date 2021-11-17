# -# задание 1
a = int(input('Укажите число:'))
b = int(input('Укажите второе число:'))
print(a + b)

username = input('Укажите Ваше ФИО:')
age = int(input('Укажите год Вашего рождения:'))
print(f'Привет {username}! Тебе уже {2021 - age} лет!')

# задание 3
a = int(input('Укажите число a:'))
temp = str(a)
a1 = temp + temp
a2 = temp + temp + temp
comp = a + int(a1) + int(a2)
print(f'Равно: {comp}')

# задание 5
a = int(input('Укажите значение выручки:'))
b = int(input('Укажите значение издержек:'))
d = ((a-b) / a) * 100
if not a <= b:
    print('Прибыль', 'Рентабельность', d)
else: (print('Убыток'))
