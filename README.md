# programa-de-jon-y-lucas-
def sumar(a, b):
    return a + b

def restar(a, b):
    return a - b

def main():
    print("Programa que suma y resta dos números")
    a = float(input("Ingrese el primer número: "))
    b = float(input("Ingrese el segundo número: "))

    suma = sumar(a, b)
    resta = restar(a, b)

    print(f"La suma de {a} y {b} es: {suma}")
    print(f"La resta de {a} y {b} es: {resta}")

if __name__ == "__main__":
    main()
    def multiplicar(a, b):
    return a * b

def dividir(a, b):
    if b == 0:
        return "Error: No se puede dividir por cero."
    return a / b

print("Calculadora de multiplicar y dividir")
num1 = float(input("Ingresa el primer número: "))
num2 = float(input("Ingresa el segundo número: "))

print(f"Multiplicación: {num1} * {num2} = {multiplicar(num1, num2)}")
print(f"División: {num1} / {num2} = {dividir(num1, num2)}")
