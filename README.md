# mini_ calculadora em python

valor1 =int(input("Digite o valor do primeiro número :"))
valor2 = int(input('Digite o valor do segundo :')) 
operacao = input("Digite o valor da operação")

match operacao:
  case "+":
    res = valor1 + valor2

  case "-": 
    res = valor1 - valor2

  case "*" :
    res = valor1 * valor2

  case "/":
    res = valor1 / valor2
      
    print("Seu resultado é{res}")
