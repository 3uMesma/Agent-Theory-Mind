Este projeto investiga a interação humano-agente no jogo "Bluff", utilizando dois modelos distintos de agentes: um agente de zero-ordem, que baseia suas decisões unicamente em variáveis ambientais, e um agente de primeira-ordem, que antecipa o comportamento do oponente com base em ações passadas. Através de experimentos, foi observado que o agente de primeira-ordem apresentou um desempenho superior em comparação ao agente de zero-ordem, resultando em partidas mais longas, dinâmicas e variadas em termos de bluffs e ações de dúvida.

Os resultados indicam que a estratégia de jogar honestamente é mais eficaz contra o agente de primeira-ordem, já que este tende a ser mais suspeito das tentativas de bluff. O relatório completo da pesquisa, incluindo análises detalhadas e dados experimentais, está disponível no repositório.

# Regras do jogo Bluff
O "Bluff" é jogado com as cartas de um baralho padrão. Ou seja, é jogado com quatro de cada um dos ases, valetes, rainhas e reis. As cartas são distribuídas entre os jogadores, de modo que cada jogador tenha o mesmo número de cartas. As cartas excedentes são descartadas viradas para baixo em uma pilha central.

O jogo começa com ases. O jogador inicial seleciona qualquer número de suas próprias cartas para jogar viradas para baixo na pilha central, com a alegação implícita de que todas são ases. Os jogadores se revezam jogando cartas ou desafiando a jogada mais recente. O jogador que não tiver cartas no início de sua vez vence o jogo. Se um jogador escolher desafiar a jogada mais recente, ele vira as cartas correspondentes. Se não forem todas ases, o jogador que jogou as cartas deve pegar todas as cartas da pilha central em sua mão. No entanto, se forem todas ases, o jogador desafiador deve pegar todas as cartas da pilha central em sua própria mão. Em ambos os casos, o próximo jogador começa um novo jogo com o próximo
rank de cartas, indo de Ases, para Valetes, para Rainhas e, finalmente, para Reis.

Um agente de teoria da mente de ordem zero só pode raciocinar sobre características observáveis ​​do jogo. Ou seja, eles podem raciocinar sobre as cartas que estão segurando, comportamento desafiador passado de seu oponente e comportamento de blefe passado de seu oponente. Observe que em um jogo de dois jogadores, qualquer
carta que não esteja em posse do jogador no início do jogo deve estar em posse de seu oponente.

Um agente de teoria da mente de primeira ordem pode se colocar na posição de seu oponente e tentar adivinhar quais cartas seu oponente jogou na rodada anterior (teoria interpretativa da mente) e determinar como seu oponente reagirá às suas jogadas, dada sua história compartilhada (teoria preditiva da mente).
