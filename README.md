# Análise e Visualização de Chamadas de Emergência 911

Este repositório contém um projeto académico desenvolvido no âmbito da unidade curricular de Apresentação e Visualização de Informação.

O projeto tem como tema a análise de chamadas de emergência 911, recorrendo a um dataset com informação sobre ocorrências, localização geográfica, códigos postais, municípios, datas, horas e tipos de emergência. O objetivo principal é transformar estes dados em informação visual útil para apoiar a tomada de decisão por parte de gestores de resposta a emergências e entidades locais/governamentais.

## Objetivo do projeto

O principal objetivo do projeto é analisar padrões associados às chamadas de emergência, identificando tendências temporais, tipos de ocorrência mais frequentes, variações geográficas e possíveis relações entre o número de chamadas e o tempo médio de resposta.

A solução desenvolvida procura apoiar decisões relacionadas com:

- alocação de recursos de emergência;
- identificação de zonas com maior incidência de chamadas;
- análise dos horários e períodos com maior frequência de ocorrências;
- apoio ao planeamento de equipas, turnos e recursos;
- melhoria da resposta a situações de emergência.

## Dataset

O projeto utiliza um dataset de chamadas de emergência 911, contendo atributos como:

- latitude;
- longitude;
- descrição da ocorrência;
- código postal;
- tipo de ocorrência;
- data e hora da chamada;
- município;
- endereço;
- variável auxiliar.

## Tecnologias utilizadas

Foram utilizadas várias ferramentas ao longo do projeto:

- Python;
- Jupyter Notebook;
- PySpark;
- Docker;
- HDFS;
- Hive Metastore;
- Trino/PrestoSQL;
- Tableau.

## Processamento dos dados

O processamento dos dados foi organizado em três camadas principais:

### Bronze

Camada onde os dados originais são armazenados sem alterações.

### Silver

Camada onde são aplicadas transformações, limpeza e preparação dos dados.

### Gold

Camada final, com os dados já tratados e organizados para análise e visualização nas dashboards.

## Visualização dos dados

A visualização foi desenvolvida em Tableau, através de dashboards interativas orientadas para dois públicos-alvo:

1. Gestores de resposta a emergências;
2. Entidades locais e governamentais.

As dashboards permitem analisar:

- variação das chamadas por mês, dia da semana e hora;
- tipos de ocorrência mais comuns;
- distribuição geográfica das chamadas;
- frequência de chamadas por código postal;
- relação entre tempo médio de resposta e número de chamadas.

## Ficheiros do repositório

- `911.csv` — ficheiro csv original;
- `911.ipynb` — notebook com o processamento dos dados;
- `dashboards de analise de chamadas de emergencia.twb` — ficheiro Tableau com as dashboards;
- `AVI_M1_TP2_GRUPO6.pdf` — relatório do Momento 1;
- `AVI_M2_TP2_GRUPO6.pdf` — relatório do Momento 2;
- `AVI_M3_TP2_GRUPO6.pdf` — relatório do Momento 3.

## Como executar

Para consultar o projeto, basta abrir os relatórios PDF e o ficheiro Tableau.

Para executar o processamento de dados, é necessário abrir o ficheiro `911.ipynb` num ambiente Jupyter com PySpark configurado.

O notebook pressupõe a existência de um ambiente com Docker, HDFS, Hive Metastore e ferramentas associadas ao processamento distribuído de dados.

## Autoria

Projeto desenvolvido pelo Grupo 6 no âmbito da unidade curricular de Apresentação e Visualização de Informação.
