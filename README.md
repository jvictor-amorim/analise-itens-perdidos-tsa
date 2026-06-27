# Análise de Itens Perdidos em Aeroportos (TSA Claims - 2014)

## Sobre o Projeto
Este projeto consiste em uma Análise Exploratória de Dados (EDA) desenvolvida em **R**. O estudo analisa dados referentes a bagagens e itens perdidos em aeroportos no ano de 2014, baseando-se em registros da TSA (Transportation Security Administration). 

O relatório gerado responde a perguntas sobre os itens mais frequentemente perdidos, períodos de maior incidência, principais aeroportos envolvidos, tempo de retenção e valores estimados das perdas.

## Tecnologias e Bibliotecas Utilizadas
- **R / RStudio**
- **RMarkdown**: Para geração do relatório web (`index.Rmd` -> `index.html`).
- **Pacotes R**:
  - `dplyr`, `tidyr`: Manipulação e tratamento de dados.
  - `ggplot2`: Criação de gráficos.
  - `DT`, `knitr`: Geração de tabelas interativas.
  - `rmdformats`: Tema e formatação visual do HTML.
  - `readxl`, `readr`: Importação e leitura de arquivos (`.xls` e `.csv`).

## Como Executar
1. Certifique-se de ter o **R** e o **RStudio** instalados em sua máquina.
2. Clone este repositório:
   ```bash
   git clone https://github.com/JoaoSilvAmorim/projeto_dados.git
   ```
3. Abra o projeto no RStudio clicando no arquivo `analise-de-dados-em-R.Rproj`.
4. Instale as dependências executando no console do R:
   ```R
   install.packages(c("rmdformats", "ggplot2", "dplyr", "DT", "knitr", "tidyr", "readxl", "readr"))
   ```
5. Abra o arquivo `index.Rmd` e clique no botão **"Knit"** para gerar a visualização completa ou abra o arquivo `index.html` em seu navegador para ver a versão já processada.

## Autores
- João Victor Silva de Amorim