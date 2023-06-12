# Solicitar al usuario que ingrese su nombre
nombre = input("Por favor, ingresa tu nombre: ")

# Verificar si el usuario ha ingresado un nombre vacío
while not nombre.strip():
    print("No has ingresado un nombre válido. Intenta nuevamente.")
    nombre = input("Por favor, ingresa tu nombre: ")

# Saludar al usuario
print(f"Hola, {nombre}! ¡Bienvenido a Programación!")
