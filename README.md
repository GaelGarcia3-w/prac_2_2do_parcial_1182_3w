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











