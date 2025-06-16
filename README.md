🎮 Objetivo do Jogo
Levar a comida até a cidade, evitando colidir com os obstáculos no caminho. A cada obstáculo desviado, o jogador ganha pontos. O jogo termina se o caminhão bater em algum obstáculo.

⚙️ Como Funciona o Jogo
O caminhão começa do lado esquerdo da tela e a cidade está do lado direito.

Obstáculos aparecem do lado direito e se movem para a esquerda.

O jogador deve mover o caminhão para cima ou para baixo com as setas do teclado (↑ e ↓) para desviar.

Se o caminhão colidir com um obstáculo, o jogo exibe a mensagem “Fim de jogo” e mostra a pontuação final.

🔁 Lógica do Jogo (em resumo)
A cada ciclo (draw), o jogo atualiza a posição dos elementos (caminhão e obstáculos).

A cada 90 frames, um novo obstáculo é gerado.

A colisão entre o caminhão e os obstáculos é verificada com base na sobreposição de retângulos.

Se o obstáculo sair da tela e não colidir com o caminhão, o jogador ganha +1 ponto.

A cidade é apenas visual, representando o destino, mas não interage com o caminhão.

🎨 Elementos Visuais
Caminhão: retângulo marrom com comida branca em cima.

Obstáculos: retângulos vermelhos simulando barreiras ou buracos.

Cidade: retângulo verde com o texto “Cidade” à direita da tela.

Pontuação: aparece no canto superior esquerdo da tela.
