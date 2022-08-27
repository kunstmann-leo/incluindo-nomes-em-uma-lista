# incluindo-nomes-em-uma-lista
incluindo nomes em lista

nomes = ['Pedro', 'João', 'Leticia']

resp="S"

while resp == "S":

    outrosNomes=input("digite um nome ")
    
    nomes.extend([outrosNomes])
    
    resp=input("digite s para continuar: ").upper()

print(nomes)

#nomes[len(nomes):] = outrosNomes
