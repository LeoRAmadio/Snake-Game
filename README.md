# 🐍 Snake Game em Python
Este é um jogo da cobrinha (Snake Game) desenvolvido em Python, utilizando a biblioteca Turtle para a interface gráfica. O objetivo do jogo é controlar a cobra, coletar alimentos e crescer o máximo possível sem colidir com as paredes ou com o próprio corpo.

## 🚀 Como funciona?
- O jogador controla a cobra usando as teclas WASD.
- O objetivo é comer os alimentos que aparecem aleatoriamente na tela.
- Cada vez que a cobra come um alimento, ela cresce e a pontuação aumenta.
- Se a cobra colidir com a parede ou com o próprio corpo, o jogo termina.

## 📌 Estrutura do código
O projeto está organizado em quatro classes principais:

### Snake 🐍

- Controla os movimentos da cobra.  
- Adiciona novos segmentos ao corpo quando a cobra cresce.
- Verifica a direção para evitar movimentos inválidos.
  
### Food 🍎

- Gera alimentos em posições aleatórias na tela.
- Atualiza a posição sempre que a cobra come um alimento.

### Scoreboard 🏆

- Exibe a pontuação do jogador.
- Atualiza a pontuação ao coletar alimentos.
- Mostra "GAME OVER" quando o jogador perde.

### Main 🎮

- Controla a lógica principal do jogo.
- Detecta colisões com a parede e com o próprio corpo.
- Controla a entrada do usuário para movimentação.

## 🛠 Tecnologias utilizadas
- Python
- Biblioteca Turtle (para renderização gráfica)
- Biblioteca Random (para posicionamento aleatório dos alimentos)
- Manipulação de classes e objetos
