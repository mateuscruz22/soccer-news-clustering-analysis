# Análise de Técnicas de Agrupamento Aplicadas a Notícias de Futebol do Campeonato Brasileiro de Futebol

Este repositório contém o código e os principais arquivos relacionados ao Trabalho de Conclusão de Curso (TCC) com o tema "Análise de Técnicas de Agrupamento de Dados para Notícias de Futebol". O objetivo deste trabalho é explorar e comparar técnicas de agrupamento, incluindo k-means, agrupamento hierárquico, DBSCAN e modelo de mistura gaussiana, aplicadas a notícias do Campeonato Brasileiro de Futebol.

## Etapas do Trabalho

1. **Pré-processamento:**
   - Tokenização
   - Remoção de stop words
   - Derivação, entre outros

2. **Representação de Notícias:**
   - Utilização de Bag of Words e TF-IDF para representação textual

3. **Redução de Dimensionalidade:**
   - Aplicação da técnica LSA (Latent Semantic Analysis) para redução de dimensionalidade

4. **Agrupamento de Notícias:**
   - Utilização de diferentes algoritmos, como k-means, modelo de mistura gaussiana, agrupamento hierárquico e DBSCAN
   - Definição de 21 clusters, representando os times do campeonato

5. **Avaliação dos Resultados:**
   - Análise da acurácia, sendo destacados os melhores resultados obtidos pelo k-means e modelo de mistura gaussiana (75%), seguidos pelo agrupamento hierárquico (70%)

## Resultados e Conclusões

Os resultados sugerem que o k-means e o modelo de mistura gaussiana são eficazes para agrupar notícias de futebol, proporcionando uma acurácia de 75%. O agrupamento hierárquico também apresenta bons resultados, enquanto o DBSCAN enfrenta desafios na formação de 21 clusters.

Este trabalho pode servir como base para trabalhos futuros, contribuindo para a extração de padrões ocultos nos dados.

Sinta-se à vontade para explorar o código e os arquivos disponíveis neste repositório. Dúvidas e sugestões são sempre bem-vindas!
