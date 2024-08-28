# Leitor de Matriz 2x3

Este projeto é um script em Python que solicita ao usuário valores para preencher uma matriz 2x3 e, em seguida, exibe a matriz preenchida.

## Objetivo

O objetivo deste projeto é criar um script que:
1. Solicite ao usuário a entrada de valores para uma matriz 2x3.
2. Armazene os valores em uma lista de listas (matriz).
3. Exiba a matriz formatada na tela.

## Código

O código funciona da seguinte maneira:
1. Inicializa uma lista vazia para armazenar a matriz.
2. Utiliza dois loops `for` para ler valores e preencher a matriz 2x3.
3. Exibe a matriz linha por linha.

```python
# Inicialização da matriz
matriz = []

# leitura dos valores para uma matriz 2x3
for i in range(2):
    linha = []
    for j in range(3):
        valor = float(input(f"Digite o valor para posição ({i+1},{j+1}): "))
        linha.append(valor)
    matriz.append(linha)

# exibição da matriz
print("Matriz digitada:")
for linha in matriz:
    print(linha)
Como Executar
1. Certifique-se de ter o Python instalado em seu sistema.

2. Salve o código acima em um arquivo chamado leitor_matriz.py.

3. Execute o código usando o seguinte comando:
python leitor_matriz.py
4. Insira os valores quando solicitado e veja a matriz exibida.

Contribuição
Sinta-se à vontade para fazer sugestões ou melhorias. Se encontrar um problema ou tiver uma ideia para aprimorar o projeto, por favor, abra uma issue ou envie um pull request.

Licença
Este projeto está licenciado sob a Licença MIT - veja o arquivo LICENSE para mais detalhes.
