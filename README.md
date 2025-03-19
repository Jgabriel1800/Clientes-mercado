Nesse projeto foi utilizado um DataFrame fictício de uma loja, contendo dados de todos os clientes. Nosso objetivo era entender qual era o público-alvo do estabelecimento e, a partir disso, gerar diferentes tipos de cartões de fidelidade: Comum, Médio e Premium.

CRIAÇÃO: 
- Entendemos qual era o número de homens e mulheres clientes da loja.
- Analisamos a idade do público para identificar a faixa etária predominante.
- Identificamos a profissão de todos os clientes para entender em que áreas trabalhavam.
- Comparamos a profissão com a renda anual.
- Calculamos o custo por pessoa em uma família, considerando a relação entre renda anual e número de integrantes.
- Analisamos como os anos de experiência influenciam no salário anual de cada indivíduo.
- Estudamos como o salário de cada cliente influencia no seu score de compras na loja. A partir disso, conseguimos entender qual era o nosso público-alvo.
- Identificamos a idade com maior score dentro da loja para determinar a faixa etária mais engajada.
- Analisamos quais profissões apresentavam os maiores scores na loja para entender quais áreas traziam maior retorno.
  - Criamos um cluster separando os clientes de acordo com seu salário e score de compras na loja, possibilitando a disponibilização dos cartões de fidelidade.

TECNOLOGIAS UTILIZADAS:
-Python
-Google colab
-Bibliotecas: Pandas, plotly, matplotlib e Numpy

HABILIDADES UTILIZADAS:
-Análise de dados
-Manipulação de dados
-visualização de dados
-Lógica de programação
-Habilidades analiticas

RESULTADOS:
- A grande maioria dos clientes são mulheres.
- A maioria das mulheres tem entre 30 e 69 anos, enquanto os homens estão entre 20 e 69 anos.
- As três profissões mais comuns para homens e mulheres são: artistas, assistência médica e área do entretenimento.
- As três profissões menos comuns para homens são: dono(a) de casa, marketing e advocacia. Para mulheres, são: dono(a) de casa, marketing e medicina.
- Os três maiores salários anuais para homens são encontrados em engenharia, entretenimento e medicina. Para mulheres, em cargo executivo, assistência médica e engenharia.
- Famílias com 1 a 7 integrantes possuem um salário médio anual acima de R$100.000. Entretanto, famílias com 8 ou 9 integrantes apresentam uma queda significativa na renda média anual, sendo R$68.000 e R$30.000, respectivamente.
- Clientes com salários entre R$150.000 e R$200.000 têm os maiores scores médios na loja. Já os clientes com salários entre R$75.000 e R$100.000 possuem os menores scores.
- Clientes com idade entre 26 e 35 anos apresentam os maiores scores na loja, enquanto o menor score médio está na faixa 36 a 45 anos.
- Profissionais das áreas de artes e entretenimento têm os maiores scores, enquanto dono(a) de casa possui o menor score, com uma diferença bastante relevante.
- Famílias com menos integrantes tendem a apresentar scores mais elevados em comparação com famílias maiores.
- Clientes Premium representam 34,1% dos clientes da loja, clientes Médios são 36,6% e clientes de baixo consumo correspondem a 29,3%.
- Filtrando os clientes Premium para considerar apenas aqueles com scores e salários altos, identificamos 127 clientes potenciais para a empresa.

