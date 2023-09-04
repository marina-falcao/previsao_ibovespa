# previsao_ibovespa
Aplicar modelos de ML para prever o comportamento do índice Ibovespa.  

**O que é o IBOVESPA?**

O Ibovespa é o principal índice da Bolsa de Valores de São Paulo (B3). Ele funciona como um termômetro do mercado acionário do Brasil e mede, através de um sistema de pontos baseado em reais, o desempenho médio de uma carteira teórica com as ações mais representativas e negociadas em Bolsa. Essa carteira teórica é reavaliada a cada 4 meses pela B3. Os principais critérios para que uma empresa faça parte do índice é ter uma boa liquidez e grande volume financeiro negociado em Bolsa.

Algumas das empresas que compõem o Ibovespa em set/2023 são: Bradesco, Alpargatas, Ambev, Arezzo, Assai, Carrefour, Cielo, entre outras. Podemos perceber que as empresas atuam em mercados distintos, e qualquer alteração nesses mercados pode alterar as ações da empresa e, consequentemente, o índice.

Além disso, o peso de cada uma das ações na pontuação do índice Ibovespa pode diferir e variar, conforme o volume de ativos de uma mesma empresa presente na composição da carteira. Ou seja, se o índice subir, não significa que, necessariamente, todas as ações que compõem a carteira tiveram alta, já que alguns ativos possuem maior peso do que outros e ajudam a puxar o índice para cima ou para baixo.

A previsão do IBOVESPA é relevante para entendermos melhor o comportamento do mercado de ações e tomarmos decisões mais assertivas no investimento de nossos ativos.

Fonte: https://www.b3.com.br/pt_br/market-data-e-indices/indices/indices-amplos/indice-ibovespa-ibovespa-composicao-da-carteira.htm (Acesso em 04/09/2023)

**Janela temporal**

Optamos por analisar dados do último ano (**30/08/2022 a 30/08/2023**), para verificar oscilações e padrões anuais da base. Caso usássemos dados dos últimos 2 ou 3 anos, teríamos o comportamento da pandemia como início da base, e esses dados provavelmente não mostrariam o comportamento padrão do mercado, por isso optamos por uma janela de análise mais curta. É importante também considerar que a variação inflacionária dos últimos anos e as eleições presidenciais de 2022 podem ter influência nas variações do índice. 
