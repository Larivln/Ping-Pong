Jogo Ping Pong com HTML5 e JavaScript
Este é um simples jogo de Ping Pong desenvolvido com HTML5 e JavaScript, utilizando o elemento canvas para renderizar a interface gráfica. O jogo simula um clássico pong, com a bola se movendo de um lado para o outro e raquetes controladas automaticamente pela inteligência artificial ou pelo usuário.

Funcionalidades
Jogo interativo usando o canvas.
Controle de uma das raquetes com o movimento do mouse.
A outra raquete é controlada automaticamente pela IA, que segue a bola.
A bola aumenta gradualmente a velocidade até um limite máximo (20).
O placar é atualizado conforme a bola ultrapassa as raquetes.
As raquetes são limitadas para não sair dos limites da tela.
Como funciona
A raquete esquerda é controlada pelo usuário movendo o mouse verticalmente.
A raquete direita é controlada pela IA, que segue a posição da bola.
A bola rebate nas raquetes e nas bordas superiores/inferiores do campo.
Pontos são contados quando a bola ultrapassa uma das raquetes.
O jogo reinicia a cada ponto, com a bola voltando ao centro e aumentando a velocidade (até um máximo de 20).
A velocidade inicial da bola é 5, e aumenta em 2 pontos a cada vez que a bola cruza uma raquete.
Requisitos
Nenhuma instalação de software adicional é necessária para rodar o jogo, basta um navegador moderno que suporte HTML5 e JavaScript.

Como jogar
Clone ou baixe este repositório.
Abra o arquivo index.html diretamente no navegador.
Use o mouse para controlar a raquete esquerda.
A raquete direita é controlada automaticamente pela IA.
A cada vez que a bola ultrapassar uma raquete, o placar é atualizado.
Estrutura do Código
canvasEl: O elemento canvas onde todo o jogo é desenhado.
leftPaddle e rightPaddle: Representam as raquetes controladas pelo jogador e pela IA, respectivamente.
ball: O objeto bola, que se move de um lado para o outro e rebate nas raquetes e nas bordas do campo.
score: Gerencia a pontuação dos jogadores.
field: Representa o campo de jogo.
animate: Função responsável por desenhar e atualizar o estado do jogo constantemente.
Personalizações
Se você quiser modificar o jogo, você pode:

Mudar o tamanho do campo: Altere os valores de field.w e field.h para modificar a largura e altura do campo.
Alterar a velocidade da bola: Mude o valor inicial de ball.speed para aumentar ou diminuir a velocidade inicial da bola.
Mudar o limite de velocidade da bola: Ajuste ball.maxSpeed para definir o valor máximo que a velocidade da bola pode alcançar.
Alterar o tamanho das raquetes: Ajuste os valores de leftPaddle.h e rightPaddle.h para mudar a altura das raquetes.
Melhoria Futuras
Adicionar sons ao jogo, como o som de rebote da bola nas raquetes ou quando um ponto é marcado.
Criar um modo multiplayer onde dois jogadores podem controlar as duas raquetes (esquerda e direita).
Implementar uma interface gráfica de início e fim de jogo, com opções para reiniciar a partida.
Tecnologias Utilizadas
HTML5: Estrutura da página.
CSS: Estilização básica da página e do jogo.
JavaScript: Lógica de jogo, movimento da bola, controle das raquetes e atualização do placar.
Contribuindo
Se você quiser contribuir com o projeto, sinta-se à vontade para abrir uma pull request ou issue.