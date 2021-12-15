# Apresentação Rpg programmer teste 1 

from time import sleep
print(' Seja bem vindo!!')
nome = str(input(' Qual é seu nome? '))
print(' Prazer em te conhecer {} '.format(nome))
sleep(1)
hist = str(input(' Você gosta de histórias? ')).lower()
if hist == 'Sim'.lower():
    print(' Otímo, Vou te contar uma história ok? Nessa hístória vou permitir você fazer algumas escolhas '
          'e as suas escolas fará o traçar um caminho só seu, OK? ')
if hist == 'Não'.lower() or hist == 'nao'.lower():
    print(' Sério, tenho um ótima hístória que gostaria de contar para você, vou até permitir que você faça mudanças '
          'na história, mudanças que fará você traçar um caminho só seu, OK? ')

sleep(2)
print(' Então valos lá')

indole = str(input(' Só para começar deixe eu imaginar se apartir de hoje você pudesse mudar seu deustino'
                   'você seria cruel ou bom? '))
                   
                   
