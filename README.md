# Machine Learning: Recomendando musicas com K-means
#####  Base de dados trabalhada nesse projeto já foi extraida e passo por um tratamento básico

Inicio avaliando  API do Spotify e vejo alguns pontos  que entram como caracteristicas das musicas que eu vou precisa avaliar:

- Acustica: Uma variavél númerica, com uma medida de confiança binaria, 1 representa alta confiança que a música é acustica e 0 a musicá tem baixa confiança que é acustica
- Dançabilidade: mesma decrição acima, a diferença é que os elementos são (tempo, elementos musicais, estabilidade de ritmo e força da batida)
- Duração: medido por uma trilha de milisegundos
- Energia: Uma variavél númerica, com uma medida de confiança binaria(aqui os elementos são o quão altas, rapidas e barulhentas a música consegue chegar)
- Musicas ao Vivo: Uma variavél númerica, detecta a presença de público na gravação
-Popularidade: Uma variavél númerica, aqui tenho uma variação de 0 a 100, sendo 100 a mais popular.
-------------------------------------------------------------------------------------------------



