Este projeto é uma demonstração simples de olhos animados que seguem o movimento do mouse pela tela, utilizando HTML, CSS e JavaScript.

Funcionalidades
Olhos Animados: Os elementos de classe "olho" giram conforme o movimento do cursor do mouse, criando a ilusão de que estão seguindo o ponteiro.
Como Funciona
Captura da Posição do Mouse:

O script detecta a posição atual do cursor do mouse na tela (coordenadas X e Y) através do evento mousemove.
Cálculo do Ângulo de Rotação:

O ângulo de rotação dos olhos é calculado utilizando a função Math.atan2, que determina o ângulo entre o eixo X e a linha que conecta o centro do olho à posição do cursor.
Aplicação da Rotação:

A rotação é aplicada a todos os elementos com a classe "olho" usando CSS transform (rotate), fazendo com que os olhos "sigam" o cursor do mouse.
