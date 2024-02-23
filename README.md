# Sentiment Analysis and Natural Language Processing for Marketing

## O que é Natural Language Processing?
Natural language processing (NLP) é, de forma simplificada, a habilidade do computador/sistema/máquina entender linguagem humana e processá-la da mesma forma como os humanos fazem.

## Resumo
Um dos principais objetivos de uma equipe de growth hacking é aumentar o crescimento massivo de startups iniciantes em pouco tempo. Para isso, são introduzidas estratégias com a ajuda das quais é possível adquirir o maior número possível de clientes com o menor custo possível. Fazendo parte da Equipe de Growth Hacking de uma startup recém-lançada que está introduzindo um produto no mercado e como parte da estratégia de growth hacking da sua equipe, a diretoria deseja mapear o campo do mercado de produtos para Pet. O objetivo é descobrir como os clientes avaliam os produtos dos seus concorrentes, ou seja, o que eles gostam e não gostam em produtos para Pet. Saber o que torna um produto atrativo para um pet ou para seu tutor ajuda a equipe de marketing a articular a mensagem do seu produto de forma mais eficaz.

Para ser capaz de descobrir o que torna um produto digno de compra de acordo com os tutores é preciso obter insights mais profundos sobre as características linguísticas de suas falas. Com conhecimento em NLP, a tarefa será analisar as avaliações dos clientes sobre o produto. Para realizar essa tarefa, serão utilizadas diferentes métodos de NLP. Esses métodos permitirão adquirir uma compreensão mais profunda do feedback e da opinião dos clientes.

O fluxo da tarefa, como responsável por Dados da Equipe de Growth Hacking, é:
- Baixar o conjunto de dados das avaliações da Amazon.
- Criar conjunto próprio de dados a partir das avaliações da Amazon.
- Decidir se as pessoas gostam ou não do que compraram. Rotular cada avaliação com uma pontuação de sentimento entre -1 e 1.
- Verificar o desempenho do analisador de sentimentos comparando as pontuações de sentimento com as das avaliações dos reviews.
- Avaliar o desempenho do analisador de sentimentos e descobrir se você conseguiu rotular corretamente as avaliações.
- Experimentar outros métodos de análise de sentimento.
- Explorar como as pessoas avaliam o produto que compraram, classificando as avaliações como positivas, negativas e neutras.
- Resumir resultados para a diretoria da Equipe de Growth Hacking.
- Com base nas descobertas, listar as coisas que são preferidas e as que não são sobre os produtos.

## Técnicas Usadas
Para obter uma compreensão mais profunda da opinião das pessoas sobre produtos do mercado Pet, serão utilizadas diversas técnicas de NLP. Aqui está uma lista resumida do que será feito e quais técnicas serão utilizadas
- Amostragem de conjuntos de dados desbalanceados usando o pacote imbalanced-learn.
- Investigação sobre o valor de sentimento das avaliações com ferramentas de análise de sentimento baseadas em dicionário, que fazem parte do NLTK, um conjunto de ferramentas de processamento de linguagem natural usado em Python.
- Verificar se o algoritmo fez um bom trabalho. Avaliação de dados com scikit-learn em Python.
- Analisar as avaliações com uma técnica de aprendizado profundo de ponta, chamada de DistilBERT. Para construir este modelo, será preciso executar pacotes como Pytorch e Transformadores.
- Avaliar o modelo e criar estatísticas descritivas em Python com a biblioteca scikit-learn antes de relatar resultados para diretoria.
- Visualizar descobertas sobre palavras preferíveis e não preferíveis relacionadas ao mercado Pet usando Altair.

## Fluxo do Projeto
O projeto inicialmente é esboçado em 5 passos:
- [Criar o dataset](https://github.com/berggama/Sentiment-analysis-for-marketing/blob/main/Criar_o_dataset.ipynb);
- [Criar um analisador de sentimentos baseado em dicionário](https://github.com/berggama/Sentiment-analysis-for-marketing/blob/main/Criando_um_Analisador_de_Sentimento_baseado_em_dicion%C3%A1rio.ipynb);
- [Avaliar o desempenho do analisador](https://github.com/berggama/Sentiment-analysis-for-marketing/blob/main/Avaliar_o_desempenho_do_analisador%3B.ipynb);
- Criar uma analisador de sentimento baseado em rede-neural;
- Reportar os resultados;

