# Implementação de Árvore B

Este repositório contém a implementação de uma árvore B em linguagem C, um tipo de estrutura de dados balanceada utilizada em sistemas de bancos de dados e sistemas de arquivos para manter dados ordenados e permitir operações de busca, inserção e deleção em tempo eficiente.

## Estrutura do Projeto

- **main.c**: Contém a função principal onde são realizadas operações de inserção e busca na árvore B.
- **f_af.h**: Arquivo de cabeçalho que inclui as definições e protótipos das funções utilizadas para manipulação da árvore B.

## Funcionalidades

- **Inserção**: Adiciona novas chaves na árvore, mantendo-a balanceada.
- **Busca**: Permite a busca de chaves específicas na árvore.
- **Divisão de Nós**: Gerencia a divisão de nós quando eles ficam cheios, garantindo a estrutura balanceada da árvore.

## Como Executar

1. Clone o repositório:
    ```bash
    git clone https://github.com/seu-usuario/nome-do-repositorio.git
    ```
2. Compile o código:
    ```bash
    gcc -o arvoreB main.c
    ```
3. Execute o programa:
    ```bash
    ./arvoreB
    ```
