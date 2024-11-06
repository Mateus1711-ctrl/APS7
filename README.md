# APS7

Jogador de Forca Automático

Este projeto utiliza teoria da informação para construir um jogador automático para o jogo de forca. O objetivo é que o jogador descubra uma palavra oculta escolhendo letras estrategicamente para aumentar suas chances de vitória com apenas cinco vidas.

Estrutura do Projeto

- Classe `JogoDeForca`
 Gerencia o jogo da forca, permitindo iniciar um novo jogo, adivinhar letras e tentar a palavra completa. Se o jogador cometer um erro, ele perde uma vida.

-Classe `JogadorDeForca`
 Usa uma estratégia automática baseada na frequência das letras. O jogador prioriza as letras mais comuns no vocabulário para aumentar suas chances de acerto. Após cada tentativa, a lista de palavras possíveis é reduzida de acordo com o feedback recebido.

Estratégia do Jogador

A estratégia utiliza entropia para determinar a próxima letra a ser escolhida, reduzindo a incerteza sobre a palavra oculta e maximizando a chance de acerto.