Projeto de Classificação de Score de Crédito
📌 Sobre o projeto

Durante o Bootcamp [RE]Start – Trilha de Analista de Dados, desenvolvi este projeto com o objetivo de realizar uma análise completa sobre classificação de score de crédito, passando por todas as etapas de um pipeline de dados: leitura, limpeza, exploração, visualização e geração de insights de negócio.

Neste cenário, assumi o papel de analista de dados em uma fintech fictícia interessada em compreender melhor o perfil financeiro de seus clientes e identificar fatores associados ao risco de crédito.

O objetivo principal foi responder perguntas importantes para o negócio, como:

Qual perfil apresenta maior risco de inadimplência?
Quais fatores estão mais associados a clientes com score Poor?
Existe relação entre renda, dívida, histórico financeiro e score de crédito?
Clientes com maior número de empréstimos apresentam maior risco?
📂 Dataset

Para este projeto utilizei o dataset Credit Score Classification, disponibilizado no Kaggle:

https://www.kaggle.com/datasets/parisrohan/credit-score-classification

O conjunto de dados contém informações financeiras, cadastrais e comportamentais dos clientes, incluindo:

renda anual e mensal;
número de contas bancárias;
número de cartões de crédito;
quantidade de empréstimos;
histórico de crédito;
dívidas;
consultas de crédito;
score de crédito.
⚙️ Tecnologias utilizadas

Durante o desenvolvimento utilizei:

Python
Pandas
NumPy
Google Colab
Power BI
Git e GitHub
🔄 Pipeline desenvolvido
1️⃣ Leitura e exploração inicial

Iniciei o projeto realizando a leitura do dataset e uma análise exploratória inicial para compreender:

estrutura dos dados;
tipos das colunas;
distribuição das variáveis;
existência de valores ausentes e inconsistências.
2️⃣ Limpeza e preparação dos dados

Esta foi uma das etapas mais importantes do projeto.

Durante a limpeza realizei:

tratamento de valores ausentes;
correção de tipos de dados;
remoção e tratamento de caracteres inválidos (_);
tratamento de valores negativos e inconsistentes;
padronização de variáveis financeiras;
tratamento de outliers;
criação da variável Credit_History_Age_Clean, utilizada para representar o histórico de crédito em anos.
3️⃣ Análise Exploratória dos Dados (EDA)

Após a preparação dos dados, investiguei a relação entre score de crédito e variáveis financeiras relevantes, buscando identificar padrões associados ao risco de crédito.

As principais análises envolveram:

renda mensal;
dívida média;
histórico de crédito;
número de empréstimos;
distribuição dos scores de crédito.
4️⃣ Desenvolvimento do Dashboard

Para comunicar os resultados desenvolvi um dashboard interativo no Power BI contendo:

total de clientes analisados;
clientes classificados como alto risco;
renda média mensal;
dívida média;
distribuição do score de crédito;
renda média por score;
dívida média por score;
histórico médio de crédito por score;
número médio de empréstimos por score;
principais insights obtidos durante a análise.

O dashboard final encontra-se abaixo:

📈 Principais insights encontrados

Durante a análise identifiquei alguns padrões importantes:

Clientes classificados como Poor possuem aproximadamente 2,6 vezes mais dívida média do que clientes classificados como Good.
Clientes classificados como Good possuem cerca de 8 anos adicionais de histórico de crédito em comparação aos clientes classificados como Poor.
A renda média dos clientes Good é aproximadamente 50% maior do que a renda média dos clientes Poor.
O número médio de empréstimos aumenta conforme o score piora.
O aumento da dívida média acompanha diretamente a piora do score de crédito, indicando forte associação entre endividamento e risco.
Embora clientes com melhor score apresentem maior renda média, a diferença observada na dívida é proporcionalmente maior, sugerindo que a gestão do endividamento pode ser mais relevante do que a renda isoladamente.
Mais da metade da carteira encontra-se classificada como Standard, indicando potencial para estratégias de evolução desses clientes para categorias de menor risco.

💡 Recomendações de negócio

Com base nos resultados obtidos, eu sugeriria:

desenvolver políticas de crédito mais conservadoras para clientes com elevado nível de endividamento;
criar programas de educação financeira voltados para clientes classificados como Poor;
incorporar histórico de crédito e quantidade de empréstimos como critérios relevantes na análise de concessão de crédito;
desenvolver estratégias específicas para clientes classificados como Standard, reduzindo o risco de migração para categorias de maior risco.

📊 Resultados

Ao final do projeto consegui construir um pipeline completo de análise de dados, passando pelas etapas de:

✅ Leitura dos dados
✅ Limpeza e preparação
✅ Análise exploratória
✅ Desenvolvimento do dashboard
✅ Geração de insights e recomendações de negócio

Além do aprendizado técnico, este projeto me permitiu praticar storytelling com dados e transformar informações em recomendações acionáveis para o negócio.

👩🏾‍💻 Sobre mim

Sou uma profissional em transição e desenvolvimento na área de dados, atualmente atuando como Analista de Dados e aprofundando meus conhecimentos em Analytics, AWS e visualização de dados.

Este projeto representa uma etapa importante da minha jornada de aprendizado e consolidação das habilidades desenvolvidas ao longo do bootcamp.

📎 Arquivos do projeto
Notebook com o pipeline completo de tratamento e análise dos dados;
Dashboard desenvolvido em Power BI (.pbix);
Dashboard exportado em PDF;
Dataset tratado utilizado na análise.

Desenvolvido por Camila de Jesus Fontes 🚀
