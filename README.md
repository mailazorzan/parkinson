# Parkinson

O principal objetivo é discriminar pessoas saudáveis daquelas com Doença de Parkinson (Parkinson Disease - PD), O dataset é composto por uma série de medições biomédicas de voz de 31 pessoas, 23 com PD. Cada coluna na tabela é uma medida de voz específica, e cada linha corresponde a uma das 195 gravações de voz desses indivíduos (coluna "nome").

Os dados estão no formato ASCII CSV. As linhas do arquivo CSV contêm uma instância correspondente a uma gravação de voz. São cerca de seis registros por paciente, o nome do paciente está identificado na primeira coluna.

Atributos do conjunto de dados:

name - nome do assunto ASCII e número de gravação;
MDVP:Fo(Hz) - Frequência fundamental vocal média;
MDVP:Fhi(Hz) - Frequência fundamental vocal máxima;
MDVP:Flo(Hz) - Frequência fundamental vocal mínima;
MDVP:Jitter(%),MDVP:Jitter(Abs),MDVP:RAP,MDVP:PPQ,Jitter:DDP - Várias medidas de variação na frequência fundamental;
MDVP:Shimmer,MDVP:Shimmer(dB),Shimmer:APQ3,Shimmer:APQ5,MDVP:APQ,Shimmer:DDA - Várias medidas de variação de amplitude;
NHR,HNR - Duas medidas de proporção de ruído para componentes tonais na voz status - Estado de saúde do sujeito: 1 = Parkinson, 0 = Saudável;
RPDE,D2 - Duas medidas de complexidade dinâmica não linear;
DFA - Expoente de dimensionamento fractal de sinal;
spread1,spread2,PPE - Três medidas não lineares de variação da frequência fundamental.
