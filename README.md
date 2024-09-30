#  Creado Por Ramirez Torres Angel Manuel De 3°W
-  probando manejo de tuplas

#Crear Tupla 
thistuple = ("apple", "banana", "cherry")
print(thistuple)


#Tupla con miembros duplicados 
thistuple = ("apple", "banana", "cherry", "apple", "cherry")
print(thistuple)


#Contanto miembros de la tupla
thistuple = ("apple", "banana", "cherry")
print(len(thistuple))


#Notese la diferencia de cuando SI es Tupla y cuando NO lo es, revisa lo que muestra este pequeño código 
thistuple = ("apple",)
print(type(thistuple))


#NOT a tuple
thistuple = ("apple")
print(type(thistuple))


#Asignando tuplas a variables 
#tuple1 = ("apple", "banana", "cherry")tuple2 = (1, 5, 7, 9, 3)
tuple3 = (True, False, False)


#Combinando tipos de datos en mis tuplas
tuple1 = ("abc", 34, True, 40, "male")
print(tuple1)



#Tipo de datos de una tupla
mytuple = ("apple", "banana", "cherry")
print(type(mytuple))


#Utilizando el método tuple para hacer una 
thistuple = tuple(("apple", "banana", "cherry"))
print(thistuple)

#Localiza el rango
thistuple = ("apple", "banana", "cherry", "orange", "kiwi", "melon", "mango")
print(thistuple[2:5])

#Omite el rango inical y permite que el rango empieze en el primer elemento
thistuple = ("apple", "banana", "cherry", "orange", "kiwi", "melon", "mango")
print(thistuple[:4])

#la tupla en una lista
x = ("apple", "banana", "cherry")
y = list(x)
y[1] = "kiwi"
x = tuple(y)

print(x)

#Se cambian y agregan elementos a las tuplas
thistuple = ("apple", "banana", "cherry")
y = list(thistuple)
y.remove("apple")
thistuple = tuple(y)

thistuple = ("apple", "banana", "cherry")
del thistuple
print(thistuple) #Esto genera un error porque la tupla ya no existe


![image](https://github.com/user-attachments/assets/876bb2b0-efa1-4c17-bcb5-3892a023f56f)
![image](https://github.com/user-attachments/assets/089abbbe-2bc1-4d30-84fe-ceb1acfb43a5)
![image](https://github.com/user-attachments/assets/2ba47532-9c81-4734-86df-4f0d453247fe)
![image](https://github.com/user-attachments/assets/7f035fee-aa96-4841-a723-64c8019542d7)
![image](https://github.com/user-attachments/assets/47ab315f-3de2-49c7-bfe5-20240d9ba1c0)
![image](https://github.com/user-attachments/assets/a80745cc-849e-461d-994e-fb69777b689f)





