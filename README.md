## 📊**MVP – Engenharia de Dados para Jogos de Tabuleiro**  
Este projeto aplica conceitos de engenharia de dados para transformar e explorar um dataset de avaliações de jogos de tabuleiro em informações estruturadas. O trabalho envolve etapas de ingestão, limpeza, transformação, modelagem, armazenamento e análise dos dados, através da plataforma Databricks. O objetivo é descobrir relações e comportamentos ocultos, gerando insights e descobertas que revelem tendências, fatores de popularidade, padrões de comportamento e conexões entre jogos e jogadores na comunidade.  

### 🎲 **Dataset**  
O conjunto de dados foi obtido na plataforma Kaggle [fonte: https://www.kaggle.com/datasets/andrewmvd/board-games] e reúne informações extraídas do site BoardGameGeek (BGG), uma das maiores comunidades online dedicadas a jogos de tabuleiro, contendo informações detalhadas sobre jogos, avaliações, mecânicas, categorias e perfis de jogadores.  

### ☁️ **Plataforma**  
O projeto utiliza o Databricks (Free Edition) como plataforma Lakehouse, integrando camadas de Data Lake e Data Warehouse em uma arquitetura unificada. Esse ambiente permite orquestrar pipelines de ingestão, processamento distribuído e consultas analíticas utilizando Python, SQL e PySpark, garantindo escalabilidade, paralelismo e governança dos dados.  

### ❓ **Questões analíticas a serem respondidas**  
Com o intuito de atingir os objetivos definidos, este trabalho se dedicará a responder questões como:  
⏩ Top 10 jogos mais bem avaliados e sua relação com popularidade;  
⏩ Influência da complexidade nas avaliações;  
⏩ Mecânicas e categorias mais associadas a alta popularidade;  
⏩ Correlação entre complexidade, tempo de jogo e satisfação; e  
⏩ Perfil dos jogos por número de jogadores e faixa etária recomendada.  

📌 **Nota:** _As respostas estão consolidadas, evidenciadas e registradas nos arquivos abaixo, ambos armazenados no GitHub:_  
▶ **Notebook‑MVP‑Eng‑Dados‑Tabuleiro:**  
---> https://github.com/marciopugnal/mvp-engenharia-dados/blob/main/Notebook-MVP-Eng-Dados-Tabuleiro.ipynb

▶ **Query-Tabuleiro-Questoes-Solucoes:**  
---> https://github.com/marciopugnal/mvp-engenharia-dados/blob/main/Query-Tabuleiro-Questoes-Solucoes.ipynb

▶ **MVP-Relatorio-Questoes-Final:** Amostra, Modelagem, Tabelas, Catálogo e Questões   
---> https://github.com/marciopugnal/mvp-engenharia-dados/blob/main/MVP-Relatorio-Questoes-Final.pdf

▶ **Painel‑Jogos‑Tabuleiro:**  
---> https://github.com/marciopugnal/mvp-engenharia-dados/blob/main/Painel-Jogos-Tabuleiro.pdf

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
O desenvolvimento deste trabalho possibilitou a aplicação prática de um conjunto significativo de conhecimentos teóricos discutidos ao longo das disciplinas, contribuindo para o aprofundamento da compreensão dos princípios de engenharia de dados no contexto mais amplo da ciência de dados. A manipulação de bancos de dados e o uso de SQL desempenharam papel central na modelagem de estruturas, na formulação de consultas e na obtenção de resultados por meio de filtragens, agregações e operações analíticas, consolidando a articulação entre teoria e prática.  
Durante as etapas iniciais, foram identificados desafios relacionados ao uso do Databricks, à curva de aprendizado associada ao PySpark e à necessidade de consulta frequente a documentações, ferramentas de inteligência artificial, tutoriais e materiais de vídeos. Dificuldades adicionais surgiram na integração com o GitHub e na assimilação dos recursos do Spark SQL, exigindo um processo contínuo de experimentação, investigação e aprimoramento técnico. Apesar desses obstáculos, os objetivos analíticos propostos — especialmente a formulação e a verificação das hipóteses iniciais — foram alcançados, resultando em identificação de insights e descobertas relevantes para a compreensão do conjunto de dados estudado.  
Para trabalhos futuros, recomenda-se o aprofundamento das análises, a incorporação de novos conjuntos de dados com maior volume e, com isso, a adoção de uma arquitetura de dados estruturada em camadas e a implementação de técnicas de machine learning. Tais aprimoramentos podem ampliar o rigor metodológico, favorecer a automação de processos analíticos e possibilitar investigações mais robustas, escaláveis e alinhadas às práticas contemporâneas da engenharia e da ciência de dados.   
