## **Projeto de Classificação de Score de Crédito**

**Contexto**
 
Este projeto foi desenvolvido durante o Bootcamp [RE]Start – Trilha de Analista de Dados com o objetivo de analisar e classificar scores de crédito. A proposta foi construir um pipeline completo de dados, da leitura à geração de insights, simulando o papel de um analista em uma fintech fictícia interessada em entender melhor o perfil financeiro de seus clientes e os fatores relacionados ao risco de crédito.
As principais perguntas que guiaram a análise foram:
Qual perfil apresenta maior risco de inadimplência?
Quais fatores estão mais associados a clientes com pontuação ruim?
Existe relação entre renda, dívida, histórico financeiro e score de crédito?
Clientes com maior número de empréstimos apresentam maior risco?

**Conjunto de Dados**

O dataset utilizado foi o Credit Score Classification, disponível no Kaggle:
https://www.kaggle.com/datasets/parisrohan/credit-score-classification
Ele contém informações financeiras e comportamentais dos clientes, incluindo renda anual e mensal, número de contas bancárias, número de cartões de crédito, quantidade de empréstimos, histórico de crédito, dívidas, consultas de crédito e pontuação de crédito.

**Tecnologias**

Python (Pandas, NumPy)
Google Colab
Power BI
Git e GitHub

 **Pipeline**
 
- Leitura e exploração inicial: análise da estrutura dos dados, tipos de colunas, distribuição das variáveis e identificação de valores ausentes.
- Limpeza e preparação: tratamento de valores ausentes, correção de tipos, remoção de caracteres inválidos, padronização de variáveis financeiras, tratamento de outliers e criação da variável Credit_History_Age_Clean.
- Análise exploratória: investigação da relação entre score e variáveis financeiras como renda mensal, dívida média, histórico de crédito e número de empréstimos.
- Dashboard no Power BI: visualização interativa com métricas de clientes, classificação por risco, renda e dívida médias, distribuição de pontuação e comparativos por score.

**Insights**

Clientes classificados como Pobres possuem aproximadamente 2,6 vezes mais dívida média do que os classificados como Bom.
Clientes Bom têm em média 8 anos a mais de histórico de crédito em relação aos Ruim.
A renda média dos clientes Bom é cerca de 50% maior do que a dos Ruim.
O número médio de empréstimos cresce conforme o score piora.
O aumento da dívida acompanha diretamente a piora do score, reforçando a associação entre endividamento e risco.
Mais da metade da carteira está na categoria Standard, o que abre espaço para estratégias de evolução para menor risco.

**Recomendações**

Adotar políticas de crédito mais conservadoras para clientes com alto nível de endividamento.
Criar programas de educação financeira voltados para clientes classificados como Pobres.
Incorporar histórico de crédito e quantidade de empréstimos como critérios relevantes na concessão.
Desenvolver estratégias específicas para clientes Standard, evitando migração para categorias de maior risco.

**Resultados**

O projeto resultou em um pipeline completo de análise de dados, incluindo leitura e preparação dos dados, análise exploratória, dashboard interativo e recomendações de negócio. Além do aprendizado técnico, foi uma oportunidade de praticar storytelling com dados e transformar informações em recomendações acionáveis.

**Sobre mim**

Sou Camila de Jesus Fontes, profissional em transição para a área de dados. Atualmente atuo como Analista de Dados, aprofundando meus conhecimentos em Analytics, AWS e visualização de dados. Este projeto representa uma etapa importante na minha jornada de aprendizado e consolidação das habilidades adquiridas.

**Arquivos**

Notebook com o pipeline completo
Dashboard em Power BI (.pbix)
Dashboard exportado em PDF
Dataset tratado utilizado na análise
