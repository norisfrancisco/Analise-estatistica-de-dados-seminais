# Análise Estatística de Dados Seminais

Este repositório reúne os scripts em **R** utilizados para análise estatística de dados seminais, com foco na comparação entre diferentes tratamentos experimentais.

**Importante**: Os dados brutos, gráficos e arquivos de saída (.xlsx, .png, .txt) são **confidenciais** e não estão disponíveis neste repositório. Esses arquivos foram excluídos intencionalmente via `.gitignore`.

## Objetivo

O objetivo deste projeto é realizar uma análise estatística completa dos dados, incluindo:

- Comparações entre grupos experimentais
- Visualizações com letras de significância (teste de Tukey)
- Correlações entre variáveis
- Análise de Componentes Principais (PCA)

## Estrutura do Projeto

Analise-estatistica-de-dados-seminais/
├── analise_dados_seminais.Rmd # Arquivo principal com o código da análise
├── .gitignore # Arquivos e pastas ignorados no versionamento
├── dados/ # (Omitido) Dados de entrada
├── plots/ # (Omitido) Gráficos gerados
├── resultados/ # (Omitido) Saídas de testes estatísticos

##  Técnicas Utilizadas

- **ANOVA** e **Teste de Tukey HSD** (`agricolae`)
- **Gráficos de barras com letras de significância** (`ggplot2`, `ggpubr`)
- **Matriz de correlação** (`corrplot`)
- **Análise de Componentes Principais (PCA)** (`FactoMineR`, `factoextra`)
- Organização visual com `patchwork` e temas personalizados

## Como Executar

Instale os pacotes necessários:

```r
install.packages(c(
  "readxl", "dplyr", "ggplot2", "ggpubr", "agricolae",
  "patchwork", "corrplot", "RColorBrewer",
  "FactoMineR", "factoextra"
))

## Técnicas Utilizadas

- **ANOVA** e **Teste de Tukey HSD** (`agricolae`)
- **Gráficos de barras com letras de significância** (`ggplot2`, `ggpubr`)
- **Matriz de correlação** (`corrplot`)
- **Análise de Componentes Principais (PCA)** (`FactoMineR`, `factoextra`)
- Organização visual com `patchwork` e temas personalizados

## Como Executar

Instale os pacotes necessários:

```r
install.packages(c(
  "readxl", "dplyr", "ggplot2", "ggpubr", "agricolae",
  "patchwork", "corrplot", "RColorBrewer",
  "FactoMineR", "factoextra"
))

## Técnicas Utilizadas

- **ANOVA** e **Teste de Tukey HSD** (`agricolae`)
- **Gráficos de barras com letras de significância** (`ggplot2`, `ggpubr`)
- **Matriz de correlação** (`corrplot`)
- **Análise de Componentes Principais (PCA)** (`FactoMineR`, `factoextra`)
- Organização visual com `patchwork` e temas personalizados

## Como Executar

Instale os pacotes necessários:

```r
install.packages(c(
  "readxl", "dplyr", "ggplot2", "ggpubr", "agricolae",
  "patchwork", "corrplot", "RColorBrewer",
  "FactoMineR", "factoextra"
))

Para gerar o relatório, execute:
rmarkdown::render("analise_dados_seminais.Rmd")
👤 Autor
Francisco Noris
Análise estatística de dados experimentais utilizando R.

Licença
Uso restrito. Os dados e resultados gráficos são confidenciais e não estão disponíveis publicamente.
