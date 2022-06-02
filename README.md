# Projeto-Final-de-Reinforcement-Learning
Repositório para o projeto final da matéria reinforcement learning


## Caso de uso 1 - Robo Trader

Ambiente: Ambiente do gym trading que possibilita o treinamento do agenda usando dados históricos
Referência: https://github.com/hackthemarket/gym-trading

Agente: O agente é um robo trader que pode entrar comprado ou vendido em uma dada ação, bem como finalizar sua posição quando julgar adequado. O agente deve analisar um conjunto de ações, nesse caso escolheria as ações que compoem o índice S&P 500, e escolher qual ou quais ações vai operar. Sendo que a operação pode ser: Comprar, entrar vendido(short) e encerrar uma posição existente. O agente pode encerrar parcialmente a posição ou aumentar, para rebalancear as alocações de acordo com informações mais recentes.

Recompensas: As recompensas do agente estão ligadas à precisão e rentabilidade dele. Ou seja, a recompensa para o agente seria uma ponderação entre o quanto um dado "padrão" de estratégia acerta(precisão) e qual a rentabilidade que ele gera quando acerta. 

Trabalhos correlatos e escolhe de reinforcement learning: Existem diversas implementações de Robo traders das mais simples às mais complexas. Acredito que a abordagem de reinforcement learning pode funcionar bem aqui já que hoje temos um número gigantesco de dados passados e presentes sendo gerados a todo o momento sobre o mercado financeiro. 

## Caso de uso 2 - 

Ambiente
