#A ideia é criar um analisador básico de nomes, primeiro nome, nome do meio, último nome, quantidade de letras, letra que mais se repete, etc

#INTRODUÇÃO
print ('Olá usuário! Seja muito bem-vindo ao analisador de nomes! \nAqui faremos uma análise básica do seu nome apenas por diversão! \nPara darmos início por favor')
nome = str (input('Digite seu nome completo:')).strip().title()
partes = nome.split()

#VARIÁVEIS
primeiro_nome = partes[0]
nome_meio = " ".join(partes[1:-1])
ultimo_nome = partes[-1]
quant_letras = len(nome.replace(" ",""))

#RESULTADOS
print (f'Seu nome completo é {nome}.')
if nome_meio:
    print (f'Seu nome do meio é {nome_meio}.')
else:
    print ('Seu nome não possui nome do meio.')
print (f'Seu último nome é {ultimo_nome}.')
print (f'Seu nome possui {quant_letras} letras.')
