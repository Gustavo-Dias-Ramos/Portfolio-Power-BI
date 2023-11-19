### UNDP Anos Esperados de Escolaridade
##### Análise inicial (Python)
Neste projeto, inicialmente realizei uma análise do dataset utilizando Python. Com isso pude constatar que as informações de alguns países estavam incompletas.
Neste estudo de caso, manter estes dados faltantes é importante pois a ausência de informação pode ser servir de comparação com a informação de outros países.

##### Dashboard (Power BI)
Na criação do dashboard, foi preciso inicialmente tratar o dataset, pois as informações dos anos estavam separadas por colunas, o que não permitia uma análise
temporal por país. Assim, realizei a transformação das colunas "Expected Years of Schooling" para linhas. Isso gerou diversas entradas para cada país, de acordo
com o ano analisado.
![Dataset01](https://github.com/Gustavo-Dias-Ramos/Portfolio-Power-BI/assets/129678166/7d364d2a-c7b1-4377-97e1-7819d6f64226)

Com isso, Bastou criar uma nova coluna com a data respectiva de cada ano analisado, e assim realizar as visualizações ao longo do tempo.

![Dataset02](https://github.com/Gustavo-Dias-Ramos/Portfolio-Power-BI/assets/129678166/d2ae596e-f5ed-4b4a-8485-c24162a4a4ed)

Na criaçãodo dashboard, optei por inserir inicialmente um filtro por Continente/País, possibilitando uma análise comparativa entre os diferentes países analisados no dataset. É possível verificar no gráfico de linhas a trajetória da expectativa de anos de escolaridade nos anos analisados, e a tendencia de aumento ou declínio dessa espectativa para cada país. Na tabela é possível verificar informações específicas dos países selecionados como o Rank do Indice de Desenvolvimento Humano (2021), o Grupo de Desenvolvimento Humano, a Região de desenvolvimento e a média e de Anos Esperados de Escolaridade. Por fim, é a presentada uma disposição geográfica dos países e a expectativa média de anos de escolaridade.

A análise inicial do dataset pode ser encontrada no arquivo Análise inicial.ipynb<br>
O dataset utlizado pode ser encontrado no arquivo schooling.csv<br>
O dashboard criado pode ser encontrado em formato .pdf ou .pbix<br>
