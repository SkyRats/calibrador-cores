
# Calibrador de Máscaras de Cores


Calibrador de máscaras de cores com opencv 
para filtrar um range
de cores desejado , além de  alterar a dilatação 
, erosão e o blur da imagem. Inclui máscaras 
prontas para vermelho e verde .



## Vídeo explicativo

Tutorial resumido sobre a utilização
https://www.youtube.com/watch?v=o7tr0csMbpU
## Máscara manual
A máscara pode ser ajustada manualmente 
alterandos os valores HSV mínimo e máximo 
(6 primeiras trackbars).



Para resetar a máscara , digite "R".
## Moldagem da Imagem

ERODE :  Aumenta as regiões NÃO selecionadas da máscara, 
ou seja , pontos de detectção
 isolados em uma região não detectada
tendem a diminuir.

DILATE : Aumenta as regiões selecionadas da máscara,ou seja, 
pontos escuros em uma região de detectção tendem
a diminuir.

BLUR : Diminui a qualidade da imagem , o que 
pode optimizar a detecção de cores. 
## Máscara por Cliques
Caso deseje selecionar uma cor diretamente 
na tela sem precisar de seus valores HSV , é
possível utilizar a calibração por cliques.

Para ativar os cliques , digite "E".

Na trackbar "CliquesMáximos" selecione o 
número de cliques necessário para selecionar
as diferentes tonalidades desejadas (recomendado
escolher pontos com luminosidade diferentes)

Clique com o botão esquerdo 
nas regiões desejadas até que a 
trackbar "Cliques" atinja o número de cliques
máximos escolhido. Após isso , a máscara será 
aplicada automaticamente. 

É possível também subtrair uma cor da máscara. 
Para isso , clique com o botão direito do mouse
na cor desejada , no mesmo processo mencionado acima.

Para resetar a máscara , digite "R".

Para desativar os cliques , digite "E".
## Máscaras vermelha e verde
Devido a demandas de uma competição , estão
inclusas máscaras pré-prontas para vermelho e verde.

Digite "F" para ativar a máscara vermelha.

Digite "G" para ativar a máscara verde.
