# Projeto: COVID-19 no Brasil - Desvendando Desigualdades e Lições para Crises Futuras

Análise de Big Data sobre o impacto da COVID-19 no Brasil, focando em desigualdades regionais e lições para futuras crises. Este projeto foi desenvolvido para a disciplina “Tópicos de Big Data em Python” da Universidade Estácio de Sá.

## Integrantes do Grupo

* EZEQUIEL OLIVEIRA BRAZ SENA
* HANNA SORAYA DE SOUZA E SILVA TORRES
* JOFABIO LIMA PINTO
* LUCAS RODRIGUES GADELHA

## Objetivo

Analisar os dados da pandemia de COVID-19 no Brasil utilizando técnicas de Big Data, com o intuito de identificar e quantificar as disparidades regionais e sociais no impacto da doença, compreender a dinâmica das ondas epidêmicas e extrair lições fundamentais para o fortalecimento da resiliência do sistema de saúde em futuras crises.

## Estrutura do Repositório

* **/notebooks**: Contém os Jupyter Notebooks com todo o código da análise, desde o processamento até a geração dos gráficos.
* **/data**: Pasta ignorada pelo Git. Contém os dados brutos (`raw`) e processados (`processed`). Os dados originais podem ser baixados do [Painel Coronavírus](https://covid.saude.gov.br/).
* **/reports**: Contém os relatórios finais e individuais do projeto.
* **/presentation**: Contém o banner final de apresentação do projeto.
* **/src**: Contém scripts ou funções auxiliares em Python.

## Ferramentas e Tecnologias

* **Linguagem:** Python 3.x
* **Processamento de Big Data:** Apache Spark (PySpark)
* **Bibliotecas Principais:** Pandas, Matplotlib, Seaborn
* **Ambiente:** Jupyter Notebook

## Como Executar

1.  Clone o repositório: `git clone https://github.com/[seu-usuario]/analise-covid-brasil.git`
2.  Crie e ative um ambiente virtual.
3.  Instale as dependências: `pip install pyspark pandas matplotlib seaborn jupyter`
4.  Faça o download dos dados da fonte original e coloque-os na pasta `data/raw/`.
5.  Execute o notebook `01_processamento_e_limpeza.ipynb` para gerar os dados tratados.
6.  Execute os demais notebooks de análise.