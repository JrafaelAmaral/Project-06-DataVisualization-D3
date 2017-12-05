README

Link de visualização – 1ª versão: http://bl.ocks.org/JrafaelAmaral/0fbb2d620173111776279f97694c2d76
Link de visualização – 2ª versão: http://bl.ocks.org/JrafaelAmaral/56b9953ac7b3a0513f5f2af1018814bb
Link de visualização – 3ª versão: http://bl.ocks.org/JrafaelAmaral/d8376049883e915431133b31e26d73b2

Resumo
Esta visualização tem como foco explorar e exibir os dados da tripulação do Titanic, estabelecendo uma correlação entre as variáveis de sobrevivência e de embarque, isto é, mostrar como se deu a questão da sobrevivência tendo como eixo central os três portos de embarque (Southampton (Reino Unido), Cherbourg (França) e Queenstown (Irlanda)), que foram as cidades escolhidas para receber a primeira e última viagem do transatlântico mais luxuoso e conhecido de sua época. 
A visualização é dividida em quatro gráficos (Pessoas em Números, Pessoas em %, Classes por Embarque e Gênero por Embarque), o que nos faz perceber as estatísticas da tragédia do Titanic por uma ótica diferente da maioria dos trabalhos que encontramos na internet a cerca deste assunto. Alguns pontos interessantes a ressaltar é que aqueles que embarcaram em Southampton foram muito menos propensos a sobreviver e a maioria dos passageiros (72%) eram de Southampton, poucos ingressos eram da primeira classe e havia um número desproporcionalmente elevado de homens (68%).

Design
Os quatro gráficos são encontrados nos exemplos index.html disponíveis na página do dimplejs.org 
O primeiro gráfico, Vertical Grouped Bubblepop, é um gráfico de bolhas e foi pensado para refletir claramente a quantia de sobreviventes e mortos por porta de embarque. O eixo X é dividido pelas três portas de embarque e o eixo Y mostra a quantia em números totais de pessoas.
O segundo gráfico, Horizontal 100% Bar, é um gráfico de barras horizontais e é utilizado para exibir a porcentagem entre vivos e mortos em cada porta de embarque. O eixo X mostra a quantidade em porcentagem e o eixo Y, as três portas de embarque.
O terceiro gráfico, Vert Stacked Grouped Bar, agrupa empilhando os dados da mesma variável, de forma vertical, exibindo as diferentes porcentagens em variações de cores. Temos no eixo X a variável classe do navio (primeira, segunda e terceira classe), com a porcentagem da tripulação empilhada por porta de embarque e no eixo Y temos a escala de porcentagem sobre a variável de passageiros.
O quarto gráfico, Vert Stacked Grouped Bar, expõe a quantidade de passageiros sendo possível visualizar e comparar facilmente a distribuição de dois valores análogos lado a lado. No eixo X temos a variável de gênero dividindo homens e mulheres de acordo com sua porta de embarque e no eixo Y é exibido a quantidade de passageiros em porcentagem.

Limpeza dos dados
Realizada em Python através do IPython Notebook.

Feedbacks 1ª versão
- O que você percebeu na visualização?
Avaliador A: Uma sintetização dos dados relativos a tripulação do navio Titanic, portos de embarque e relações entre números de mortos  e sobreviventes.
Avaliador B: Um resumo sobre a tragédia do Titanic e suas características de sobrevivência.
Avaliador C: Percebi que eu pouco ou nada sabia sobre as pessoas que morreram ou sobreviveram no acidente.

- Quais perguntas você tem sobre os dados?
Avaliador A: Nenhum questionamento
Avaliador B: Nada veio a mente
Avaliador C: Será que é possível ter na internet dados diferentes que estes apresentados.

- Que relacionamento você percebeu?
Avaliador A: Pude observar após a leitura dos gráficos que grande parte da tripulação que não sobreviveu eram da classe mais baixa.
Avaliador B: Que o porto de Southampton foi o que apresentou o maior número de mortos.
Avaliador C: Que havia correlação entre classe social, sexo, idade, e os portos de embarque.

- O que você acha que é o principal destaque dessa visualização?
Avaliador A: A relação direta da tragédia do Titatanic que se tem entre portos de embarque, tipos das tripulação e o grande número de mortos das classes sociais mais baixas. 
Avaliador B: As pessoas da terceira classe não tiveram a mesma sorte que as pessoas da primeira.
Avaliador C: Na minha opinião foram as 3 cidades já apresentadas logo no início e a tripulação relacionada a elas.

- Existe algo que você não entende no gráfico? 
Avaliador A: No gráfico não, depois de algum esforço consegui descobrir o que significava algumas letras, pois na minha opinião faltaram algumas legendas explicativas e observações para interpretar o gráfico melhor.
Avaliador B: Eu entendo inglês mas outras pessoas não e os gráficos estão todos em inglês embora o texto esteja em português, seria melhor passar os gráficos para português.
Avaliador C: Depois de algumas leituras entendi tudo porém o texto, na minha opinião ficou um pouco extenso e poderia ser mais reduzido, pois as pessoas podem ter preguiça de ler. Em especial seria bom reduzir a parte da ‘Curiosidade sobre os portos’ pois há alguns trechos desnecessários. Outra coisa que poderia mudar seria a ‘Característica da tripulação’, na minha opinião seria melhor vir antes dos gráficos pois é a parte que explica as correlações, já que quase não tem legendas ou observações, notas de rodapé, etc..

Modificações realizadas sobre os feedbacks da 1ª versão
O avaliador A sugeriu incluir legendas explicativas e observações para melhorar a interpretação, decidi incluir uma linha explicando que é possível ver detalhes a mais apenas deslizando o mouse sobre seus conteúdos e cores. 
O avaliador B sugeriu passar os gráficos para português e assim foi feito.
O avaliador C sugeriu reduzir o tamanho do texto, decidi reduzir o formato contextual com explicações mais diretas.

Feedback 2ª versão
Avaliador do projeto Udacity: Gráfico Classe por Embarque: seria interessante modificar o rótulo do eixo y. Passageiros é um termo muito abrangente e leva o leitor a entender que neste eixo teremos um número, e não um percentual, como é apresentado.
Gráfico Gênero por Embarque: O mesmo comentado acima vale para o 4º gráfico. Seria interessante adicionar um espaçamento entre as barras de homens e mulheres, como é feito no 3º gráfico. Deste modo, o usuário não dependeria do tooltip para saber qual barra refere aos homens e qual barra é das mulheres.
É necessário adicionar comentários no código para que as principais partes do nosso código javascript sejam legíveis por futuros leitores.

Modificações realizadas sobre o feedback da 2ª versão
Como sugerido pelo avaliador do projeto, modifiquei os rótulos do eixo y do 3º e 4º gráfico, para "Passageiros em %". Apliquei também um espaçamento entre as barras de homens e mulheres no 4º gráfico.
Foram adicionados comentários na 3ª versão do código.

Recursos e referências
http://dimplejs.org/

https://docs.google.com/document/d/1w7KhqotVi5eoKE3I_AZHbsxdr-NmcWsLTIiZrpxWx4w/pub?embedded=true

http://bl.ocks.org/ishashankverma/61f8bd16bff7c41ad02709dc1a0fdcab
