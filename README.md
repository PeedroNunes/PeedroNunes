while (True) :
    v = float(input('Qual o Valor da Venda : '))
    c = int(input('Qual a Porcentagem da comissão : '))
    e = v * c / 100
    print('O valor da Venda é {:.2f}, é a comissão da venda séra {:.2f}'.format(v,e))
