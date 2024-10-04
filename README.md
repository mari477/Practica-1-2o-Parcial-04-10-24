# Practica-1-2o-Parcial-04-10-24
#Actividad1_listas
print(" ")
print("Mendez Sanchez Maria Gudalupe Yazmin, 3w, listas")
print(" ")
thislist= ("43", "57", "92", "20", "37", "5", "9")     #La lista de los precios
print (thislist)                                       #Imprimo la lista
print(" ")
print ("El menor de los precios es:", thislist[5])     #Imprimo de la lista el menor
print ("El mayor de los precios es:", thislist[3])     #Imprimo de la lista el mayor
print(" ")
![image](https://github.com/user-attachments/assets/7141475e-3b27-4077-b0f8-3fe18a6c4d9d)

# Practica-2-3-Parcial-04-10-24
print(" ")
print("Mendez Sanchez Maria Gudalupe Yazmin, 3w , listas")
print(" ")

thislist= ("Pensamiento Matematico", "Lengua y Comunicacion", "Ingles", "Quimica", "Civica", "Tecnologias", "Frances", "Humanidades")  #Defino la lista

print(thislist[0])   #Imprimo la primera materia
print(thislist[1])   #Imprimo la segunda materia
print(thislist[2])   #Imprimo la tercer materia
print(thislist[3])   #Imprimo la cuarta materia
print(thislist[4])   #Imprimo la quinta materia
print(thislist[5])   #Imprimo la sexta materia
print(thislist[6])   #Imprimo la septima materia
print(thislist[7])   #Imprimo la octava materia
print(" ")
print("Estoy cursando :", thislist[0])   #Imprimo la primera materia con el "Estoy cursando"
print("Estoy cursando :", thislist[1])   #Imprimo la segunda materia con el "Estoy cursando"
print("Estoy cursando :", thislist[2])   #Imprimo la primera materia con el "Estoy cursando"
print("Estoy cursando :", thislist[3])   #Imprimo la segunda materia con el "Estoy cursando"
print("Estoy cursando :", thislist[4])   #Imprimo la primera materia con el "Estoy cursando"
print("Estoy cursando :", thislist[5])   #Imprimo la segunda materia con el "Estoy cursando"
print("Estoy cursando :", thislist[6])   #Imprimo la primera materia con el "Estoy cursando"
print("Estoy cursando :", thislist[7])   #Imprimo la segunda materia con el "Estoy cursando"
print(" ")
![image](https://github.com/user-attachments/assets/644e0c2e-0e76-4637-b82b-678f6678066a)
![image](https://github.com/user-attachments/assets/87eb3a32-b3a0-4fcf-a626-b8a6d0860e0b)

# Practica-4-Parcial-04-10-24
#Actividad4_listas
print(" ")
print("Mendez Sanchez Maria Gudalupe Yazmin, 3w , listas")
print(" ")
thislist= ("Pensamiento Matematico", "Lengua y Comunicacion", "Ingles", "Quimica", "Civica", "Tecnologias", "Frances", "Humanidades")  #Defino la lista
pm=int(input("Ingresa tu calificacion de pensamiento matematico:"))     #Imprimir ingresa la calificacion de mate
lyc=int(input("Ingresa tu calificacion de lengua y comunicacion:"))     #Imprimir ingresa la calificacion de lengua
ing=int(input("Ingresa tu calificacion de Ingles:"))                     #Imprimir ingresa la calificacion de ingles
qui=int(input("Ingresa tu calificacion de quimica:"))                    #Imprimir ingresa la calificacion de quimica
civ=int(input("Ingresa tu calificacion de civica:"))                     #Imprimir ingresa la calificacion de civica
tec=int(input("Ingresa tu calificacion de Tecnologia:"))                 #Imprimir ingresa la calificacion de tecnologia
fra=int(input("Ingresa tu calificacion de Frances:"))                    #Imprimir ingresa la calificacion de frances
hum=int(input("Ingresa tu calificacion de humanidades:"))                #Imprimir ingresa la calificacion de humanidades
print(" ")
print ("Has obtenido en Pensamiento Matematico:", pm)             #Imprimir la calificacion
print ("Has obtenido en lengua y comunicacion:", lyc)             #Imprimir la calificacion
print ("Has obtenido en ingles:", ing)                             #Imprimir la calificacion
print ("Has obtenido en Quimica:", qui)                            #Imprimir la calificacion
print ("Has obtenido en Civica:", civ)                             #Imprimir la calificacion
print ("Has obtenido en Tecnologia", tec)                         #Imprimir la calificacion
print ("Has obtenido en Frances:", fra)                            #Imprimir la calificacion
print ("Has obtenido en Humanidades:", hum)                        #Imprimir la calificacion
print("")

![image](https://github.com/user-attachments/assets/2a6430c2-422e-4122-8873-59734cf6b315)
![image](https://github.com/user-attachments/assets/e94aab2e-7fe6-41ef-9b47-ac5594f5b1b9)

# Practica-5-Parcial-04-10-24
#Actividad5_listas
print(" ")
print("Mendez Sanchez Maria Guadalupe Yazmin, 3w, listas")
print(" ") 
#Pedir los numeros ganadores del priero al cuarto
gn1=int(input("lngresa el primer numero ganador:"))
gn2=int(input("Ingresa el segundo numero ganadr:"))
gn3=int(input("Ingresa el tercer numero ganador:"))
gn4=int(input("Ingresa el cuaro numero ganador:"))
print(" ")
#Imprimir los ganadores
print("Los Ganadore son::",gn1)
print("Los Ganadore son:",gn2 )
print("Los Ganadore son:",gn3)
print("Los Ganadore son:",gn4)
print(" ")
thislist =[gn1,gn2,gn3,gn4]    #hacer la lista con los numeros ganadores
thislist.sort()                #Acomodar los numeros de la lista del mas chico al mas grande
print(thislist)                #Imprimir la lista
print(" ")
for x in thislist:             #Hacerlo para que se pongan los ganadores vertical
    print (x)                  #Hacerlo para que funcione el for con el int
print(" ")


