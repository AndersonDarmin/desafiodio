# desafiodio
nome_heroi = "Guerreiro"

xp_heroi = 10001

if xp_heroi < 1000:
  nivel = "ferro"
elif 1001 <= xp_heroi <= 2000:
  nivel ="bronse"
elif 2001 <= xp_heroi <= 5000:
  nivel ="Prata "
elif 5001 <= xp_heroi <= 7000:
  nivel = "Ouro"
elif 7001 <= xp_heroi <= 8000:
  nivel = "Platina"
elif 8001 <= xp_heroi <= 9000:
  nivel = "Ascendente"
elif 9001 <= xp_heroi <= 10000:
  nivel = "Imortal"
else:
  nivel = "Radiante" 

print(f"O heroi de nome {nome_heroi} está no nivel {nivel}")
