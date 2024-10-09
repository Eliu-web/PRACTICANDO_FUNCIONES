print("")
print ("Zamarripa Castro Erick Fabián 3W 1220")

#Practicando funciones
#En Python una funcion es definida usando la palabra def como palabra clave 

def my_function():
  print("HOLA PE YA COMISTE CUYO ")


#Para llamar a una funcion, use la funcion nombrada y seguida de parentesis:
def my_function():
  print("HOLA PE YA COMISTE CUYO ")
 
#El siguiente ejemplo tiene una función con un argumento (fname). 
 #Cuando se llama a la función, pasamos un nombre, que se usa dentro de la función para imprimir el nombre completo:

def my_function(fname):
  print(fname + " ")

my_function("dame un pedazo")
my_function("de ese chocolate")
my_function("Se acabdo ese era el ultimo")

#De forma predeterminada, se debe llamar a una función con la cantidad correcta de argumentos. Lo que significa que si su función espera 2 argumentos, debe llamar a la función con 2 argumentos, ni más ni menos.

![image](https://github.com/user-attachments/assets/b4aaffef-cb07-445c-a81a-56855a59bf2d)
![image](https://github.com/user-attachments/assets/5fd82608-495e-4d7c-9082-44e65971a73f)

#Ejemplo

#Esta función espera 2 argumentos y obtiene 2 argumentos:

def my_function(fname, lname):

  print(fname + " " + lname)

my_function("TILIN", "EL PEPE")

#Esta función espera 2 argumentos, pero solo obtiene 1:
def my_function(fname, lname):
  print(fname + " " + lname)

my_function("TILIN", "EL PEPE")

#Si se desconoce el número de argumentos, agregue un * antes del nombre del parámetro:

def my_function(*kids):
  print("El chavito mas joven es: " + kids[2])

my_function("TILIN", "EL PEPE", "ETE SECH")

#También puede enviar argumentos con la sintaxis clave = valor.

#De esta forma no importa el orden de los argumentos.
def my_function(child3, child2, child1):
  print("TEl chavito mas joven es:" + child3)

my_function(child1 = "TILIN", child2 = "EL PEPE", child3 = "ETE SECH")

#De esta manera, la función recibirá un diccionario de argumentos y podrá acceder a los elementos en consecuencia:
#Si se desconoce el número de argumentos de palabras clave, agregue un doble ** antes del nombre del parámetro:

#Ícono de validado por la comunidad

def my_function(**kid):
  print("Su apellido es:  " + kid["lname"])

my_function(fname = "POTAXIO", lname = "ARROZ BLANCO")

![image](https://github.com/user-attachments/assets/576acb21-80f5-4c75-ae54-575e374a29eb)
![image](https://github.com/user-attachments/assets/f589bb2d-48f7-4d7b-badc-129c74d1f2b0)
![image](https://github.com/user-attachments/assets/b4a1de52-c17d-42f6-a8e6-b7e941dcbbbf)

PUNTO #2

print("")
print ("Zamarripa Castro Erick Fabián 3W 1220")
print("")
#Valor de parámetro predeterminado
#El siguiente ejemplo muestra cómo utilizar un valor de parámetro predeterminado.
#Si llamamos a la función sin argumento, usa el valor predeterminado:
def my_function(country = "peru pe causa"):
  print("Yo soy de " + country)

my_function("MEXICO TACO TACO")
print("")
my_function("INDIA DIARREA DIARREA")
print("")
my_function()
print("")
my_function("BRAZIL, EU SOU BRASILEIRO FILHO DA ######")
print("")

#Pasar una lista como argumento
#Puede enviar cualquier tipo de argumento de datos a una función (cadena, número, lista, diccionario, etc.) y será tratado como el mismo tipo de datos dentro de la función.

#P.ej. Si envía una Lista como argumento, seguirá siendo una Lista cuando llegue a la función:

def my_function(food):
  for x in food:
    print(x)

fruits = ["ARROZ", "CHOCOLATE CASERO", "FRUTILLA"]

![image](https://github.com/user-attachments/assets/2df7f0f4-c096-435d-8923-85a8c8d73cb8)
![image](https://github.com/user-attachments/assets/0b0ff7c2-e84f-4c87-840a-a3d7525eade3)
![image](https://github.com/user-attachments/assets/6ffc6aa9-a2b4-4218-bab1-5f5a8882b93b)

