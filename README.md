# Pipeline de Dados para ETL

Este projeto de exemplo de pipeline de dados no modelo ETL visa implementar a arquitetura de medalhão para armazenamento dos dados em diferentes camadas, de acordo com seu nível de processamento.

Os dados brutos são armazenados na calada Bronze;
Dados com algum tipo de tratamento ou limpeza ficam na camada Prata;
Já os dados que contém agregações ou filtros, que facilitam análises, são alocados na camada Ouro.

Também há o objetivo de implantar um modelo de Machine Learning a partir dos dados coletados e armazenados.
