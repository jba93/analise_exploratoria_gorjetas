# Analisando gorjetas
Projeto realizado no curso Data Visualization: explorando com Seaborn (prof. Guilherme Lima - Alura).

- Importamos os dados referentes as gorjetas de um arquivo .csv, transformamo-os em DataFrame e os traduzimos, já que estavam em inglês.
- Instalamos a biblioteca Seaborn para a plotagem de gráficos.
- Analisamos o valor da conta x gorjeta através de um gráfico de dispersão (scatterplot) e procuramos por valores nulos na base de dados importada.
- Criamos um novo campo no DataFrame, o "Porcentagem", para entender qual o percentual do total da conta que corresponde a gorjeta.
- Com o novo campo foi possível plotar mais alguns gráficos para verificar se o valor da gorjeta é proporcional ao valor total da conta ou não.
- Aanlisamos o campo Sobremesa e realizamos seu teste de hipótese. Para o Teste de Hipótese, baixamos o ranksums da biblioteca SciPy, que faz o cálculo do p-value e assim, podemos seguir com uma ou outra hipótese definida.
- Analisamos o campo Dia da Semana e realizamos seu teste de hipótese.
- Analisamos o campo Refeicao e realizamos seu teste de hipótese com relação ao valor da conta e também com relação ao valor da gorjeta.
