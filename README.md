# mini-projeto
Análise de Dados — Base Varejo
Insights obtidos da análise dos dados
1. Dimensão da base de dados

A base analisada contém 830.000 registros, 1.000 clientes únicos e 229 produtos distintos. Essa dimensão permite explorar diferentes características dos clientes e dos produtos. Como cada cliente pode aparecer em vários registros, o total de registros não representa a quantidade de clientes individuais.

2. Predominância de registros de clientes sem filhos

A análise da coluna CL_FHL identificou 435.501 registros com zero filhos, aproximadamente 52,47% do total. Esse é o grupo mais frequente da distribuição e representa mais da metade dos registros analisados.

3. Média e mediana do número de filhos

A média do número de filhos foi de 1,15, enquanto a mediana foi igual a zero. Isso indica que pelo menos metade dos registros possui valor zero nessa variável. A diferença entre média e mediana é explicada pela distribuição dos valores, na qual os registros com filhos elevam a média.

4. Distribuição dos registros entre um e quatro filhos

Foram identificados 102.813 registros com um filho, 106.622 com dois filhos, 104.685 com três filhos e 80.379 com quatro filhos. Entre esses grupos, o valor de dois filhos foi o mais frequente. A quantidade de registros diminui no grupo de quatro filhos em comparação aos grupos de um, dois e três filhos.

5. Dispersão e amplitude dos dados

O número de filhos varia de zero a quatro, com desvio padrão de aproximadamente 1,42. O primeiro quartil e a mediana são iguais a zero, enquanto o terceiro quartil é igual a dois. Esses indicadores demonstram a concentração de registros nos valores mais baixos e a variação existente entre os perfis familiares representados na base.

Conclusão
O projeto permitiu aplicar técnicas de limpeza, transformação e estatística descritiva utilizando Python e Pandas. A análise da variável CL_FHL revelou a predominância de registros com zero filhos, média de 1,15 e valores observados entre zero e quatro. Os resultados demonstram a importância da estatística descritiva para resumir e interpretar os dados.

É importante considerar que a análise foi realizada sobre os 830.000 registros da base, e não necessariamente sobre 830.000 pessoas diferentes. Como existem 1.000 clientes únicos, análises sobre o perfil individual dos clientes devem considerar uma observação por cliente, verificando previamente a consistência dos dados.