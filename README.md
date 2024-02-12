# Recebendo o nome e a quantidade de experiência do herói (XP)
nome_heroi = input("Digite o nome do herói: ")
xp_heroi = int(input("Digite a quantidade de experiência do herói (XP): "))

# Utilizando uma estrutura de decisão para determinar a categoria do herói com base na quantidade de XP
if xp_heroi < 1000:
    categoria = "Ferro"
elif 1001 <= xp_heroi <= 2000:
    categoria = "Bronze"
elif 2001 <= xp_heroi <= 5000:
    categoria = "Prata ouro"
elif 5001 <= xp_heroi <= 8000:
    categoria = "Platina diamante"
elif 8001 <= xp_heroi <= 9000:
    categoria = "Ascendente"
elif 9001 <= xp_heroi <= 10000:
    categoria = "Imortal"
else:
    categoria = "Radiante"

# Exibindo a mensagem com a categoria do herói
print(f"O herói {nome_heroi} é da categoria {categoria}.")
