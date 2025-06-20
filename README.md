# Programa que multiplica y divide dos números

# Solicitar al usuario los dos números
num1 = float(input("Introduce el primer número: "))
num2 = float(input("Introduce el segundo número: "))

# Multiplicación
multiplicacion = num1 * num2
print(f"La multiplicación de {num1} y {num2} es: {multiplicacion}")

# División, verificando que el segundo número no sea cero
if num2 != 0:
    division = num1 / num2
    print(f"La división de {num1} entre {num2} es: {division}")
else:
    print("No se puede dividir entre cero.")
def sumar(a, b):
    return a + b

def restar(a, b):
    return a - b

def main():
    print("Programa que suma y resta dos números.")
    a = float(input("Ingresa el primer número: "))
    b = float(input("Ingresa el segundo número: "))
    operacion = input("¿Quieres sumar o restar? (suma/resta): ").strip().lower()

    if operacion == "suma":
        resultado = sumar(a, b)
        print(f"El resultado de la suma es: {resultado}")
    elif operacion == "resta":
        resultado = restar(a, b)
        print(f"El resultado de la resta es: {resultado}")
    else:
        print("Operación no reconocida. Por favor, elige 'suma' o 'resta'.")

if __name__ == "__main__":
    main()
