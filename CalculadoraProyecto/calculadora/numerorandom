import random
 
 
numero_secreto = random.randint(1, 20)
intentos = 0
 
 
print("¡Bienvenido al juego de adivinar el número!")
print("Estoy pensando en un número entre 1 y 20.")
 
 
while intentos < 6:
    adivina = int(input("Adivina el número: "))
    intentos += 1
 
 
    if adivina < numero_secreto:
        print("El número que ingresaste es muy bajo.")
    if adivina > numero_secreto:
        print("El número que ingresaste es muy alto.")
 
 
if adivina == numero_secreto:
    print("¡Felicidades! Adivinaste el número en", intentos, "intentos.")
 
if intentos == 6:
    print("Lo siento, se te acabaron los intentos. El número era", numero_secreto)
