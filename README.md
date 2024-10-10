# pr9-Sepulveda-Gonzalez-Angel-Alejandro-3W-1215

# 9. Función que suma todos los números de una lista

def suma_lista(lista):

  # Usamos la función sum para sumar todos los elementos de la lista
    
  return sum(lista)

# Función que multiplica todos los números de una lista

def multip_lista(lista):

  # Inicializamos el resultado en 1 (neutro multiplicativo)
    
   resultado = 1
    
  # Iteramos sobre cada número en la lista
    
  for num in lista:
    
   # Multiplicamos el resultado por el número actual
        
   resultado *= num
    
  # Devolvemos el resultado final
    
  return resultado

# Pedimos al usuario que introduzca una lista de números

entrada_usuario = input("Introduce una lista de números separados por comas: ")

# Convertimos la entrada en una lista de números

lista_numeros = [float(num.strip()) for num in entrada_usuario.split(',')]

# Calculamos la suma y el producto de la lista

suma_total = suma_lista(lista_numeros)

producto_total = multip_lista(lista_numeros)

# Mostramos los resultados

print(f"La suma de la lista es: {suma_total}")

print(f"La multiplicación de la lista es: {producto_total}")

![image](https://github.com/user-attachments/assets/27ada5ba-dd8f-435b-bcb6-f8f7878909f9)
![image](https://github.com/user-attachments/assets/f0ccb0df-0c36-4944-944e-6a8b0b1e8b06)
![image](https://github.com/user-attachments/assets/c6f66c93-7eb9-4b44-ac56-cd04d823fa35)

