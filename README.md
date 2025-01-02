# Análise do Preço de Venda da Gasolina em São Paulo - Julho de 2021

Este projeto realiza a análise do preço de venda da gasolina nos 10 primeiros dias de julho de 2021 na cidade de São Paulo. Ele gera um gráfico que mostra a variação dos preços durante este período e salva o gráfico em formato PNG.

## Objetivo

O objetivo deste projeto é analisar e visualizar a variação diária do preço da gasolina durante os 10 primeiros dias de julho de 2021. Para isso, o código utiliza um conjunto de dados simples contido em um arquivo CSV (`gasolina.csv`), que inclui o preço de venda da gasolina a cada dia. A partir desse arquivo, é gerado um gráfico de linha que exibe a evolução dos preços.

## Tecnologias Utilizadas

- **Python**: Linguagem de programação utilizada.
- **Pandas**: Biblioteca para manipulação e análise de dados.
- **Seaborn**: Biblioteca para criação de gráficos.
- **Matplotlib**: Biblioteca para visualização de dados.

## Arquivos

- `gasolina.csv`: Arquivo CSV contendo os dados diários do preço de venda da gasolina.
- `gasolina.png`: Imagem gerada contendo o gráfico de preço da gasolina.

## Como Rodar

1. Clone este repositório ou baixe os arquivos para o seu computador:
    ```bash
    git clone https://github.com/seu-usuario/nome-do-repositorio.git
    ```

2. Instale as dependências necessárias (se ainda não tiver as bibliotecas instaladas):
    ```bash
    pip install pandas seaborn matplotlib
    ```

3. Execute o script Python para gerar o gráfico:
    ```bash
    python script.py
    ```

    **Nota**: O arquivo `gasolina.csv` deve estar no mesmo diretório que o script Python ou você pode modificar o caminho do arquivo no código.

## Como Funciona

O código realiza as seguintes etapas:

1. **Carregamento dos dados**: Carrega o arquivo `gasolina.csv`, que contém os preços diários da gasolina.
2. **Criação do gráfico**: Utiliza o `Seaborn` e o `Matplotlib` para gerar um gráfico de linha, que mostra como o preço da gasolina variou ao longo dos 10 primeiros dias de julho de 2021.
3. **Salvamento e Exibição do Gráfico**: O gráfico gerado é salvo no formato PNG e também é exibido para o usuário.

## Exemplo de Saída

Após a execução do script, o gráfico gerado será salvo como `gasolina.png` e exibido na tela. O gráfico terá o título "Preço de Venda da Gasolina em São Paulo - 10 primeiros dias de Julho de 2021", com o preço da gasolina no eixo Y e os dias no eixo X.

## Contribuições

Contribuições são bem-vindas! Se você deseja melhorar este projeto ou adicionar novos recursos, sinta-se à vontade para abrir um *pull request*.

## Licença

Este projeto está licenciado sob a Licença MIT - veja o arquivo [LICENSE](LICENSE) para mais detalhes.
