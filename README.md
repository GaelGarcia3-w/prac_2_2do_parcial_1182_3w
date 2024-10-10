# prac_2_2do_parcial_1182_3w
Edgar Gael Garcia Camacho 3-W

print(" ")

print("Edgar Gael garcia Camacho : pr2")

print(" ")

# 1- Funcion que muestre el saludo Hey amigos! cada vez que se le pida.

def saludo(Hola):#Se ingresa la funcion para llevar acabo el programa
  
  return Hola#Rreturn significa el final de la funcion y el principio de la ejecucion.

veces= int(input("¿Cuantas veces quieres que salude? :"))#Te pide las veces que quieres que te salude.

contador = 0 #El contador  sirve para que el programa detecte el numero de veces que se quiere escribir el nombre.

while contador < veces:#Se usa "While" para que cuando el "contador" se a menor al numero de "veces" se detenga.

  print("Hola")#Aqui se imprime el saludo.
  
  contador =+1 #Para que el contador cuente los saludos uno por uno.

  ![image](https://github.com/user-attachments/assets/cdd6023b-8d55-48cd-a76e-9361a6eb183c)

  ![image](https://github.com/user-attachments/assets/6935b24d-940d-4ccc-9787-69831c920847)

  ![image](https://github.com/user-attachments/assets/336df0f6-3283-421c-9b13-f1ed00873bda)

# 2- Dar un string <nombre> y despliegue un saludo ¡hola <nombre>!.

print(" ")

print("Edgar Gael garcia Camacho 1182 :prac_2")

def saludo_con_tu_nombre(a):#Ingresa una funcion con una variable para llevar acabo el problema

  return a#Indica el final de la funcion y el principio de la ejecucion. 

a = saludo_con_tu_nombre(input("Ingresa tu nombre :"))#Te pide que ingreses tu nombre.

print("Hola" + " " + a + "!")#El mensaje que dice "hola" con tu nombre y al final un signo de exclamación.

![image](https://github.com/user-attachments/assets/967c7c0a-f090-41d8-af32-edd710b0e490)

![image](https://github.com/user-attachments/assets/7648e5f1-5da9-4fda-9763-d6d021f600e3)

# 3- Dar un entero positivo y resuelva su factorial.

print(" ")

print("Edgar Gael garcia Camacho 1182 :Prac_2")

print(" ")

def num_factorial(n):#Se ingres a la funcion una vrible par llevar acabo el programa.

  resultado = 1
  
  for i in range(2, n + 1):#Se us aessto paara determinar el numero.
  
  resultado *= i #El resultado de la factorial.
  
  return resultado#Return significa l fin de la funcion y el inicio de la ejecucion.


numero = int(input("Introduce un entero positivo: "))#Te pide introducir un numero entero.


if numero < 0:#Por si el numnero ess menor  0.

  print(" ")
  
  print("Ese no es un numero positivo >:V.")#te indica que no es un numero positivo el que seleccionaste.

else:
    
resultado = num_factorial(numero)
    
  print(f"El factorial de {numero} es {resultado}.")#El resultado de laa facotoril del numero elegido.

  ![image](https://github.com/user-attachments/assets/5731bde0-0168-42ba-b456-eedbd7d77f91)

  ![image](https://github.com/user-attachments/assets/2d052560-b8f7-4aae-8f02-f83786018992)

# 4.- Calcular total de una factura luego del IVA. primero obtener la cantidad sin IVA luego el porcentaje de IVA a aplicar, por ultimo devolver el total de la factura. 

print(" ")

print("Edgar Gael Garcia Camacho 1182:Pract_2")

print(" ")

cantidad_sin_iva = float(input("Introduce la cantidad sin IVA: "))#Te pide introducir una cantidad.

print(" ")

porcentaje_iva = float(input("Introduce el porcentaje de IVA: "))#Te pide el % del IVA.

print(" ")

total_factura = cantidad_sin_iva * (1 + porcentaje_iva / 100)#L opercion que se lleva acabo.

print(" ")

print(f"El total de la factura, incluyendo IVA, es: {total_factura:.2f}")#El resultdo de l factura.

print(" ")

![image](https://github.com/user-attachments/assets/8116bc91-3990-461d-97f9-515d5c08ca9c)

![image](https://github.com/user-attachments/assets/e31b5921-48c6-4736-9531-41cbc40827f6)

# 5- Calcular el área de un círculo  y el volumen otra que calcule el volumen de un cilindro y utilice  primera función.

print(" ")

print("edgar gael garcia camacho 1182:Prac_2")

print(" ")

import math#Esto define varias funciones matemticas.

print(" ")

radio = float(input("Introduce el radio del círculo: "))#Te pide que introduscas el radio del circulo. 

print(" ")

area = math.pi * (radio ** 2)#La operacion para llevar acabo el area del circulo.

print(" ")

print(f"El área del círculo es: {area:.2f}")#Te imprime el resultado del area.

print(" ")

altura = float(input("Introduce la altura del cilindro: "))#Te pide que introlduscas la altura del cilindro.

print(" ")

volumen = area * altura#La opercion para obtener el volumen.

print(" ")

print(f"El volumen del cilindro es: {volumen:.2f}")#Te imprime el resultado del volumen del cilindro.

print(" ")

![image](https://github.com/user-attachments/assets/e96edd89-e172-4f67-b656-eeab9fcb71d0)

![image](https://github.com/user-attachments/assets/fd219ebc-ef55-4aff-b76f-864297a3c173)

# 6- Capturar dirección de email. Desplegar mensaje si la dirección es válida o no, siendo que una función lo revisar por tener la @ solo así es valida

print(" ")

print("Edgar Gael garcia Camacho 1182:Prac_2")

print(" ")

def es_email_valido(email):#Se usa la funcion para llevar acabo el programa. 
   
  return '@' in email#Se usa para verificar que lleve el @.


print(" ")

email = input("Introduce tu dirección de email: ")#Te pide introducir un Email.

print(" ")

if es_email_valido(email):

  print(" ")
  
  print("La dirección de email es válida.")#Si el Email esta bien escrito te saldra este mensaje.
  
  print(" ")

else:

  print(" ")
  
  print("La dirección de email no es válida.")#Si e Email esta mal escrito te saldra este mensaje
  
  print(" ")

![image](https://github.com/user-attachments/assets/cbab7b9a-f63e-4c64-b89f-16724bbe6040)

![image](https://github.com/user-attachments/assets/8724d029-2c5d-4be6-9742-59202e1ceb92)

# 7- Función que de un string, regrese la longitud de la última palabra. Las palabras tienen separación por uno o más espacios.

print(" ")

print("Edgr Gael Garcia Camacho 1182:Prac_2")

print(" ")

def longitud_ultima_palabra(frase):#Se utiliza la funcion para llevar acabo el programa.
    
  palabras = frase.split()#Se usa para contar las palabras de las frases
   
  return len(palabras[-1]) if palabras else 0#Se utiliza para solo rescatar ls plabras.


print(" ")

frase = input("Introduce una frase: ")#Te pide introducir una frase.

print(" ")

longitud = longitud_ultima_palabra(frase)#Se introduce la longitud.

print(" ")



print(f"La longitud de la última palabra es: {longitud}")#Te imprime el numero de letras que hay en la ultima  palabra de la frase.


print(" ")

![image](https://github.com/user-attachments/assets/933c9cb1-2743-4d59-972e-b38184419608)

![image](https://github.com/user-attachments/assets/349597e6-7b70-4fcd-8624-568d64d14d56)

# 8- Definir una función (), que tome tres números como argumentos y devuelva el mayor de ellos.

print(" ")

print("Edgar gael garcia camacho 1182 :Prac_2" )

print(" ")

def mayor_de_tres(num1, num2, num3):#Se usa la funcion para llevar acabo el progarma. 

  #Se toma la diferencia de los numeros.
  
  if num1 >= num2 and num1 >= num3:
  
  return num1
  
  elif num2 >= num1 and num2 >= num3:
  
  return num2
  
  else:
  
  return num3

#Te pide introducir diferentes numeros en tres ocaciones.

numero1 = float(input("Introduce el primer número: "))

numero2 = float(input("Introduce el segundo número: "))

numero3 = float(input("Introduce el tercer número: "))

#Se evalua el numero mayor y se determina cual es.

mayor = mayor_de_tres(numero1, numero2, numero3)

print(f"El mayor de los tres números es: {mayor}")

![image](https://github.com/user-attachments/assets/dfa8e349-4764-4ffa-95d2-87372a853bd1)

![image](https://github.com/user-attachments/assets/3001770c-ea21-4b0f-bffc-40710fc2914a)

# 9- Escribir una funcion sum() y una función multip() que sumen y multipliquen respectivamentetodos los números de una lista. Por ejemplo: sum([1,2,3,4]) debería devolver 10 y multip([1,2,3,4])debería devolver 24.

print(" ")

print("Edgar Gael Garcia Camacho 1182:Prac_2")

print(" ")

#Se realiza una funcion para elaborar una suma.

def sumar(lista):

  return sum(lista) 

#Se realiza una funcion para elaborar una multiplicacion.

def multiplicar(lista):

  resultado = 1
  
  for num in lista:
  
  resultado *= num
  
  return resultado

#Los numeros que se van a multiplicar y  sumar.

numeros = [1, 4, 3, 2]

#Los respectivos resultados.

print("Números:", numeros)

print(" ")

print("Suma:", sumar(numeros))

print(" ")

print("Multiplicación:", multiplicar(numeros))

print(" ")

![image](https://github.com/user-attachments/assets/973fc763-38fe-48c8-9a72-b8363d56d0c3)

![image](https://github.com/user-attachments/assets/4e492080-6475-481e-9afa-78c50eda9c70)

# 10- Escribir una función que tome un carácter y devuelva True si es una vocal, de lo contrariodevuelve False.

print(" ")

print("Edgar Gael Gracia Camacho 1182 :Prac_2")

print(" ")

#Se usa la funcion para pedir los carcteres aeiou

def es_vocal(caracter):

  return caracter.lower() in 'aeiou'

#Se le pide al usuario introducir un caracter y te dice dice si es True o False.

caracter = input("Introduce un carácter: ")

print(" ")

print(es_vocal(caracter))

![image](https://github.com/user-attachments/assets/bd003478-b255-406b-97c0-636b0ddf8c99)

![image](https://github.com/user-attachments/assets/eafd7010-5d18-47f5-a2b7-69e5edf49618)  ![image](https://github.com/user-attachments/assets/7ea20f18-2b51-4c1d-8733-a60f11c46992)

# 11-  Que saque la distancia dirigida entre dos puntos.

print(" ")

print("Edgar Gael Garcia Camacho 1182:Prac_2")

print(" ")

#Se usa una funcion para tener  varibles para agregarles valores.

def distancia_dirigida(x1, y1, x2, y2):

return (x2 - x1, y2 - y1)

#Se les asignan valores a las variables

x1 = float(input("x1: "))

print(" ")

y1 = float(input("y1: "))

print(" ")

x2 = float(input("x2: "))

print(" ")

y2 = float(input("y2: "))

print(" ")

#Te imprime un mensaje con las cohordendas.

distancia = distancia_dirigida(x1, y1, x2, y2)

print(" ")

print("Distancia dirigida:", distancia)

print(" ")

![image](https://github.com/user-attachments/assets/5086cddb-88ce-4fd7-a307-040d59d2c5f6)

![image](https://github.com/user-attachments/assets/21ed38d7-3e6b-4362-90c2-45f97d91c396)






