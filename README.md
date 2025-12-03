### 📊 MVP - Engenharia de dados.

🧩 **Engenharia de Dados para Jogos de Tabuleiro**  
Este projeto tem como objetivo aplicar os conceitos de engenharia de dados para analisar e estruturar um conjunto de informações relacionadas a jogos de tabuleiro. O desafio consiste em extrair insights significativos desse conjunto de dados, de modo a identificar tendências, fatores de popularidade, padrões de comportamento e relações entre jogos e jogadores dentro da comunidade.  

A escolha pela plataforma Databricks se deve à sua característica de ser um Lakehouse, ou seja, combinar os conceitos de Data Warehouse e Data Lake em uma plataforma unificada de análise de dados e inteligência artificial baseada em nuvem. Essa arquitetura facilita o trabalho com big data e machine learning, oferecendo escalabilidade, flexibilidade e integração com ferramentas como Python, SQL e PySpark, essenciais para o processamento e análise de grandes volumes de dados.  
O Databricks funciona como um ambiente colaborativo, integrando armazenamento, processamento e análise de dados em larga escala, o que possibilita tanto a exploração avançada quanto a geração de relatórios estratégicos para apoiar decisões relacionadas ao universo dos jogos de tabuleiro.  

🎲 **Dataset**  
O conjunto de dados foi obtido na plataforma Kaggle [fonte: https://www.kaggle.com/datasets/andrewmvd/board-games] e reúne informações extraídas do site BoardGameGeek (BGG), uma das maiores comunidades online dedicadas a jogos de tabuleiro.

🔄 **Metodologia**  
A abordagem será estruturada em etapas sequenciais, organizadas em um pipeline de dados:  
- Ingestão de dados: coleta de informações de diferentes fontes (avaliadores, bases públicas, APIs).  
- Modelagem: aplicação do modelo estrela, com tabelas de fatos (interações, avaliações, métricas de popularidade) e dimensões (jogos, jogadores, categorias).  
- Transformação: limpeza, padronização e enriquecimento dos dados para garantir consistência e qualidade.  
- Armazenamento: consolidação em um data lake estruturado, pronto para consultas e análises.  
- Análise exploratória: utilização de SQL, Python e PySpark para identificar padrões, tendências e fatores que influenciam o sucesso dos jogos.  

🛠️ **Ferramentas Utilizadas**  
- Linguagem: Python, SQL  
- Bibliotecas: Pandas, NumPy, PySpark  
- Ambientes: Databricks e GitHub  
- Documentação: Markdown e Catálogo Databricks  

📋 **Resultados Esperados**  
- Obter uma base de dados confiável e estruturada sobre jogos de tabuleiro.  
- Facilitar a consulta e análise de informações por meio de queries SQL e processamento distribuído em PySpark.  
- Identificar padrões de comportamento dos jogadores e tendências emergentes no mercado.  
- Fornecer insights estratégicos para editoras, desenvolvedores e comunidades, apoiando decisões sobre design, marketing e lançamento de novos jogos.  
- Realizar a segmentação de jogos com base em características e níveis de popularidade.  
- Analisar correlações entre mecânicas de jogo e indicadores de popularidade.  
- Explorar tendências no comportamento dos jogadores e na evolução da popularidade dos jogos.  
- Mapear perfis de jogadores considerando preferências, estilos de jogo e avaliações.

🌟 **Conclusão**  
Este projeto demonstra como a engenharia de dados aplicada em ambientes de big data pode transformar informações dispersas em conhecimento estruturado.  
A utilização de Databricks, Python, SQL e PySpark garante robustez e escalabilidade, permitindo análises aprofundadas sobre o universo dos jogos de tabuleiro.  
Ao final, espera-se que os resultados obtidos contribuam para uma compreensão mais ampla da dinâmica desse segmento, revelando fatores de popularidade, padrões de interação e oportunidades de inovação.  


