# Avaliador de Ações com base em Fundamentos
Este script Python realiza uma análise fundamentalista de ações da B3 utilizando os dados do site Fundamentus. O objetivo é pontuar e ranquear ações com base em critérios quantitativos de qualidade e valuation.

⚙️ Funcionalidades
Conecta-se automaticamente ao Fundamentus e carrega os dados financeiros das empresas listadas na bolsa.

Aplica critérios básicos e avançados para avaliar a qualidade da empresa, tais como:

Dividend Yield

Preço/Lucro (P/L)

ROE, ROIC, Margem Líquida

Endividamento, Liquidez, Crescimento de Receita

Para cada critério atendido, a empresa recebe 1 ponto.

Ao final, exibe a pontuação de cada empresa e gera um ranking comparativo.

⚠️ Penalidade
Se uma ação apresentar Dividend Yield abaixo de 6%, ela recebe uma penalização automática, tendo sua pontuação total reduzida em 50%.
