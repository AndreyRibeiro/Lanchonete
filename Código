print('Seja bem-vindo a lanchonete do Andrey Grigoletto')
print('*******************Cardápio******************')
print('|   Código  |        Descrição      | Valor |')
print('|    100    |    Cachorro Quente    |  9,00 |')
print('|    101    | Cachorro Quente Duplo | 11,00 |')
print('|    102    |          X-Egg        | 12,00 |')
print('|    103    |         X-Salada      | 12,00 |')
print('|    104    |          X-Bacon      | 14,00 |')
print('|    105    |          X-Tudo       | 17,00 |')
print('|    200    |    Refrigerante Lata  |  5,00 |')
print('|    201    |       Chá Gelado      |  4,00 |')
acumulador = 0
while True: #While true após o cardápio para não ficar repetindo o cardápio para o cliente
    codigo = input('Entre com o código desejado: ')
    if codigo == "100":
        acumulador += 9
        precoAtual = 9
        produtoAtual = "Cachorro Quente" # Fiz uma variável para o preço atual e para o nome do produto para retornar o que está sendo pedido e o valor para o cliente
    elif codigo == "101":
        acumulador += 11
        precoAtual = 11
        produtoAtual = "Cachorro Quente Duplo"
    elif codigo == "102":
        acumulador += 12
        precoAtual = 12
        produtoAtual = "X-Egg"
    elif codigo == "103":
        acumulador += 12
        precoAtual = 12
        produtoAtual = "X-Salada"
    elif codigo == "104":
        acumulador += 14
        precoAtual = 14
        produtoAtual = "X-Bacon"
    elif codigo == "105":
        acumulador += 17
        precoAtual = 17
        produtoAtual = "X-Tudo"
    elif codigo == "200":
        acumulador += 5
        precoAtual = 5
        produtoAtual = "Refrigerante Lata"
    elif codigo == "201":
        acumulador += 4
        precoAtual = 4
        produtoAtual = "Chá Gelado"
    else:
        print("Opção inválida") #Caso o cliente insira um código errado
        continue
    print(f"Você pediu um {produtoAtual} no valor de: R$ {precoAtual:.2f}") #Produto e valor do produto inserido
    outroPedido = input("Deseja pedir mais alguma coisa? "  "\n 1 - Sim" "\n 0 - Não ") 
    if outroPedido == "1":
        continue
    else:
        print('O valor final da conta é: R$ {:.2f}' .format(acumulador)) #Valor final a ser pago com todos os produtos escolhidos
        break
