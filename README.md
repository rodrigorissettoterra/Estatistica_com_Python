ESTATÍSTICA: FREQUÊNCIA E MEDIDAS
<ul>
 	<li>Variáveis utilizadas</li>
 	<li>Observação</li>
 	<li>Preparando o ambiente
<ul>
 	<li>Importando as bibliotecas necessárias</li>
 	<li>Carregando a base de dados</li>
 	<li>Informações sobre a base de dados</li>
</ul>
</li>
 	<li>Distribuição de frequências
<ul>
 	<li>UF</li>
 	<li>Sexo</li>
 	<li>Idade</li>
 	<li>Cor</li>
 	<li>Anos de Estudos</li>
 	<li>Renda</li>
 	<li>Altura</li>
</ul>
</li>
 	<li>Informações estatísticas</li>
</ul>
</br></br>
ESTATÍSTICA: TESTE DE HIPÓTESES COM PYTHON
<ul>
 	<li>Variáveis utilizadas</li>
 	<li>Observação sobre a base de dados</li>
 	<li>Preparando o ambiente
<ul>
 	<li>Importando as bibliotecas necessárias</li>
 	<li>Carregando a base de dados</li>
 	<li>Informações sobre a base de dados</li>
 	<li>Dados faltantes</li>
 	<li>Dados nulos</li>
</ul>
</li>
 	<li>Teste de hipóteses
<ul>
 	<li>Teste de normalidade
<ul>
 	<li>Definindo a significância do teste (α)</li>
 	<li>Testando a variável Renda
<ul>
 	<li>Critério do valor p - Renda</li>
</ul>
</li>
 	<li>Testando a variável Altura
<ul>
 	<li>Critério do valor p - Altura</li>
</ul>
</li>
</ul>
</li>
</ul>
</li>
 	<li>Renda de SP com RJ
<ul>
 	<li>Selecionando 2 amostras de 500 respondentes de cada estado</li>
 	<li>Média e Desvio padrão das duas amostras</li>
 	<li>Definindo valores para os testes</li>
 	<li>Teste de hipótese
<ul>
 	<li>Fixação da significância do teste (α)</li>
</ul>
</li>
 	<li>Cálculo da estatística-teste e verificação desse valor com as áreas de aceitação / rejeição do teste</li>
 	<li>Aceitação / Rejeição de H0</li>
 	<li>Valor p</li>
</ul>
</li>
 	<li>Conclusão</li>
</ul>
</br></br>
CORRELAÇÃO E REGRESSÃO

1 CONHECENDO OS DADOS
<ul>
 	<li>1.1 Dataset do projeto
<ul>
 	<li>Pesquisa Nacional por Amostra de Domicílios - 2015</li>
 	<li>Fonte dos Dados</li>
 	<li>Variáveis utilizadas</li>
 	<li>Observação</li>
 	<li>Solução do problema com dependência do statsmodels</li>
 	<li>Importando bibliotecas</li>
 	<li>Abrindo arquivos dretamente do Google Drive</li>
 	<li>Lendo o dataset do projeto</li>
</ul>
</li>
</ul>
2 RODANDO UMA REGRESSÃO LINEAR
<ul>
 	<li>Dataset de exemplo</li>
 	<li>Estatísticas descritivas</li>
 	<li>Análise gráfica</li>
 	<li>Análise da correlação</li>
 	<li>Modelo de regressão linear simples</li>
 	<li>Estimando o modelo</li>
 	<li>Obtendo as previsões dentro da amostra</li>
</ul>
3 CORRELAÇÃO
<ul>
 	<li>3.1 Covariância
<ul>
 	<li>Covariância populacional</li>
 	<li>Covariância amostral</li>
 	<li>Gerando uma amostra aleatória para facilitar o entendimento</li>
 	<li>Obtendo a matriz de covariância</li>
 	<li>Identificando as variâncias na diagonal principal da matriz</li>
</ul>
</li>
 	<li>3.2 Interpretação da Covariância
<ul>
 	<li>Verificando a existência de uma associação linear negativa</li>
 	<li>Verificando a existência de uma associação linear positiva</li>
 	<li>Verificando a inexistência de uma associação linear entre as variáveis</li>
 	<li>Observação Importante:</li>
</ul>
</li>
 	<li>3.3 Coeficiente de correlação de Pearson
<ul>
 	<li>Coeficiente de correlação de Pearson - dados populacionais</li>
 	<li>Obtendo sxy</li>
 	<li>Obtendo sx e sy</li>
 	<li>Obtendo o coeficiente de correlação rxy</li>
 	<li>Obtendo uma matriz de correlação com o Pandas</li>
</ul>
</li>
</ul>
4 REGRESSÃO LINEAR
<ul>
 	<li>Terminologia</li>
 	<li>4.1 Regressão linear simples
<ul>
 	<li>Função consumo</li>
 	<li>Carregando o dataset</li>
 	<li>Identificando a relação entre as variáveis</li>
 	<li>Matriz de correlação</li>
 	<li>Função de regressão populacional</li>
</ul>
</li>
</ul>
<ul>
 	<li>4.2 O método de mínimos quadrados
<ul>
 	<li>Yi=β1+β2Xi+ui</li>
</ul>
</li>
</ul>
<ul>
 	<li>4.3 Estimadores de mínimos quadrados ordinários
<ul>
 	<li>Obter n</li>
 	<li>Obter ∑Y</li>
 	<li>Obter ∑X</li>
 	<li>Obter ∑X2</li>
 	<li>Obter ∑Y2</li>
 	<li>Obter ∑XY</li>
 	<li>Obter β^2</li>
 	<li>Obter β^1</li>
 	<li>Obtendo a estimativa dos parâmetros com o StatsModels</li>
 	<li>Importando a biblioteca</li>
 	<li>Estimando o modelo</li>
 	<li>Visualizando os parâmetros estimados</li>
 	<li>Intervalo de confiança para os parâmetros estimados</li>
</ul>
</li>
 	<li>4.4 Obtendo previsões
<ul>
 	<li>Y^i=207,9033+0,2973Xi</li>
 	<li>Previsões dentro da amostra</li>
 	<li>Estimando o 'Gasto das Famílias' fora da amostra</li>
 	<li>Estimando o 'Gasto das Famílias' fora da amostra via StatsModels</li>
</ul>
</li>
 	<li>4.5 Resíduos
<ul>
 	<li>u^i=Yi−Y^i</li>
</ul>
</li>
 	<li>4.6 Suposições sobre o termo de erro u
<ul>
 	<li>Plotando os resíduos do modelo</li>
 	<li>Hipótese de variância constante</li>
</ul>
</li>
 	<li>4.7 O coeficiente de determinação R2
<ul>
 	<li>R2=[∑(Yi−Y¯)(Y^i−Y¯)]2∑(Yi−Y¯)2∑(Y^i−Y¯)2</li>
 	<li>Soma do quadrados do erros (SQE)</li>
 	<li>Soma do quadrados total (SQT)</li>
 	<li>Soma do quadrados da regressão (SQR)</li>
 	<li>Relação entre as somas de quadrados</li>
 	<li>Coeficiente de determinação (R²)</li>
</ul>
</li>
 	<li>4.8 Testes aplicados a modelos de regressão
<ul>
 	<li>Yi=β1+β2Xi</li>
 	<li>Output do modelo de regressão estimado</li>
 	<li>Erro quadrático médio - estimativa de σ2</li>
 	<li>Teste de hipótese para nulidade do coeficiente angular</li>
 	<li>Yi=β1+β2Xi+ui</li>
 	<li>Calculando s</li>
 	<li>Calculando ∑(Xi−X¯)2</li>
 	<li>Calculando sb2</li>
 	<li>Determinando as áreas de aceitação e rejeição de H0</li>
 	<li>Níveis de confiança e significância</li>
 	<li>Obtendo tα/2</li>
 	<li>Obtendo t=b2−β2sb2</li>
 	<li>Etapas e regras de decisão do teste t de significância dos parâmetros</li>
 	<li>Critério do valor crítico</li>
 	<li>Critério do p−valor</li>
 	<li>Conclusão: Rejeitamos H0 e concluímos que existe uma relação significativa entre as duas variáveis.</li>
 	<li>Teste F</li>
 	<li>H0:β2=0</li>
 	<li>Calculando a estatística de teste (F)</li>
 	<li>Obtendo o p-valor</li>
</ul>
</li>
</ul>
5 EXTRAS
<ul>
 	<li>5.1 Outros testes
<ul>
 	<li>Normalidade dos resíduos - Omnibus</li>
 	<li>Verificando a simetria</li>
 	<li>Verificando a curtose</li>
 	<li>Normalidade dos resíduos - Jarque-Bera (statsmodels)</li>
 	<li>Normalidade dos resíduos - Jarque-Bera (Correção)</li>
</ul>
</li>
</ul>
