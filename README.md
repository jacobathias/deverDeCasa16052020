# deverDeCasa16052020

Depois de assistir, tenta fazer o seguinte:

a) criar 1 classe principal  chamada personagem com nome, vida, vida_atual (==vida) e ataque;
b) criar na classe personagem, 2 funções: Atacar e receberDano, o ataque enviará o dano na requisição da função receberDano do alvo passado por parametro ao ataque. A função receberDano que fará a subtração do dano aplicado em parametro ao objeto determinado no ataque.
   Ex: fora da classe podemos a qualquer momento chamar a função ataque como a seguir:    jogador.atacar(montro)   ou monstro.atacar(jogador)
   Ex: dentro da função ataque {  monstro.receberDano(20)  }
c) criar 2 objetos do tipo personagem, um jogador e o outro monstro, cada um com seus dados diferentes passados no construtor;
d) simular uma batalha dos dois objetos e checar a vida_atual de cada um deles para confirmar a subtração;

BONUS
1) Melhorar o sistema criando uma batalha real até a morte de forma dinamica, checando vida e determinando a vitória automaticamente em Loop até o final da batalha.
2) Criar Eventos e Interface html para o jogo, não necessitando de loop e definição completa da batalha, tornando interativo e jogavel. Usando botões de ataque por exemplo.
