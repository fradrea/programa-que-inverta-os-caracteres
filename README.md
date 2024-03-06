# programa-que-inverta-os-caracteres
 Escreva um programa que inverta os caracteres de um string.  
 IMPORTANTE: 
 a) Essa string pode ser informada através de qualquer entrada de sua preferência ou pode ser previamente definida no código; 
 b) Evite usar funções prontas, como, por exemplo, reverse;

def inverte_string(string):
    tamanho = len(string)
    string_invertida = ''
    for i in range(tamanho - 1, -1, -1):
        string_invertida += string[i]
    return string_invertida

# String a ser invertida
string_original = input("Digite a string que deseja inverter: ")

# Inverte a string e imprime o resultado
string_invertida = inverte_string(string_original)
print("String invertida:", string_invertida)

