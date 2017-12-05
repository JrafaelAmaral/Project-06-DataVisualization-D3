README


Link de visualização – 1ª versão: http://bl.ocks.org/JrafaelAmaral/0fbb2d620173111776279f97694c2d76

Resumo
Esta visualização tem como foco explorar e exibir os dados da tripulação do Titanic, estabelecendo uma correlação entre as variáveis de sobrevivência e de embarque, isto é, mostrar como se deu a questão da sobrevivência tendo como eixo central os três pontos de embarque (Southampton, Cherbourg e Queenstown), que foram as cidades escolhidas para receber a primeira e última viagem do transatlântico mais luxuoso e conhecido de sua época. 
A visualização é dividida em quatro gráficos (sobrevivente e mortos por grupo, sobrevivente e mortos por porta, classes por porta e gênero por porta - de embarque), o que nos faz perceber as estatísticas da tragédia do Titanic por uma ótica diferente da maioria dos trabalhos que encontramos na internet a cerca deste assunto. Alguns pontos interessantes a ressaltar é que aqueles que embarcaram em Southampton foram muito menos propensos a sobreviver e a maioria dos passageiros (72%) eram de Southampton, poucos ingressos eram da primeira classe e havia um número desproporcionalmente elevado de homens (68%).

Design
Os quatro gráficos são encontrados nos exemplos index.html disponíveis na página do dimplejs.org 
O primeiro gráfico, Vertical Grouped Bubblepop, é um gráfico de bolhas e foi pensado para refletir claramente a quantia de sobreviventes e mortos por porta de embarque. O eixo X é dividido pelas três portas de embarque e o eixo Y mostra a quantia em números totais de pessoas.
O segundo gráfico, Horizontal 100% Bar, é um gráfico de barras horizontais e é utilizado para exibir a porcentagem entre vivos e mortos em cada porta de embarque. O eixo X mostra a quantidade em porcentagem de 0 a 100% e o eixo Y, as três portas de embarque.
O terceiro gráfico, Vert Stacked Grouped Bar, agrupa empilhando os dados da mesma variável, de forma vertical, exibindo as diferentes porcentagens em variações de cores. Temos no eixo X a variável classe do navio (primeira, segunda e terceira classe), com a porcentagem da tripulação empilhada por porta de embarque e no eixo Y temos a escala de porcentagem de 0 a 100% sobre a variável de passageiros.
O quarto gráfico, Vertical Grouped Bar, foi pensado para exibir a quantidade de passageiros por barras não empilhadas, neste tipo, é possível visualizar e comparar facilmente a distribuição de dois valores análogos lado a lado. No eixo X temos a variável de gênero dividindo homens e mulheres de acordo com sua porta de embarque e no eixo Y é exibido a quantidade em números totais.

Recursos e referências
http://dimplejs.org/
https://docs.google.com/document/d/1w7KhqotVi5eoKE3I_AZHbsxdr-NmcWsLTIiZrpxWx4w/pub?embedded=true
http://bl.ocks.org/ishashankverma/61f8bd16bff7c41ad02709dc1a0fdcab

Limpeza dos dados
Realizada em Python através do IPython Notebook gerando dois arquivos D3_1.csv e D3_2.csv

Perguntas que serão feitas para obter o primeiro feedback
- O que você percebeu na visualização?
- Quais perguntas você tem sobre os dados?
- Que relacionamento você percebeu?
- O que você acha que é o principal destaque dessa visualização?
- Existe algo que você não entende no gráfico? 

