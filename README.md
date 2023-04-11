# Jogo de Tetris

Esta é uma implementação do clássico jogo do Tetris em JavaScript. O jogo utiliza uma grade 10x20 e apresenta cinco formas diferentes de Tetromino: L, Z, T, O e I. O jogo começa com uma forma de Tetromino aleatória que cai pela grade. O jogador pode mover a forma para a esquerda ou para a direita, girá-la ou acelerar a queda. Quando uma linha é completamente preenchida com formas de Tetromino, ela é eliminada e o jogador ganha pontos. O jogo termina quando as formas de Tetromino atingem o topo da grade.

![](https://github.com/lfanjos/tetris-js/blob/master/tetris.gif)

## Como Jogar

Para iniciar o jogo, clique no botão "Iniciar/Pausar". O jogo começará com uma forma de Tetromino aleatória caindo pela grade. O jogador pode mover a forma para a esquerda ou para a direita usando as setas esquerda e direita do teclado. A seta para cima pode ser usada para girar a forma. A seta para baixo pode ser usada para acelerar a queda da forma. Quando uma linha é completamente preenchida com formas de Tetromino, ela é eliminada e o jogador ganha pontos. O jogo termina quando as formas de Tetromino atingem o topo da grade.

## Visão Geral do Código

O jogo é implementado usando HTML, CSS e JavaScript. A lógica do jogo está contida no arquivo JavaScript.

O jogo usa uma grade 10x20 para representar a área jogável. A grade é composta por 200 células individuais, cada uma representada por um elemento `div`. A forma atual de Tetromino também é representada como uma matriz de índices dentro da matriz da grade. O jogo usa o método `setInterval` para mover a forma de Tetromino pela grade em um intervalo fixo.

O jogo usa Event Listeners para receber a entrada do usuário pelo teclado. O jogador pode mover a forma de Tetromino para a esquerda ou para a direita usando as setas esquerda e direita, girar a forma usando a seta para cima e acelerar a queda da forma usando a seta para baixo.

Quando uma linha é completamente preenchida com formas de Tetromino, ela é eliminada e o jogador ganha pontos. A pontuação do jogador é exibida na tela. O jogo termina quando as formas de Tetromino atingem o topo da grade.

## Começando

Para executar o jogo, basta abrir o arquivo `index.html` em um navegador da web. O jogo deve começar automaticamente. Use as setas do teclado para controlar o movimento das formas de Tetromino.

## Melhorias Futuras

Algumas melhorias futuras que podem ser feitas neste projeto incluem:

- Adicionar efeitos sonoros e música ao jogo para melhorar a experiência do jogador.
- Adicionar uma tabela de pontuação alta ao jogo para permitir que os jogadores compitam pela maior pontuação.
