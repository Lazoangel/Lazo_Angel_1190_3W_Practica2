# Lazo_Angel_1190_3W_Practica2
prueba de envio del codigo y de screenshot
1. 
print ("Lazo Jimenez Angel 3W")
def myfunction ():
    print("!!Hey amigos!!") #explica que esta función imprime un saludo y no toma parámetros ni devuelve valores

while True: #Se indica que este bucle permite la repetición continua del saludo hasta que el usuario decida salir
    myfunction()

    saludo = input("¿Quieres repetir el mensaje de nuevo?:") #Se detalla que se le pregunta al usuario si desea repetir el mensaje.   
    if saludo != 'si': #Se explica que si la respuesta del usuario no es 'si', el programa se detendrá
      break
![image](https://github.com/user-attachments/assets/3553f6d8-2916-4aa3-9e68-49586aa4d5d5)

2.
print ("Lazo Jimenez Angel 3W")
def saludar(nombre): # Define una función llamada 'saludar' que toma un parámetro 'nombre'
    print(f"¡Hola {nombre}!") # Imprime un saludo personalizado utilizando el valor de 'nombre'

nombre = input("Introduce tu nombre: ") # Solicita al usuario que introduzca su nombre y almacena la entrada en la variable 'nombre'.
saludar(nombre) # Llama a la función 'saludar' y le pasa la variable 'nombre' como argumento para mostrar el saludo
![image](https://github.com/user-attachments/assets/8e259f6e-7cf8-45f6-9fcd-4c8f3dbdcc06)
3. 
print ("Lazo Jimenez Angel Jesus 3W")
def factorial(n):    # Define una función llamada 'factorial' que toma un parámetro 'n'
    if n == 0 or n == 1:   # Si 'n' es 0 o 1, el factorial es 1.
        return 1 
    else: # Si 'n' es mayor que 1, calcula el factorial de forma recursiva
        return n * factorial(n - 1)

numero = int(input("Introduce un entero positivo: ")) # Solicita al usuario que introduzca un número entero y convierte la entrada a un entero, almacenándola en la variable 'numero'
if numero < 0:
    print("Por favor, introduce un entero positivo.")  # Si el número es negativo, imprime un mensaje pidiendo un entero positivo
else:
    resultado = factorial(numero)    # Llama a la función 'factorial' con 'numero' como argumento y almacena el resultado
    print(f"El factorial de {numero} es {resultado}.") # Imprime el resultado del factorial en un formato legible          
    ![image](https://github.com/user-attachments/assets/843cfb8a-fb73-462c-aaa9-5867bb6ef6e7)
4.
