# Tratamento de Dados da COVID-19

Esse projeto tem o intuito de explorar o dataframe da COVID-19 no Brasil (com dados iniciando no começo de Janeiro e finalizando em 27 - fev - 2023).
Nele, mapeei a quantidade de casos e óbitos acumulados e a quantidade populacional de cada estado brasileiro. Mostrando por partes meu primeiro contato e processo de exploração na biblioteca Folium.
Esses resultados podem ser visualizados nos arquivos "covid_br_2023", "covid_casos_br_2023" e "covid_obitos_br_2023".

## Instruções de Uso
### 1 - Preparando o ambiente
Os códigos foram desenvolvidos no sistema operacional Windows 10 com a linguagem de programação Python (versão 3.9.13) e o auxílio do ambiente de programação Jupyter Notebook. Dessa forma, é provável que surjam erros inesperados caso o código seja rodado em outras versões.

Além disso, utilizei a distribuição Anaconda - que já contém o python e muitos outros módulos. Abaixo, deixo algumas bibliotecas necessárias para o funcionamento do projeto e que precisam ser instaladas:

    pip install folium
    pip install geopandas
    pip install geobr

### 2 - Arquivos necessários
O arquivo necessário para a plotagem dos mapas está nomeado como "Tratamento de dados da COVID-19 (27 fev 2023).ipynb", também é importante ter em sua máquina os arquivos "HIST_PAINEL_COVIDBR_2023_Parte1_27fev2023" (dados da covid-19), "br_states.json (json que contém todos os estados brasileiros demarcados pela latitude e longitude) e "estados_POP2021_20221212" (dataframe com os estados brasileiros).


### 3 - Utilizando os script
* Escolha uma pasta do seu computador e coloque todos os arquivos necessários.
* Após isso, copie o endereço dessa pasta (localizado na parte superior do explorador de arquivos do Windows).
* Digite "cmd" na barra de pesquisa do Windows e abra o Prompt de comando. 
* Digite "cd <caminho_da_pasta>" e após entrar no diretório, escreva "jupyter notebook", aguarde abrir uma aba do navegador.
* No navegador, é possível ver todos os arquivos que estão localizados dentro da pasta que você escolheu, selecione o arquivo "Tratamento de dados da COVID-19 (27 fev 2023).ipynb".

