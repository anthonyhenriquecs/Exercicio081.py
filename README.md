# Exercicio081.py

valores = []
while True:
    valores.append(int(input('Digite um valor:')))
    resp = str(input('Quer continuar? [S/N]'))
    if resp in 'Nn':
        break

print('-='*30)
print(f'Foram digitados {len(valores)} elementos')
valores.sort(reverse=True)
print(f'Os valores em ordem decrescentes: {valores}')
if 5 in valores:
    print('O valor 5 esta na lista')
else:
    print('O valor 5 n foi encontrado')
