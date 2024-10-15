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


![image](https://github.com/user-attachments/assets/6ffc6aa9-a2b4-4218-bab1-5f5a8882b93b)

