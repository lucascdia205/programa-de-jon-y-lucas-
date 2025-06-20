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
