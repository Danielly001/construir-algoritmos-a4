# Atividade 4 | Modelagem Preditiva para Avaliação Imobiliária

Contexto:
A imobiliária Lar Perfeito está em processo de modernização do seu sistema de avaliação de imóveis. Historicamente, os preços eram estimados de forma intuitiva pelos corretores, o que resultava em distorções significativas nos valores de anúncio e inconsistência no mercado. Para mitigar esse problema e padronizar o processo, o departamento de dados coletou uma amostra de 500 vendas recentes ocorridas no mesmo bairro.

O Desafio:
O objetivo desta atividade é desenvolver um modelo de regressão linear capaz de explicar a variação do preço de venda com base nas características estruturais dos apartamentos.&nbsp;

Dados Disponíveis:
Você recebeu um arquivo CSV (imoveis_lar_perfeito.csv) contendo as seguintes variáveis:
- id_imovel: Identificador único da transação (deve ser desconsiderado na modelagem).
- area_util_m2: Área útil do apartamento em metros quadrados (variável preditora).
- quantidade_quartos: Número de quartos do imóvel (variável preditora).
- preco_venda: Valor final da venda em Reais (variável alvo/dependente).

Sua Tarefa:
Utilizando as técnicas de regressão linear múltipla, determine a equação que melhor estima o preço de venda dos imóveis. Sua resposta deve apresentar:

A Equação do Modelo: Apresente a fórmula final na forma:
- $\text{Preco} = \beta_0 + \beta_1 * \text{Area} + \beta_2 * \text{Quartos}$
- Onde $beta_0$ é o intercepto e $beta_1$, $beta_2$ são os coeficientes angulares encontrados.

Resolva esta atividade com o conhecimento de matrizes e numpy. Deverá ser desenvolvida uma função que receberá um arquivo e retornará uma lista com 3 valores. Algumas dicas:
- Utilize a função `read_csv` do `pandas` para a leitura do `csv`;
- Para ler cada coluna poderá definir o conjunto de dados, selecionar a coluna e aplicar o método `to_list()`: `df["coluna"].to_list()`

Deverá ser enviado o link do fork deste repositório.
