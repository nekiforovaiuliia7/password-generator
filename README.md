import random
print('Добро пожаловать в генератор паролей!')
symbols = 'abcdefghijklmnopqrstuvwxyzABCDEFGHIJKLMNOPQRSTUVWXYZ0123456789!#$%&*+-=?@^'
number = int(input('Количество паролей? '))
length = int(input('Количество символов в пароле? '))
print('твои пароли:')
for pwd in range(number):
    passwords =''
    for c in range(length):
        passwords += random.choice(symbols)
    print(passwords)
