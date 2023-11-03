# Ranking Loader
Um aplicativo que obtem o resultado do torneio diário (todos que jogam o jogo participam desse torneio), o torneio 
fica disponível para ser jogado todos os dias de 00:00 às 21:59 (UTC-0).

## RF (Requisitos funcionais)

- [x] Deve ser possivel exibir resumo rápido do ranking;
- [x] Deve ser possivel exibir o nome dos jogadores;
- [x] Deve ser possivel exibir os heróis que eles usaram no torneio;
- [x] Deve ser possivel exibir sua pontuação final;
- [x] Deve ser possivel na tela mais detalhada, exibir o nome do usuário e sua nacionalidade, os nomes dos heróis e seus níveis, a pontuação final e a data/hora que o jogador atingiu aquela pontuação

## RN (Regras de negócio)
- [x] De 00:00 às 21:59 os jogadores podem conferir o resultado do último torneio;
- [x] De 22:00 às 23:59 essa API não deve retornar nenhum dado (período de suspense antes de anunciar os vencedores);


