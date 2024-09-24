# PR9_TRABAJOENCLASE


#Practica en clase 1

#imprime el nombre del programador

print("Jimenez Gamboa Issis Alexa 3W")

#Se imprime una linea en blanco

print("")


print("Practica en clase,  codigo donde solicite tres numeros y se realice la multiplicacion de ellos") #esta linea se imprimira en la pantalla, en este caso es el titulo de lo que se hará

#ingresa el primer numero
num1 = int(input("Ingresa un número: "))

#ingresa el segundo numero
num2 = int(input("Ingresa un número: "))

#ingresa el tercer numero
num3 = int(input("Ingresa un número: "))

#realiza la siguiente operación
multiplicacion = num1 * num2 * num3

#imprime el resultado de la operación
print ("El resultado total es:" ,multiplicacion)

![image](https://github.com/user-attachments/assets/e4e66d9c-8f2d-4ebe-b041-459068a313f8)




#Practica en clase 2

#imprime el nombre del programador 
print("Jimenez Gamboa Issis Alexa 3W")

print("")#Se imprime una linea en blanco

#ingresa la cantidad de kilometros recorridos 
num1 = int(input("Ingresa la cantidad de kilometros recorridos: "))

#ingresa la cantidad de litros consumidos 
num2 = int(input("Ingresa la cantidad de litros consumidos: "))

#realizar la siguiente operacion
division = num2 / num1

print("") #se imprime una linea en blanco 

#se imprime el resultado 
print("El consumo de combustible por kilometrio es:", division)

![image](https://github.com/user-attachments/assets/d7903aa3-a4d1-4e43-972e-764de5cb91bd)




#Practica en clase 4

#imprime el nombre del programador 
print("Jimenez Gamboa Issis Alexa 3W")

print("Programa que obtiene el promedio de 3 numeros") #titulo del programa 

print("")#Se imprime una linea en blanco

#ingresamos el primer numero 
num1 = int(input("ingrese el primer valor:"))

#ingresamos el segundo numero
num2 = int(input("ingrese el segundo valor:"))

#ingresamos el tercer numero 
num3 = int(input("ingrese el tercer valor:"))

#indicamos que se hara una operación
promedio = (num1+num2+num3 ) / 3 

#se imprimira el resultado de la operacion
print("El promedio de las cantidades es:" , promedio)

![image](https://github.com/user-attachments/assets/56f01d09-e605-43ec-bbd8-e6aad221224e)




#Practica en clase 3

#imprime el nombre del programador
print("Jimenez Gamboa Issis Alexa 3W")

print("")#Se imprime una linea en blanco

#se imprime el titulo del programa 
print("programa que convierte temperatura en fahrenheit a celsius")

"imprime linea en blanco 
print("")

#ingresar la temperatura en fahrenheit que desea convertir a celsius
num1 = float(input("ingrese la temperatura en fahrenheit: "))

#se indica la formula a realizar
multiplicacion = (5/9) * (num1-32)

#se imprime el resultado de la operación
print("La temperatura en Celsiusius es:", multiplicacion)

![image](https://github.com/user-attachments/assets/02f7d0d7-abeb-4d7b-9147-358f2f0d628b)




#Practica 5 de trabajo en clase

#Se imprime el nombre del autor 

print("JIMENEZ GAMBOA ISSIS ALEXA 3W")


#Imprime un espacio en blanco

print("")


#Nombre del programa 

print("Programa que pide al usuario adivinar el numero almacenado")


#Imprime una linea en blanco

print("")


#Funcion que se utilizara 

import random
intentos = 0


#Imprime para introducir el nombre del usuario tan bello 

print ("cual es tu nombre?")
nombre = input()


#almacen aun numero del 1 al 50

x = random.randint (1, 50)


#Imprime la cantidad de intentos 

print ("Hola " + nombre + ",vamos a jugar tienes nomas 5 intentos" )


#Funcion para la cantidad de intentos 

while intentos < 5:


    #Funcion para la cantidad de intentos que se lleva 
    
    intentos = intentos + 1

    
    #Imprime para introducir un numero y tratar de adivinar 
    
    print ("Elige un numero del 1 al 50")

    
    #Funcion para introducir el numero 
    
    numero = input ()
    numero = int (numero)

    
    #Funcion que se utilizara para acercar al usuario porq esta mensillo 
    
    if x < numero:

    
        #Imprime lo que esta entre comillas
        
        print ("El numero es menor")

        
        #Imprime lo que se encuentra entre comillas o sea la cantidad de intentos, dahhh
        
        print ("Llevas %d intentos" % (intentos))

        
    #Funcion que se utiliza para ingresar el siguiente numero 
    
    if x > numero:

    
        #Se iprime lo que esta entre comillas 
        
        print ("El numero es mayor")

        
        #Imprime lo que esta entre comillas o sea otra vez la cantidad de intentos que lleva el bello usuario jiji
        
        print ("Llevas %d intentos" % (intentos))

        
    #Funcion que se utiliza para volver 
    
    if numero == x:
        break


if numero == x:


    #imprime lo que esta entre comillas 
    
    print ("Eres un genio, chiquill@")

    
    #imprime la cantidad de intentos con los cuales lo lograste 
    
    print (nombre + " lo lograste con %d intentos" % (intentos))

    
#Imprime que no lo lograste jjajajjaj

if numero != x:


    print ("has perdido tontuelo, vuelve a jugar")

![image](https://github.com/user-attachments/assets/f23acada-27cc-4227-a865-8d846dea01d5)




