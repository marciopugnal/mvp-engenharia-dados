## 📊**MVP – Engenharia de Dados para Jogos de Tabuleiro**  
Este projeto aplica conceitos de engenharia de dados para transformar e explorar um dataset de avaliações de jogos de tabuleiro em informações estruturadas. O trabalho envolve etapas de ingestão, limpeza, transformação, modelagem, armazenamento e análise dos dados. O objetivo é extrair insights relevantes que revelem tendências, fatores de popularidade, padrões de comportamento e relações entre jogos e jogadores na comunidade.  

### 📁 **Dataset**  
O conjunto de dados foi obtido na plataforma Kaggle [fonte: https://www.kaggle.com/datasets/andrewmvd/board-games] e reúne informações extraídas do site BoardGameGeek (BGG), uma das maiores comunidades online dedicadas a jogos de tabuleiro, contendo informações detalhadas sobre jogos, avaliações, mecânicas, categorias e perfis de jogadores.  

### ☁️ **Plataforma**  
O projeto utiliza o Databricks (Free Edition) como plataforma Lakehouse, integrando camadas de Data Lake e Data Warehouse em uma arquitetura unificada. Esse ambiente permite orquestrar pipelines de ingestão, processamento distribuído e consultas analíticas utilizando Python, SQL e PySpark, garantindo escalabilidade, paralelismo e governança dos dados.  

### ❓ **Questões analíticas a serem respondidas**  
O estudo busca responder questões, tais como:  
▶ Top 10 jogos mais bem avaliados e sua relação com popularidade;  
▶ Influência da complexidade nas avaliações;  
▶ Mecânicas e categorias mais associadas a alta popularidade;  
▶ Correlação entre complexidade, tempo de jogo e satisfação; e  
▶ Perfil dos jogos por número de jogadores e faixa etária recomendada.  

📌 **Nota:** _As respostas estão consolidadas, evidenciadas e registradas nos arquivos abaixo, ambos armazenados no GitHub:_  
▶ **Relatorio-Final** -->  
▶ **Query-Tabuleiro** -->   
▶ **Painel‑Jogos‑Tabuleiro** -->   
▶ **Notebook‑MVP‑Eng‑Dados‑Tabuleiro** -->  https://github.com/marciopugnal/mvp-engenharia-dados/blob/main/Query-Tabuleiro.ipynb  

### 🧩 **Metodologia**  
Pipeline de engenharia de dados composto por:  
▶ Ingestão de dados via GitHub  
▶ Transformação (limpeza, padronização e enriquecimento)  
▶ Modelagem em esquema estrela  
▶ Armazenamento em data lake no Databricks  
▶ Análise exploratória com SQL, Python e PySpark  

### 🛠️ **Ferramentas**  
▶ Linguagens: Python, SQL  
▶ Bibliotecas: Pandas, NumPy, PySpark  
▶ Ambientes: Databricks, GitHub, brModelo  
▶ Documentação: Markdown e Catálogo Databricks  

### 📝 **Resultados Esperados**  
▶ Identificação de padrões entre jogos e jogadores;  
▶ Segmentação por características e popularidade;  
▶ Correlações entre mecânicas, categorias e avaliações;  
▶ Tendências de comportamento da comunidade;  
▶ Perfis de jogadores baseados em preferências e avaliações;  
  
### ✅ **Autoavaliação**  
O projeto consolidou conhecimentos de engenharia de dados e SQL, permitindo análises complexas e manipulação eficiente dos dados.  
O uso do Databricks e Spark representou um desafio inicial, superado com estudo e prática, ampliando a compreensão sobre ambientes distribuídos e processamento em larga escala.
