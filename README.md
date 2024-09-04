#PREPARANDO UMA CALCULADORAA

print("Bem vindo à calculadora")

num1 = float(input("Digite aqui o primeiro número: "))
num2 = float(input("Digite aqui o segundo número: "))

operacao = input("Selecione uma operação (+, -, *, /): ")

if operacao == "+":
    resultado = num1 + num2
    print("O resultado é: ", resultado)

elif operacao == "-":
    resultado = num1 - num2
    print("O resultado é: ", resultado)

elif operacao == "*":
    resultado = num1 * num2
    print("O resultado é: ", resultado)

elif operacao == "/":
    resultado = num1 / num2
    print("O resultado é: ", resultado)

else:
    print("Operação inválida.")
