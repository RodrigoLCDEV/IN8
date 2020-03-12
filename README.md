# Array
uf =['ES', 'MG', 'RJ', 'SP', 'MT']
estado =['Mato Grosso', 'São Paulo', 'Rio de Janeiro', 'Minas Gerais', 'Espírito Santo']
Nova_Lista = []
cont = -1

for i in range(len(estado)):    
    A = uf[i]+' '+'=>'+' '+estado[cont]
    Nova_Lista.append(A)
    cont  = cont - 1  

for key in range(len(Nova_Lista)):
    print (Nova_Lista[key]," - %i "%key)
