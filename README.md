# Exercicios_modulo1.python

Realização do primeiro módulo do curso de Python da EBAC

Exercícios

 1.Google Colab
  
  Crie uma célula de código que escreva o texto "Olá mundo!", utilize o comando print .

R:  print('Olá mundo')

2.Números

  Preencha as células de código para preencher os valores de (A), (B) e (C) na tabela de ticket
médio abaixo:

  Dia    Valor Total Vendas    Qtd Total Vendas   Ticket Medio
  19/01        (A)                    3             320.52
  20/01      834.47                  (B)            119.21
  23/01     15378.12                  5               (C)

sqv_19 = 3
tikt_19 = 320.52

    svv_19 = sqv_19 * tikt_19
    questao_a = f'(A) {svv_19}'
    print(questao_a)
'(A)961.56'

    svv_20 = 834.47
    tikt_20 = 119.21
    
    sqv_20 = int(svv_20/tikt_20)
    questao_b = f'(B) {sqv_20}'
    print(questao_b)
'(B)6'

    svv_23 = 15378.12
    sqv_23 = 5
    
    tikt_23 = svv_23/sqv_23
    questao_c = f'(B) {tikt_23}
    print(questao_c)
'(C) 3075.6240000000003'

3. Strings

Aplique três métodos distintos na string abaixo, você pode conferir alguns métodos neste link:

cancao = 'Roda mundo, roda gigante, roda moinho, roda pião.'

    posicao = cancao.find('gigante')
    print(posicao)
'17'

     final_cancao = cancao[posicao+9:len(cancao)]
     print(final_cancao)
'roda moinho, roda pião.'

      abreviacao = cancao.replace('gigante','gg')
      print(abreviacao)
 'Roda mundo, roda gg, roda moinho, roda pião'

Extraia da string abaixo o valor da taxa selic na variável selic e o valor do ano na variavel
ano . Imprima os valores na tela.

noticia = 'Selic vai a 2,75% e supera expectativas; é a primeira alta em 6 anos.'

      taxa_selic = noticia[12:17]
      print(str(taxa_selic))
 '2,75%'
 
      valor_do_ano= noticia[-7:-1]
      print(valor_do_ano)
 '6 anos'

4. Booleanos

Utilize a tabela da verdade para responder: qual o valor da variável x?
  a = False
  b = True
  x = not a & b
  
    print(x)
'TRUE'
