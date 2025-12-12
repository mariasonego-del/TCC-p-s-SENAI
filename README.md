# README --- Consolidação de Planilhas e Previsão de Horas dos Colaboradores

## Descrição do Projeto

Este projeto automatiza a consolidação de dados de atividades de
colaboradores horistas a partir de uma planilha Excel e realiza
previsões de horas futuras utilizando um modelo de Machine Learning
Random Forest Regressor.

O projeto executa três etapas principais:

1.  Consolidação da planilha de atividades\
2.  Treinamento do modelo e previsão\
3.  Geração de gráficos individuais e relatório visual de riscos

## Arquivos do Projeto

  --------------------------------------------------------------------------
  Arquivo                                Função
  -------------------------------------- -----------------------------------
  consolidação_planilha_e\_previsão.py   Script completo que consolida
                                         planilhas, treina o modelo e gera
                                         resultados

  Planilha de entrada (.xlsx)            Base bruta com atividades dos
                                         colaboradores

  \*\_Consolidado_por_Colaborador.xlsx   Consolidação mensal gerada

  Previsoes_Professores.xlsx             Previsões e classificação de risco

  graficos_previsoes.zip                 Conjunto de gráficos
  --------------------------------------------------------------------------

## Requisitos

-   Google Colab\
-   pandas\
-   numpy\
-   scikit-learn\
-   matplotlib\
-   openpyxl\
-   google.colab

## Como Executar

1.  Abrir o Google Colab\
2.  Importar o arquivo .py\
3.  Executar o notebook\
4.  Enviar a planilha consolidada quando solicitado\
5.  Baixar os arquivos gerados automaticamente

## Classificação de Risco

-   Risco de Excesso: média das previsões \> 120 horas\
-   Risco de Baixa Alocação: média das previsões \< 10 horas

## Resultados Esperados

-   Previsões de carga de trabalho\
-   Identificação de sobrecarga ou subutilização\
-   Planilhas estruturadas\
-   Gráficos para análise e apresentação
