# дана строка. Если ее длина больше 10,
# то оставить в строке тоько первые 6 символов,
# иначе дополнить строку символами 'o'до длины 12.

str = input("Введите строку:")

if len(str) > 10
    str = str[:5]
    print(str)
else:
    str = str.ljust(12, 'o')
    print(str)


# Дана строка.
# Заменить каждый честный символ или на 'a'
# если символ не равен 'a' или 'b' ,
# или на 'c' в противном случае.

str = input("Введите строку:")
result = ""
count = 0
for i in str:
    count += 1
    if count % 2 == 0:
        if i != 'a' and i != 'b':
            i = 'a'
        else:
            i = 'c'
    result += i
 print(result)

# Дан текст. Найдите сумму имеющихся в нем цифр

str = input("Выедите строку:")
sum = 0

for i in str:
    if i.isdigit():
        sum += int(i)
print(sum)

# DANIK
