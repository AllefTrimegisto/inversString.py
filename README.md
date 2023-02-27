# inversString.py

 
5) Escreva um programa que inverta os caracteres de um string.

IMPORTANTE:
	a) Essa string pode ser informada através de qualquer entrada de sua preferência ou pode ser previamente definida no código;
	b) Evite usar funções prontas, como, por exemplo, reverse;
  
  # Lê a string de entrada do usuário ou define uma string no código
entrada = input("Digite uma string: ")

# Cria uma lista vazia para armazenar os caracteres da string invertida
invertida = []

# Percorre a string original de trás para frente, adicionando cada caractere encontrado na lista criada
for i in range(len(entrada) - 1, -1, -1):
    invertida.append(entrada[i])

# Junta os caracteres da lista em uma nova string
saida = "".join(invertida)

# Imprime a string invertida
print("A string invertida é:", saida)
