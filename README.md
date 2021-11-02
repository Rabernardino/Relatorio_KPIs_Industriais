# Relatorio_KPIs_Industriais

<p align="center">
  <a href="#Introdução">Introdução</a> |
  <a href="#Bibliotecas Utilizadas">Bibliotecas Utilizadas</a> |
  <a href="Descrição do Projeto">Descrição do Projeto<a> |
  
  # Introdução
<font color ='gray' style = 'font-size: 18px;'></font>
<p style='font-size: 18px; line-height: 2;'>O projeto apresentado tem como objetivo demonstrar as etapas do desenvolvimento dos KPIs de uma determinada planta produtiva, onde para
tal foram utilizados dados que simulam o comportamento de uma unidade fabril, levando em conta ainda erros e desvios que são inerentes aos variados tipos de processos produtivos.

São apresentadas as etapas de importação dos dados oriundos de uma view gerada no banco de dados, o tratamento realizado e necessario para correção de desvios presentes nos dados, 
o desenvolvimento do conceito dos KPIs que serão apresentados, a construção dos mesmos e por fim a sua apresentação visual.</p>

# Bibliotecas Utilizadas
<font color ='gray' style ='font-size: 18px;'></font>
<ul>
<li>Pandas</li>
<li>Numpy</li>
<li>Matplotlib</li>
<li>Seaborn</li>
</ul>

# Descrição do Projeto
<font color ='gray' style = 'font-size: 18px;'></font>
<p style='font-size: 18px; line-height: 2;'>O gerenciamento de um processo é feito através do monitoramento e controle das suas entradas e saídas, buscando sempre a manutenção
qualidade do produto final obtido. Para que sejam monitorados e controlados de maneira constante e com assertividade se faz necessario definir os pontos chaves associados a performance
do processo. 

No ambiente industrial composto pelos mais variados tipos de processos produtivos, existem um grande numero de indicadores que permitem acompanhar o desempenho de equipamento, linhas 
de processo, areas e a propria planta como um todo. Dentre estes indicadores se destacam o OEE, do inglês Overall Equipment Effectiveness, traduzido como a Eficácia Geral do Equipamento.
O OEE é o produto total de três outros indicadores sendo eles a Disponibilidade, Performance e a Qualidade. 

A Disponibilidade de um equipamento ou linha é obtido através da comparação do tempo trabalhado pelo tempo total que o equipamento estava planejado para o trabalho. 
Este indicador sofre impacto por quebras e interveções corretivas ao longo da produção, setups que podem ser inerentes ao tipo do processo produtivo 
ou mesmo ociosidade do equipamento.

A Performance por sua vez é encontrada com são comparados a quantidade que foi produzida ao longo das horas trabalhadas, pela quantidade que deveria ter sido produzida.  
Os aspectos que podem ocasionar variações neste KPI são variações de velocidade ao longo da produção, bem como pequenas paradas. A Performance deve sempre ser observada pois 
obter um processo que permanece em operação a uma velocidade mais rapida do que o especificado, pode ocasionar falhas e desgastes prematuros.

Por fim a Qualidade que é a razão da produção que de fato possui a qualidade especificada, pelo total que foi produzido. Como impactos diretos para a diminuição deste KPI 
estão associados os refugos gerados nas partidas de equipamento, setups e ao longo do processos produtivos.

Obtendo o valor final do OEE, o mesmo é comparado com o benchmark que varia de acordo com o processo produtivo em questão, além disso fornecendo a informação necessaria para a 
tomada de ação nos pontos negativos presentes em uma determinada linha ou area para alcançar o desempenho desejado. 


</p>
