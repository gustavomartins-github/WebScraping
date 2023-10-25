# WebScraping - Monitores Gamers da Kabum
Esse repositório hospeda uma solução de webscraping para benchamrk de dados de monitores gamers da plataforma de vendas online <a href = "https://www.kabum.com.br/computadores/monitores/monitor-gamer">Kabum</a>. Somado a isso, um grafico de linhas interativo foi desenvolvido para análise dos resultados obtidos.

### Ferramentas
* Python         - Linguagem de desenvolvimento do app
* Selenium       - Simular o uso do Navegador Web
* Openpyxl       - Criar e Manipular arquivos em Excel
* Pandas         - Abrir e Manipular arquivos em Excel
* Plotly_express - Criação de Gŕaficos Interativos

### Inferência
* ![image](https://github.com/gustavomartins-github/WebScraping-Kabum_Gamer_Monitors/assets/72039007/7dddb004-aa5c-44e1-bfcb-71857633370e)

### Sobre o código

O código foi estruturado em um <a href = "https://github.com/gustavomartins-github/WebScraping-Kabum_Gamer_Monitors/blob/main/app.ipynb">jupyter notebook</a> contendo 4 etapas principais. São elas

* <strong>ETAPA 01</strong> (Premissas / Requerimentos): instalação/importação das biblitoecas necessárias para o projeto. (Linux - Ubuntu 22.04 LTS)
* <strong>ETAPA 02</strong> (Criação do Excel): criação e população da base de dados que mais tarde será utilizada para plotar o gráfico interativo.
* <strong>ETAPA 03</strong> (Formatação dos Dados): refinamento dos dados para torna-los utilizáveis ao futuro gráfico
* <strong>ETAPA 04</strong> (Criação do Gráfico): criação do gráfico de linhas de acordo com os dados coletados e refinados da base de dados

Obs.: caso deseje apenas visualizar o gráfico, basta abrir o arquivo graphic.html

### Referências
* <a href = "https://www.youtube.com/watch?v=UVfNeNoybOs">Dev Aprender (Jhonatan Souza)</a>
* <a href = "https://www.selenium.dev/selenium/docs/api/py/index.html">Selenium - Official Documentation</a>
* <a href = "https://plotly.com/python/plotly-express/"> Plotly Express - Official Documentation</a>
* <a href = "https://pandas.pydata.org/docs/user_guide/index.html"> Pandas - User Guide Documentation</a>
* <a href = "https://pypi.org/project/kaleido/"> Kaleido - Graphic WEB API to Plotly</a>
