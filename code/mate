import math

def calcular_area(figura):
    if figura == "círculo":
        radio = float(input("Ingresa el radio del círculo: "))
        return math.pi * radio ** 2
    elif figura == "cuadrado":
        lado = float(input("Ingresa el lado del cuadrado: "))
        return lado ** 2
    elif figura == "triángulo":
        base = float(input("Ingresa la base del triángulo: "))
        altura = float(input("Ingresa la altura del triángulo: "))
        return (base * altura) / 2
    elif figura == "rectángulo":
        base = float(input("Ingresa la base del rectángulo: "))
        altura = float(input("Ingresa la altura del rectángulo: "))
        return base * altura
    elif figura == "pentágono":
        lado = float(input("Ingresa el lado del pentágono: "))
        apotema = float(input("Ingresa la apotema del pentágono: "))
        return (5 * lado * apotema) / 2
    else:
        return "Figura no válida."

def calcular_perimetro(figura):
    if figura == "círculo":
        radio = float(input("Ingresa el radio del círculo: "))
        return 2 * math.pi * radio
    elif figura == "cuadrado":
        lado = float(input("Ingresa el lado del cuadrado: "))
        return 4 * lado
    elif figura == "triángulo":
        lado1 = float(input("Ingresa el primer lado del triángulo: "))
        lado2 = float(input("Ingresa el segundo lado del triángulo: "))
        lado3 = float(input("Ingresa el tercer lado del triángulo: "))
        return lado1 + lado2 + lado3
    elif figura == "rectángulo":
        base = float(input("Ingresa la base del rectángulo: "))
        altura = float(input("Ingresa la altura del rectángulo: "))
        return 2 * (base + altura)
    elif figura == "pentágono":
        lado = float(input("Ingresa el lado del pentágono: "))
        return 5 * lado
    else:
        return "Figura no válida."

def main():
    print("Bienvenido a la calculadora geométrica.")
    figura = input("Elige una figura (círculo, cuadrado, triángulo, rectángulo, pentágono): ").lower()
    operacion = input("¿Deseas calcular área o perímetro?: ").lower()

    if operacion == "área":
        resultado = calcular_area(figura)
    elif operacion == "perímetro":
        resultado = calcular_perimetro(figura)
    else:
        print("Operación no válida.")
        return

    print(f"El resultado es: {resultado:.2f}")

if __name__ == "__main__":
    main()
