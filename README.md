# 2019.02-Tunel-de-Vento
# 1.Início
## Tema: Experimentos em Túnel de Vento
### Integrantes:
Flávio Henrique de Almeida Feitoza Filho-17/0103145;

Gabriel Metre Resende-17/0120805;

Raiane Almeida Silva Vieira-17/0021220.
### 1.1 Objetivo:
 O presente trabalho tem por objetivo apresentar, bem como demonstrar por meio da realização de experimento em túnel de vento os efeitos do fluxo de ar sobre determinado corpo, permitindo-se assim obter resultados referentes a força de sustentação e de arrasto através da análise do comportamento estrutural. 
### 1.2 Escopo:
O estudo da Aerodinâmica consiste na verificação do comportamento do ar e sua interação com um objeto sólido. Assim, a verificação das forças de arrasto e sustentação, bem como os momentos sobre um corpo e a determinação do comportamento do escoamento correspondem aos objetivos das análises aerodinâmicas.

Tanto as forças quanto os momentos são provenientes da distribuição de pressão e da tensão de cisalhamento sobre a superfície do corpo.

Abaixo será apresentado um esquemático das forças e momentos em um perfil aerodinâmico.

![perfil de asa](https://github.com/laboratorio-de-dinamica-dos-fluidos/2019.02-Tunel-de-Vento/blob/master/perfil%20de%20asa.PNG)

**Figura 1**-Diagrama de forças aerodinâmicas.

- &alpha; - ângulo de ataque;

- L - sustentação;

- D - arrasto;

- R - força resultante;

- N - força normal;

- c - corda da asa; 

- A - força axial; 

- V&infin; - velocidade do vento. 

Tendo em vista, tais características para realização do experimento serão realizadas as seguintes etapas:
- Dimensionamento do túnel de vento;
- Desenvolvimento de perfis aerodinâmicos em impressora 3D e cano PVC, a fim de verifiar os esforços e pesos de diferentes estruturas; 
- Monitoramento e medição das variáveis: força de sustentação e força de arrasto;
- Verificação do comportamento físico da parte estrutural;
- Simulação e verificação das linhas de emissão, as quais poderam ser vizualizadas com a utilização de pedaços de barbante posicionados ao longo do perfil; 
- Aquisição dos dados obtidos através de equipamentos eletrônicos e análise via software;
- Comparação dos resultados obtidos aos cálculos teóricos.
### 1.3 Viabilidade
Para realizar o experimento é preciso de um túnel de vento, uma balança aerodinâmica e perfis de asas. O laboratório de termofluídos do Campus Gama da Universidade de Brasília, possui um túnel de vento e uma balança aerodinâmica, ambos atendem aos requisitos para a realização do experimento. Sabendo que já é de posse a maioria dos materiais a serem utilizados, os custos adicionais serão baixos e não será despendido muito tempo para montagem, assim conclui-se que é viável a execução do projeto. 

 # 2.Planejamento e preparação
 ## 2.1 Cronograma
 
![Planejamento e organização](https://github.com/laboratorio-de-dinamica-dos-fluidos/2019.02-Tunel-de-Vento/blob/master/Planejamento%20e%20Organiza%C3%A7%C3%A3o.jpg)
 **Figura 2** - Cronograma.
 ## 2.2 Dados Medidos
 Para realização do experimento deve-se inicialmente determinar a velocidade de escoamneto do túnel de vento. Dessa maneira, é necessário utilizar as equações de Bernoulli e da continuidade, que serão apresentadas respectivamente a seguir:
 
 ![Eq.Bernoulli](https://github.com/laboratorio-de-dinamica-dos-fluidos/2019.02-Tunel-de-Vento/blob/master/Eq.Bernoulli.PNG)(Eq.1)
 
 Consoante as equações apresentadas acima tem-se que V é a velocidade do vento, P é a pressão a qual o fluido está submetido, 𝜌 é
a densidade do fluido, g é a aceleração da gravidade, z é a altura em que o fluido está, ademais considera-se as
variáveis com o número 1 referentes aos dados para a maior seção do túnel de vento e 2 se refere à
seção menor. Isola-se a velocidade 𝑉1 da equação (2) e substitui na equação (1), podendo-se obter assim, as velocidades 𝑉1 e 𝑉2.

 Ademais, para vizualizar as linhas de emissão para diferentes ângulos de ataque, em especial no ângulo de estol, no qual há uma perda total de sustentação da asa, já que ocorre uma variação da camada limite. Tais características serão vizualizadas, bem como simuladas no programa XFLR5.
 
 A Sustentação corresponde a uma força aerodinâmica produzida pela ação do vento relativo
em um aerofólio, influenciada por superfícies de controle. Um aerofólio que se move no ar produz a sustentação, pois exerce em sua
superfície inferior uma pressão maior do que na superfície, essa diferença de pressão se dá devido a característica estrutural do aerofólio. Da mesma maneira pode-se considerar pra a força de Arrasto, no entanto deve-se levar em conta que essa força fornece uma resistência às aeronaves e por conseguinte redução da velocidade. Ambas forças dependem do ângulo de ataque.(ASSY,2004)

![Eq.Bernoulli](https://github.com/laboratorio-de-dinamica-dos-fluidos/2019.02-Tunel-de-Vento/blob/master/Eq.Continuidade.PNG)(Eq.2)

Com relação as fórmulas apresentadas acima tem-se que 𝜌 representa a densidade do fluido, 𝑐𝑙 é o coeficiente de sustentação e 𝑐𝑑 é o
coeficiente de arrasto, v é a velocidade, c é a corda do perfil, D é a força de Arrasto e S a força de Sustentação.

A visualização do escoamento em perfis aerodinâmicos é utilizada para aferir os resultados obtidos pelos métodos numéricos, normalmente, resultados obtidos em softwares
de simulação. A geração de um escoamento laminar é imprescindível para a visualização
das linhas de corrente que são linhas desenhadas no campo de escoamento de forma que
num dado instante, são tangentes à direção do escoamento em cada ponto do campo.
(FOX, 2001)

## 2.3 Resultados Esperados
 O experimento visa validar os gráficos "cl versus angulo de ataque" e "cd versus angulo de ataque" simulados via software. Bem como também mostrar o efeito dinâmico sobre o escoamento causado um certo ângulo de ataque no aerofólio.
