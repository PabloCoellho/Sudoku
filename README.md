# Sudoku Game
Este repositório contém um algoritmo para jogar e resolver o Sudoku, desenvolvido como trabalho prático final na disciplina de Introdução a Programação.

### Descrição
Este algoritmo permite que os usuários joguem e resolvam tabuleiros do Sudoku interativamente.

### Como Usar
Para jogar o Sudoku, siga estas etapas:

1. Clone este repositório para o seu ambiente local.

2. Compile os arquivos sudoku.c e funcoes.c usando o seguinte comando:
      gcc sudoku.c funcoes.c -o sudoku
  Isso criará um arquivo executável chamado 'sudoku'.

3. Execute o arquivo 'sudoku':
      ./sudoku

4. O programa solicitará o arquivo de texto que contém o jogo. No repositório, há um exemplo chamado 'jogo.txt'.
No arquivo de texto 'jogo.txt', o tabuleiro é criado com os números correspondentes, e os locais com "0" são os espaços a serem preenchidos durante o jogo.

5. Após indicar o arquivo de texto com o jogo, você pode fazer alterações no tabuleiro. Digite a célula que deseja alterar, seguida pelo valor que deseja adicionar à célula.
Por exemplo, ao digitar "119", o programa acessará a célula na linha 1 e na coluna 1 e adicionará o valor 9.

6. Quando desejar, você pode digitar o comando "salvar" para salvar o tabuleiro atual ou "sair" para encerrar a execução do programa.
