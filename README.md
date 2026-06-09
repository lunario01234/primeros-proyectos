import random
caracteres = "+-/*!&$#?=@abcdefghijklnopqrstuvwxyzABCDEFGHIJKLMNOPQRSTUVWXYZ1234567890"
contraseña= int(input("introduzca la longitud de la contraseña"))
contraseña_generada= ""
for i in range(contraseña):
    contraseña_generada+= random.choice(caracteres)

print(contraseña_generada)
