1. Endereço do Repositório no GitHub
https://github.com/Silvairv/Game-JS

2. Checklist do Desenvolvimento do Jogo
Definição do Tema
O tema do jogo é "sobrevivência e esquiva". Inspirado no jogo do dinossauro do Google e na movimentação dinâmica de jogos como Mario, o jogador controla uma nave (ou personagem) que deve desviar de obstáculos enquanto a dificuldade aumenta gradualmente. O objetivo é sobreviver o maior tempo possível e alcançar a maior pontuação.

Planejamento
Etapa 1: Planejamento do Design e Mecânicas 

Definir o tema e a jogabilidade.
Criar uma lista de mecânicas principais (movimentação, obstáculos, pontuação, aumento de dificuldade).

Etapa 2: Desenvolvimento Inicial Implementar a movimentação básica do jogador.
Criar o sistema de geração de obstáculos.
Adicionar detecção de colisão e sistema de pontuação.

Etapa 3: Aprimoramento e Ajustes 
Ajustar a dificuldade dinâmica.
Adicionar movimentação nos obstáculos.
Otimizar o desempenho para diferentes tamanhos de tela.

Etapa 4: Testes e Depuração
Testar diferentes níveis de dificuldade.
Corrigir bugs (como colisões inconsistentes ou obstáculos sobrepostos).

Etapa 5: Documentação e Publicação 
Documentar o código, incluindo comentários claros e um guia do desenvolvedor.
O jogo foi desenvolvido seguindo o plano acima, garantindo que cada etapa fosse concluída antes de passar para a próxima. A implementação foi feita em HTML, CSS e JavaScript puro.

Testes foram realizados para:
Garantir que o jogador se move corretamente com as teclas WASD.
Certificar que os obstáculos aparecem e se movem conforme esperado.
Confirmar que o sistema de pontuação e dificuldade funciona.
Verificar se o jogo termina ao detectar colisões.

Documentação

O código foi documentado com comentários explicativos para cada função, além de incluir um guia breve sobre o funcionamento do jogo e suas mecânicas.

3. Tecnologias Utilizadas
Linguagens de Programação:
HTML5 (estrutura do jogo).
CSS3 (estilização básica).
JavaScript (lógica do jogo, movimentação, obstáculos, pontuação).
Ferramentas:
Navegador Web (para testes).
(VS Code).

API de Canvas:
Utilizada para desenhar o jogador, os obstáculos e exibir o jogo em tempo real.
4. Identificação da Complexidade do Jogo

Análise da Complexidade
Movimentação do jogador:
Simples, implementada com eventos de teclado para detectar as teclas WASD.

Geração e movimentação de obstáculos:
Obstáculos são gerados aleatoriamente com tamanho, velocidade e movimento variável. O algoritmo utiliza lógica condicional para ajustar a direção e a velocidade dos obstáculos móveis.

Detecção de colisão:
Verifica se o retângulo do jogador intercepta o retângulo de qualquer obstáculo.

Aumento de dificuldade:
Implementado de forma dinâmica com base na pontuação, ajustando a velocidade dos obstáculos e a frequência de geração.

Gestão da Complexidade
O jogo utiliza estruturas simples (como arrays para obstáculos e eventos para movimentação) para garantir que a execução seja eficiente.
A dificuldade foi ajustada gradualmente para manter o jogo desafiador, mas não impossível.

5. Regras (Jogabilidade)
Regras do Jogo
O jogador deve usar as teclas W, A, S, D para se mover.
O objetivo é desviar de obstáculos que se movem horizontalmente pela tela.
A pontuação aumenta com o tempo e a dificuldade aumenta gradualmente.
O jogo termina quando o jogador colide com um obstáculo.

Instruções para o Jogador
Pressione W para mover para cima, S para baixo, A para esquerda e D para direita.
Evite os obstáculos vermelhos que aparecem na tela.
Continue jogando para alcançar a maior pontuação possível.
Se você colidir com um obstáculo, o jogo termina e sua pontuação final será exibida.

5.Demo do Jogo por Vídeo


