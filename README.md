📊 Clusterização de Penguins
Este notebook apresenta uma aplicação prática do algoritmo K-Means para clusterização de pinguins com base em características fisiológicas.

🔍 Objetivo
Utilizar técnicas de aprendizado não supervisionado para agrupar os pinguins da base penguins (do seaborn), identificando padrões sem utilizar o rótulo da espécie.

🧪 Etapas do notebook
Pré-processamento dos dados
-Eliminação de variáveis categóricas
-Renomeação das colunas
-Remoção de valores nulos

Visualização exploratória
-Uso do pairplot (Seaborn) para observar possíveis agrupamentos naturais nos dados

Padronização dos dados
-Aplicação de StandardScaler para normalizar os valores

Aplicação do K-Means
-Clusterização com 3 grupos (correspondendo às espécies Adelie, Chinstrap e Gentoo)

Visualização dos clusters
-Criação de gráficos de dispersão com Plotly para análise dos agrupamentos e centróides

Discussão de aplicações
-Segmentação de clientes
-Detecção de anomalias em segurança cibernética
-Análise de exames médicos por imagem

📚 Bibliotecas utilizadas
pandas
seaborn
plotly
scikit-learn

