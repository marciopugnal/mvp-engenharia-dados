### 📊 MVP - Engenharia de dados

🧩 **Engenharia de Dados para Jogos de Tabuleiro**  

Este projeto tem como objetivo aplicar os conceitos de engenharia de dados para analisar e estruturar um conjunto de informações relacionadas a jogos de tabuleiro. A abordagem será conduzida por meio de etapas fundamentais, incluindo modelagem de dados, limpeza e transformação, organização e integração e, por fim, análise e elaboração de relatórios.  
O desafio central consiste em transformar dados dispersos em conhecimento estruturado, capaz de revelar tendências, fatores de popularidade, padrões de comportamento e relações entre jogos e jogadores dentro da comunidade.   

🌐 **Análise de dados no Databricks**   
A escolha pela plataforma Databricks se deve à sua característica de ser um Lakehouse, ou seja, combinar os conceitos de Data Warehouse e Data Lake em uma solução unificada de análise de dados e inteligência artificial baseada em nuvem. Essa arquitetura facilita o trabalho com big data e machine learning, oferecendo escalabilidade, flexibilidade e integração com ferramentas como Python, SQL e PySpark, essenciais para o processamento e análise de grandes volumes de dados. Além disso, o projeto será desenvolvido utilizando a versão Free Edition, que permite acesso às funcionalidades básicas da plataforma sem custo.  
O Databricks funciona como um ambiente colaborativo, integrando armazenamento, processamento e análise de dados em larga escala. Essa abordagem possibilita tanto a exploração avançada quanto a produção de relatórios estratégicos, apoiando decisões relacionadas ao universo dos jogos de tabuleiro e ampliando a capacidade de gerar insights relevantes para diferentes públicos e aplicações.  

🎲 **Dataset**  
O conjunto de dados foi obtido na plataforma Kaggle [fonte: https://www.kaggle.com/datasets/andrewmvd/board-games] e reúne informações extraídas do site BoardGameGeek (BGG), uma das maiores comunidades online dedicadas a jogos de tabuleiro.

🔄 **Metodologia**  
A abordagem será estruturada em etapas sequenciais, organizadas em um pipeline de dados:  
- Ingestão de dados: coleta de informações através de dataset armazenado no github.  
- Modelagem: aplicação do modelo estrela com tabelas de fatos e dimensões
.  
- Transformação: limpeza, padronização e enriquecimento dos dados para garantir consistência e qualidade.  
- Armazenamento: consolidação em um data lake estruturado (Databricks), pronto para consultas e análises.  
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
Este projeto evidencia a aplicação da engenharia de dados em ambientes de análise para transformar informações dispersas em conhecimento estruturado.  
A utilização de Databricks, Python, SQL e PySpark possibilitaram a realização de análises aprofundadas sobre o universo dos jogos de tabuleiro, permitindo identificar padrões e tendências relevantes.  
Os resultados demonstram que popularidade não garante qualidade: jogos mais jogados não são necessariamente os mais bem avaliados. Além disso, verificou-se que complexidade e duração estão diretamente associadas a notas mais altas, enquanto jogos curtos (≤30 minutos), embora abundantes, tendem a ser menos valorizados.  
Observa-se também a existência de lacunas para determinados públicos, como adultos e grupos grandes, que dispõem de menor oferta de títulos e apresentam níveis mais baixos de satisfação. Já as categorias e mecânicas revelam fidelidade de nichos específicos, mas não asseguram avaliações elevadas de forma consistente.  
Em síntese, os achados reforçam que fatores como complexidade, duração e público-alvo exercem influência significativa na percepção de qualidade dos jogos de tabuleiro, oferecendo subsídios para decisões estratégicas de editoras, desenvolvedores e comunidades.  


