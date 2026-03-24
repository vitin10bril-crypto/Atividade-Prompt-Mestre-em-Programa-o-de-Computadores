# Atividade – Prompt Mestre em Programação de Computadores

## Tema: Estruturas de Repetição

### Prompt Mestre Inicial

# 1. VOCÊ FALA: "Robô, faz tabuada do 6!"
# 2. ROBÔ RESPONDE 10 VEZES:
#    6 x 1 = 6
#    6 x 2 = 12
#    6 x 3 = 18
#    ...até 6 x 10 = 60

# CÓDIGO DO ROBÔ:
numero = int(input("Digite um número para ver a tabuada: "))  # você fala o número
for i in range(1, 11):  # repete 10 vezes
    print(f"{numero} x {i} = {numero * i}")  # fala resultado

# É como copiar lição, mas o computador faz TUDO!
