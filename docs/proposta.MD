# Proposta Inicial do Jogo

Este documento deve ser preenchido pelo grupo na Semana 1 do projeto.

A proposta deve apresentar uma ideia simples, clara e viável para ser desenvolvida com Python e Pygame dentro do prazo disponível.

## 1. Nome provisório do jogo

Escreva aqui o nome provisório do jogo.

XO Duel

> Corrida dos Obstáculos

## 2. Integrantes do grupo

Liste os integrantes do grupo.

- Nome 1: Brendon Leonardo Martins Alves
- Nome 2: Daniel Eiji Serra Tsuruga
- Nome 3:
- Nome 4:

## 3. Tipo de jogo

Indique o tipo de jogo que será desenvolvido.

Exemplos:

- jogo de desviar de obstáculos;
- jogo de coleta de itens;
- labirinto simples;
- jogo de perguntas e respostas;
- jogo de memória;
- Pong;
- Snake;
- Breakout;
- nave desviando de meteoros;
- corrida simples com obstáculos;
- jogo de clique rápido;
- jogo de sobrevivência simples.

Tipo escolhido pelo grupo: Jogo da Velha 

> Escreva aqui.

## 4. Descrição geral do jogo

Explique, em poucas linhas, como o jogo funcionará.

Procure responder:

- O que aparece na tela?
- O que o jogador controla?
- O que o jogador precisa fazer?
- Quais desafios aparecem durante a partida?

Descrição: O jogo exibirá um tabuleiro 3x3 na tela. Dois jogadores se alternam realizando jogadas, marcando os símbolos X e O nas casas disponíveis. O objetivo é formar uma linha, coluna ou diagonal com três símbolos iguais antes do adversário.

> Escreva aqui.

## 5. Objetivo do jogador

Explique qual é o objetivo principal do jogador.

Exemplos:

- coletar o maior número possível de itens;
- sobreviver pelo maior tempo possível;
- chegar até o final do labirinto;
- acertar alvos;
- responder perguntas corretamente;
- evitar obstáculos;
- quebrar todos os blocos.

Objetivo: Conseguir alinhar três símbolos iguais em uma linha, coluna ou diagonal antes do outro jogador.

> Escreva aqui.

## 6. Regras principais

Liste as principais regras do jogo.

Exemplo:

- O jogador começa com 3 vidas.
- Cada moeda coletada vale 10 pontos.
- Cada colisão com obstáculo remove 1 vida.
- A partida termina quando as vidas chegam a zero.
- O jogador vence se alcançar 100 pontos.

Regras do grupo:

- Regra 1: O jogador X inicia a partida.
- Regra 2: Os jogadores jogam alternadamente.
- Regra 3: Uma casa ocupada não pode ser utilizada novamente.
- Regra 4: O jogo verifica automaticamente vitória ou empate.
- Regra 5: A partida termina quando houver vencedor ou empate.

## 7. Condição de vitória

Explique como o jogador vence ou conclui o jogo.

Exemplos:

- atingir determinada pontuação;
- chegar ao final da fase;
- sobreviver até o tempo acabar;
- responder uma quantidade mínima de perguntas;
- quebrar todos os blocos.

Condição de vitória: O jogador vence ao formar uma sequência de três símbolos iguais em uma linha, coluna ou diagonal

> Escreva aqui.

## 8. Condição de derrota ou encerramento

Explique como o jogador perde ou quando a partida termina.

Exemplos:

- perder todas as vidas;
- acabar o tempo;
- colidir com determinado obstáculo;
- errar muitas perguntas;
- deixar a bola cair, no caso de Breakout ou Pong.

Condição de derrota ou encerramento: O jogador perde quando o adversário forma uma sequência vencedora. A partida também pode terminar em empate quando todas as casas estiverem preenchidas sem vencedor.

> Escreva aqui.

## 9. Elementos previstos no jogo

Descreva os principais elementos que farão parte do jogo.

## Jogador ou elemento principal

Exemplo: 

> Um personagem controlado pelas setas do teclado.

Descrição: Dois jogadores representados pelos símbolos X e O.

> Escreva aqui.

## Obstáculos, inimigos ou desafios

Exemplo:

> Obstáculos aparecem em posições aleatórias e devem ser evitados.

Descrição: O principal desafio é impedir que o adversário complete uma sequência vencedora.

> Escreva aqui.

## Itens, alvos ou objetos de interação

Exemplo:

> Moedas aparecem na tela e aumentam a pontuação quando coletadas.

Descrição: As nove casas do tabuleiro, que podem ser selecionadas pelos jogadores.

> Escreva aqui.

## Pontuação, vidas, tempo ou progresso

Exemplo:

> O jogador começa com 3 vidas e ganha 10 pontos por item coletado.

Descrição: Será exibido o vencedor da partida. Opcionalmente poderá existir um placar acumulado entre várias rodadas.

> Escreva aqui.

## 10. Controles previstos

Informe os comandos que serão utilizados pelo jogador.

Exemplo:

- Seta para cima: mover para cima
- Seta para baixo: mover para baixo
- Seta para esquerda: mover para esquerda
- Seta para direita: mover para direita
- Espaço: realizar ação
- ESC: sair do jogo

Controles do grupo:

- Tecla/comando: Mouse : selecionar uma casa do tabuleiro.
- Tecla/comando: Tecla R : reiniciar a partida
- Tecla/comando: Tecla ESC : encerrar o jogo.

## 11. Organização inicial do código

Explique como o grupo pretende organizar o código.

Exemplo:

- `main.py`: inicia o jogo;
- `src/jogo.py`: contém o loop principal;
- `src/config.py`: guarda configurações como tamanho da tela e cores;
- `src/funcoes.py`: contém funções auxiliares;
- `src/dados.py`: contém funções de leitura e escrita de arquivos.

Organização planejada:
main.py: inicialização do jogo.
src/game.py: loop principal e gerenciamento da partida.
src/board.py: controle do tabuleiro e validação das jogadas.
src/player.py: gerenciamento dos jogadores.
src/utils.py: funções auxiliares.
tests/: testes das regras do jogo.

> Escreva aqui.


## 12. Recursos externos previstos

Informe se o grupo pretende utilizar imagens, sons, fontes, tutoriais ou códigos externos.

Exemplo:

- imagens obtidas de banco gratuito;
- sons gratuitos;
- tutorial usado apenas como referência;
- fonte personalizada.

Recursos previstos:
Imagens simples para os símbolos X e O.
Fonte para exibição de mensagens.
Sons opcionais para jogadas e vitória.

> Escreva aqui.

Caso não pretenda utilizar recursos externos, escreva:

> Não pretendemos utilizar recursos externos.

## 13. Principais dificuldades esperadas

Liste as dificuldades que o grupo acredita que poderá enfrentar.

Exemplos:

- movimentação do jogador;
- colisão entre objetos;
- controle de tempo;
- criação do ranking;
- organização do código;
- uso do GitHub;
- testes;
- exibição de textos na tela.

Dificuldades previstas:

- Dificuldade 1: Implementação da verificação de vitória
- Dificuldade 2: Organização do projeto utilizando o template fornecido.
- Dificuldade 3: Desenvolvimento e execução dos testes.

## 14. Escopo mínimo para a entrega final

Descreva qual será a versão mínima aceitável do jogo.

Esta seção é importante para evitar que o grupo escolha uma ideia grande demais.

Exemplo:

> A versão mínima do jogo terá um personagem controlado pelo teclado, obstáculos aparecendo na tela, sistema de vidas, sistema de pontuação e tela de fim de jogo.

Escopo mínimo: O jogo deverá possuir tabuleiro funcional, alternância entre jogadores, verificação de vitória, detecção de empate, reinício de partida e interface gráfica básica utilizando pygame.

> Escreva aqui.

## 15. Possíveis melhorias, caso haja tempo

Liste funcionalidades extras que o grupo poderá implementar se conseguir concluir o escopo mínimo.

Exemplos:

- tela inicial;
- sons;
- fases;
- aumento de dificuldade;
- ranking;
- animações;
- novos tipos de obstáculos;
- diferentes personagens;
- menu de pausa.

Melhorias possíveis:

- Melhoria 1: Modo contra computador.
- Melhoria 2: Sistema de placar entre partidas.
- Melhoria 3: Efeitos sonoros e animações.
- Melhoria 4: Tela inicial e menu.
- Melhoria 5: Diferentes temas visuais.