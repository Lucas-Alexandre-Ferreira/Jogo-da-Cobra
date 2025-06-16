# Snake Game

Este é um projeto simples de um jogo da cobrinha (Snake Game) desenvolvido com HTML, CSS e JavaScript. O objetivo do jogo é controlar a cobrinha para comer a comida que aparece na tela, fazendo-a crescer. O jogo termina se a cobrinha colidir com as bordas da tela ou com seu próprio corpo.

## Tecnologias Utilizadas

* **HTML**: Estrutura e conteúdo da página web.
* **CSS**: Estilização e layout do jogo.
* **JavaScript**: Lógica do jogo, interatividade e manipulação do DOM.

## Como Jogar

1.  Clone ou faça o download deste repositório.
2.  Abra o arquivo `index.html` no seu navegador web.
3.  Use as **setas do teclado** (Cima, Baixo, Esquerda, Direita) para controlar a direção da cobrinha.
4.  Coma a comida (quadrado colorido) para aumentar o tamanho da cobrinha e ganhar pontos.
5.  Evite colidir com as bordas da tela ou com o corpo da cobrinha.
6.  Ao colidir, a tela de "Game Over" será exibida, mostrando sua pontuação final.
7.  Clique no botão "Jogar novamente" para reiniciar o jogo.

## Estrutura do Projeto

* `index.html`: Arquivo principal HTML que define a estrutura da página, incluindo o canvas para o jogo, o placar e a tela de game over.
* `css/style.css`: Arquivo CSS responsável por toda a estilização do jogo, garantindo um visual agradável.
* `js/script.js`: Arquivo JavaScript que contém toda a lógica do jogo, como o movimento da cobrinha, a geração da comida, a detecção de colisões, o gerenciamento do placar e o controle da tela de game over.
* `assets/audio.mp3`: Um arquivo de áudio reproduzido quando a cobrinha come a comida.

## Funcionalidades

* **Movimentação da Cobrinha**: Controlada pelas setas do teclado.
* **Crescimento da Cobrinha**: A cobrinha aumenta de tamanho ao comer a comida.
* **Geração Aleatória de Comida**: A comida aparece em posições e cores aleatórias na tela.
* **Placar**: Exibe a pontuação atual do jogador.
* **Detecção de Colisões**: Verifica colisões com as bordas da tela e com o próprio corpo da cobrinha.
* **Tela de Game Over**: Exibida ao final do jogo, mostrando a pontuação final.
* **Reiniciar Jogo**: Opção para iniciar uma nova partida após o "Game Over".
