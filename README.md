### 📊 MVP - Engenharia de dados

🧩 **Engenharia de Dados para Jogos de Tabuleiro**

Este projeto tem como objetivo explorar, analisar e aplicar princípios de engenharia de dados em um dataset contendo informações sobre avaliações de jogos de tabuleiro. A execução seguirá etapas essenciais, tais como: ingestão de dados, limpeza e transformação dos dados, modelagem, armazenamento e organização, disponibilização e, por fim, análise e elaboração de relatórios.  
O desafio central é converter dados dispersos em conhecimento estruturado e extrair resultados e insights significativos, capazes de revelar tendências, fatores de popularidade, padrões de comportamento e relações entre jogos e jogadores na comunidade.  

🌐 **Análise de dados no Databricks**   
A escolha pela plataforma Databricks se deve à sua característica de ser Lakehouse, ou seja, a combinação dos conceitos de Data Warehouse e Data Lake em uma solução unificada de análise de dados e inteligência artificial baseada em nuvem. Essa arquitetura facilita o trabalho com big data e machine learning, oferecendo escalabilidade, flexibilidade e integração com ferramentas como Python, SQL e PySpark, essenciais para o processamento e análise de grandes volumes de dados. Trata-se de um ambiente colaborativo que integra armazenamento, processamento e análise de dados em larga escala. Além disso, o Databricks disponibiliza a versão Free Edition, que permite acesso às funcionalidades básicas sem custo.  

🎲 **Dataset**  
O conjunto de dados foi obtido na plataforma Kaggle [fonte: https://www.kaggle.com/datasets/andrewmvd/board-games] e reúne informações extraídas do site BoardGameGeek (BGG), uma das maiores comunidades online dedicadas a jogos de tabuleiro.

🔄 **Metodologia**  
A abordagem será organizada em etapas sequenciais, estruturadas em um pipeline de dados:  
- Ingestão de dados: coleta de informações a partir de um dataset armazenado no GitHub.  
- Transformação: limpeza, padronização e enriquecimento dos dados, assegurando consistência e qualidade.  
- Modelagem: aplicação do modelo estrela, com a definição de tabelas de fatos e dimensões.  
- Armazenamento: consolidação em um data lake estruturado no Databricks, preparado para consultas e análises.  
- Análise exploratória: utilização de SQL, Python e PySpark para identificar padrões, tendências e fatores que influenciam o desempenho e a popularidade dos jogos.  

🛠️ **Ferramentas Utilizadas**  
- Linguagens: Python e SQL  
- Bibliotecas: Pandas, NumPy e PySpark  
- Ambientes: Databricks e GitHub  
- Documentação: Markdown e Catálogo do Databricks  

📋 **Resultados Esperados**  
- Identificar padrões de comportamento e relações entre jogos e jogadores na comunidade.  
- Extrair resultados e insights significativos, através de caracteristicas ocultas.  
- Realizar a segmentação de jogos com base em características e níveis de popularidade.  
- Analisar correlações entre mecânicas de jogo e indicadores de popularidade.  
- Explorar tendências no comportamento dos jogadores e na evolução da popularidade dos jogos.  
- Mapear perfis de jogadores considerando preferências, estilos de jogo e avaliações.

🌟 **Conclusão**  
Este projeto evidencia a aplicação da engenharia de dados em ambientes de análise para transformar informações dispersas em conhecimento estruturado.  
Os resultados demonstram que popularidade não garante qualidade, ou seja, jogos mais jogados não são necessariamente os mais bem avaliados. Além disso, verificou-se que complexidade e duração estão diretamente associadas a notas mais altas, enquanto jogos curtos (≤30 minutos), embora abundantes, tendem a ser menos valorizados.  
Observa-se também a existência de lacunas para determinados públicos, como adultos e grupos grandes, que dispõem de menor oferta de títulos e apresentam níveis mais baixos de satisfação. Já as categorias e mecânicas revelam fidelidade de nichos específicos, mas não asseguram avaliações elevadas de forma consistente.  
Em síntese, os achados reforçam que fatores como complexidade, duração e público-alvo exercem influência significativa na percepção de qualidade dos jogos de tabuleiro, oferecendo subsídios para decisões estratégicas de editoras, desenvolvedores e comunidades.  
