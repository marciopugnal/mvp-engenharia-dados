## 📊**MVP – Engenharia de Dados para Jogos de Tabuleiro**  
Este projeto aplica conceitos de engenharia de dados para transformar e explorar um dataset de avaliações de jogos de tabuleiro em informações estruturadas. O trabalho envolve etapas de ingestão, limpeza, transformação, modelagem, armazenamento e análise dos dados. O objetivo é descobrir relações e comportamentos ocultos, gerando insights que revelem tendências, fatores de popularidade, padrões de comportamento e conexões entre jogos e jogadores na comunidade.  

### 🎲 **Dataset**  
O conjunto de dados foi obtido na plataforma Kaggle [fonte: https://www.kaggle.com/datasets/andrewmvd/board-games] e reúne informações extraídas do site BoardGameGeek (BGG), uma das maiores comunidades online dedicadas a jogos de tabuleiro, contendo informações detalhadas sobre jogos, avaliações, mecânicas, categorias e perfis de jogadores.  

### ☁️ **Plataforma**  
O projeto utiliza o Databricks (Free Edition) como plataforma Lakehouse, integrando camadas de Data Lake e Data Warehouse em uma arquitetura unificada. Esse ambiente permite orquestrar pipelines de ingestão, processamento distribuído e consultas analíticas utilizando Python, SQL e PySpark, garantindo escalabilidade, paralelismo e governança dos dados.  

### ❓ **Questões analíticas a serem respondidas**  
Com o intuito de atingir os objetivos definidos, este trabalho se dedicará a responder questões como:  
▶ Top 10 jogos mais bem avaliados e sua relação com popularidade;  
▶ Influência da complexidade nas avaliações;  
▶ Mecânicas e categorias mais associadas a alta popularidade;  
▶ Correlação entre complexidade, tempo de jogo e satisfação; e  
▶ Perfil dos jogos por número de jogadores e faixa etária recomendada.  

📌 **Nota:** _As respostas estão consolidadas, evidenciadas e registradas nos arquivos abaixo, ambos armazenados no GitHub:_  
▶ **Relatorio-Final**  
--->  xxxxxx
▶ **Query-Tabuleiro-Questoes-Solucoes**  
---> https://github.com/marciopugnal/mvp-engenharia-dados/blob/main/Query-Tabuleiro-Questoes-Solucoes.ipynb  

▶ **Painel‑Jogos‑Tabuleiro**  
---> https://github.com/marciopugnal/mvp-engenharia-dados/blob/main/Painel-Jogos-Tabuleiro-v.2025-12-07.pdf  

▶ **Notebook‑MVP‑Eng‑Dados‑Tabuleiro**  
--->  https://github.com/marciopugnal/mvp-engenharia-dados/blob/main/Query-Tabuleiro.ipynb  

### 🧩 **Metodologia**  
A abordagem será organizada em etapas sequenciais, estruturadas em um pipeline de dados:  
▶ Ingestão de dados: coleta de informações a partir de um dataset armazenado no GitHub;  
▶ Transformação: limpeza, padronização e enriquecimento dos dados, assegurando consistência e qualidade;  
▶ Modelagem: aplicação do modelo estrela, com a definição de tabelas de fatos e dimensões;  
▶ Armazenamento: consolidação em um data lake estruturado no Databricks, preparado para consultas e análises; e  
▶ Análise exploratória: utilização de SQL, Python e PySpark para consulta de banco de dados e geração de relatórios e gráficos para identificar padrões, tendências e fatores que influenciam o desempenho e a popularidade dos jogos.  

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
O desenvolvimento deste trabalho possibilitou aplicar, na prática, alguns dos conhecimentos teóricos das disciplinas, consolidando o entendimento dos conceitos de engenharia de dados dentro do contexto da ciência de dados. A experiência com bancos de dados e SQL foi essencial para modelar estruturas, executar consultas e gerar insights por meio de filtragens, agregações e cálculos analíticos.  
No início, surgiram desafios relacionados ao uso do Databricks, à curva de aprendizado do PySpark e à necessidade de consultar documentações, ferramentas de IA, tutoriais e vídeos. Também houve dificuldades na integração com o GitHub e na compreensão dos recursos do Spark SQL, exigindo experimentação e estudo contínuo.  
Para trabalhos futuros, recomenda-se o aprofundamento das análises, a incorporação de novos conjuntos de dados, a possibilidade de organização em camadas e a implementação de técnicas de machine learning, de modo a viabilizar investigações mais automatizadas, robustas, e metodologicamente avançadas.
