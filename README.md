# Projeto-Final-de-Reinforcement-Learning
Repositório para o projeto final da matéria reinforcement learning


## Caso de uso 1 - Robo Trader

**Ambiente:** Ambiente do gym trading que possibilita o treinamento do agenda usando dados históricos.
*Referência: https://github.com/hackthemarket/gym-trading*

**Agente:** O agente é um robo trader que pode entrar comprado ou vendido em uma dada ação, bem como finalizar sua posição quando julgar adequado. O agente deve analisar um conjunto de ações, nesse caso escolheria as ações que compoem o índice S&P 500, e escolher qual ou quais ações vai operar. Sendo que a operação pode ser: Comprar, entrar vendido(short) e encerrar uma posição existente. O agente pode encerrar parcialmente a posição ou aumentar, para rebalancear as alocações de acordo com informações mais recentes.

**Recompensas:** As recompensas do agente estão ligadas à precisão e rentabilidade dele. Ou seja, a recompensa para o agente seria uma ponderação entre o quanto um dado "padrão" de estratégia acerta(precisão) e qual a rentabilidade que ele gera quando acerta. 

**Trabalhos correlatos e escolha de reinforcement learning:** Existem diversas implementações de Robo traders das mais simples às mais complexas. Acredito que a abordagem de reinforcement learning pode funcionar bem aqui já que hoje temos um número gigantesco de dados passados e presentes sendo gerados a todo o momento sobre o mercado financeiro. 

## Caso de uso 2 - Bank Heist 

**Ambiente:** O ambiente do gym possuí uma biblioteca de jogos do Atari. Nesse caso o jogo em questão é Bank Heist, uma cidade com bancos e caminhos onde um carro(agente) pode andar e ser perseguido por policiais após roubar os bancos. No início do jogo o agente(carro de fuga) começa com 4 vidas, perdendo uma cada vez que é pego pelo carro de polícia, fica sem gasolina ou passa na própria dinamite. O objetivo é o carrao roubar todos os bancos da cidade e destruir o máximo de carros de polícia e ir para uma próxima sem ser pego. Ao chegar na nova cidade o carro é reabastecido.
*Referência:https://www.gymlibrary.ml/environments/atari/bank_heist/*

**Agente:** O agente é um carro que pode andar pela cidade(2D) podendo virar a direita ou esquerda e ir reto. Quando o carro passa por cima de um banco, ele rouba esse banco e um carro de polícia vai começar a persegui-lo. O agente deve fugir do carro de polícia e pode destrui-lo deixando uma dinamite para trás. 

**Recompensas:** As recompensas do agente são dadas pelo própio ambiente. Sendo que elas estão ligadas à quantidade de bancos que rouba e carros de polícia que destroi. 

**Trabalhos correlatos e escolha de reinforcement learning:** Existem outras soluções para jogar esse jogo de forma otimizada, mas eu acredito que reinforcement learning é uma boa opção pela facilidade, o jogo é simples e não leva muito tempo para o agente aprender a jogar. Por outro lado fazer um programa "vanilla" para jogar esse jogo não seria tão trivial. 

## Caso de uso 3 - Asteroids

**Ambiente:** O ambiente do gym possuí a biblioteca de jogos do Atari. Nesse caso o jogo em questão é Asteroids, o ambiente é composto por um campo de asteróides que se movem. A nave (agente) deve destruir todos os asteroides atirando neles e evitar colidir com os mesmos. Ao destruir todos os asteróides, inicia-se um novo nível e aparecerão novos asteróides.  

**Agente:** O agente é uma nave, ela pode se mover em todas as direções, rotacionar e atirar, destruindo os asteroides. Quando ele é atingido por um asteroide o agente perde uma vida. 

**Recompensas:** As recompensas do agente são dadas pelos asteroides que ele destroi, quanto menor, mais pontos. Conforme ele vai sobrevivendo(evitando colisões) e passando de fase, ele vai pontuando mais. 

**Trabalhos correlatos e escolha de reinforcement learning:** Existem outras soluções para jogar esse jogo de forma otimizada, mas eu acredito que reinforcement learning é uma boa opção pela facilidade, o jogo é simples e não leva muito tempo para o agente aprender a jogar. Por outro lado fazer um programa "vanilla" para jogar esse jogo não seria tão trivial. 

## Escolha de implementação:

Escolhi o 
