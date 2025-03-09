import random

characters = "+-/*!&$#?=@abcdefghijklnopqrstuvwxyzABCDEFGHIJKLMNOPQRSTUVWXYZ1234567890"
password_length = int(input("Введите длину пароля: "))
password = ""
for i in range(password_length):
    password += random.choice(characters)

print("Сгенерированный пароль:", password)
