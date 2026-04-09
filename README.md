# Gastos Parlamentares (2026)

Análise Exploratória de Dados focada em investigar o uso do dinheiro público na cota parlamentar, especificamente na categoria de Combustíveis e Lubrificantes.

- Bibliotecas e ferrametas utilizadas -
Python | Pandas | Matplotlib | Numpy | Google Colab

##  O Projeto
O script processa uma base de dados real do governo seguindo estas etapas:
1. **Limpeza e Filtro:** Isolamento das despesas com combustíveis e remoção de dados inválidos.
2. **Análise:** Uso da função groupby para cruzar o CNPJ dos fornecedores com os valores pagos.
3. **Visualização:** Identificação e plotagem do ranking com o **Top 3 postos de gasolina que mais faturaram**.

##  Como Executar
1. Clone este repositório.
2. Coloque o arquivo de dados original (`Ano-2026.csv`) na mesma pasta.
3. Execute o script em um ambiente com pandas, numpy e matplotlib instalados.
