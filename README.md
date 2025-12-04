### 📊 MVP - Engenharia de dados  

🧩 **Engenharia de Dados para análise de Jogos de Tabuleiro**  
**Objetivo:**  
Este projeto tem como objetivo explorar, analisar e aplicar princípios de engenharia de dados em um dataset contendo informações sobre avaliações de jogos de tabuleiro. A execução seguirá etapas essenciais, tais como: ingestão de dados, limpeza e transformação dos dados, modelagem, armazenamento e organização, disponibilização e, por fim, análise e elaboração de relatórios.  
O desafio central é converter dados dispersos em conhecimento estruturado e extrair resultados e insights significativos, capazes de revelar tendências, fatores de popularidade, padrões de comportamento e relações entre jogos e jogadores na comunidade.  

**Coleta**  
🎲 **Dataset**  
O conjunto de dados foi obtido na plataforma Kaggle [fonte: https://www.kaggle.com/datasets/andrewmvd/board-games] e reúne informações extraídas do site BoardGameGeek (BGG), uma das maiores comunidades online dedicadas a jogos de tabuleiro.

**Modelagem**  
Modelagem estrela com tabelas com fato e dimensões.  
<img width="660" height="441" alt="Conceitual_Tabuleiro_Estrela3" src="https://github.com/user-attachments/assets/f9dbe4b9-3514-4006-86fb-8cc2045a9bb5" /><img width="756" height="488" alt="Lógico_Tabuleiro_Estrela3" src="https://github.com/user-attachments/assets/aefe95b7-dcf1-4644-a00f-48c2cc09260f" />

**Carga**  

**Catálogo de Dados**  

**Análise**   

🌐 **Análise de dados no Databricks**   
A escolha pela plataforma Databricks se deve à sua característica de ser Lakehouse, ou seja, a combinação dos conceitos de Data Warehouse e Data Lake em uma solução unificada de análise de dados e inteligência artificial baseada em nuvem. Essa arquitetura facilita o trabalho com big data e machine learning, oferecendo escalabilidade, flexibilidade e integração com ferramentas como Python, SQL e PySpark, essenciais para o processamento e análise de grandes volumes de dados. Trata-se de um ambiente colaborativo que integra armazenamento, processamento e análise de dados em larga escala. Além disso, o Databricks disponibiliza a versão Free Edition, que permite acesso às funcionalidades básicas sem custo.  

**Resultados**  
01. Quais são os jogos (top 10) de tabuleiro mais bem avaliados e sua relação com a popularidade?
02. Como o nível de complexidade dos jogos influencia a avaliação média dos jogos?
03. Quais as mecânicas de jogos que estão associadas às maiores avaliações e popularidade?
04. Qual a correlação entre a complexidade dos jogos e o tempo médio de uma partida?
05. Como a faixa etária recomendada pelo jogo influencia a avaliação dos jogos?
06. Quais categorias (dominios) temáticas tem maior popularidade e mantêm alta avaliação?
07. Qual a relação entre tempo de jogo e satisfação dos jogadores?
08. Qual é o perfil dos jogos (quantidade, avaliação e tempo) por faixa de jogadores?

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
- Ambientes: Databricks, GitHub e brModelo  
- Documentação: Markdown e Catálogo do Databricks  
 
📋 **Resultados Esperados**  
- Identificação de padrões de comportamento entre jogadores e jogos.  
- Segmentação de jogos por características e popularidade.  
- Análise de correlações entre mecânicas de jogo e níveis de popularidade.  
- Exploração de tendências no comportamento dos jogadores e na popularidade dos jogos.  
- Mapeamento de perfis de jogadores com base em preferências, estilos de jogo e avaliações.  

**Autoavaliação**  
O trabalho permitiu aplicar de forma prática o conhecimento teórico abordados nas aulas, com isso permitiu consolidar o conhecimento de engenharia de dados na área de ciência de dados. O conhecimento em SQL adquirido ao longo do curso, me permitiu realizar consultas, manipulação e análise de dados. Essas habilidades foram úteis para extrair informações relevantes do conjunto de dados, realizar filtragens, agregações e cálculos. No entanto, não possuia conhecimento prévio em Databricks, uma das ferramentas utilizadas nesse trabalho. Tal fato representou um desafio inicial, bem com a utilização do Spark, sendo necessário consultar documentações, tutoriais e vídeos da internet.  

Os desafios inicias foram a familiarização com o ambiente do Databricks e suas interfaces;  
Integração com o GitHub, compreensão do funcionamento de Spark SQL e PySpark;  

🌟 **Conclusão**  
Este projeto evidencia a aplicação da engenharia de dados em ambientes de análise para transformar informações dispersas em conhecimento estruturado.  
Os resultados demonstram que popularidade não garante qualidade, ou seja, jogos mais jogados não são necessariamente os mais bem avaliados. Além disso, verificou-se que complexidade e duração estão diretamente associadas a notas mais altas, enquanto jogos curtos (≤30 minutos), embora abundantes, tendem a ser menos valorizados.  
Observa-se também a existência de lacunas para determinados públicos, como adultos e grupos grandes, que dispõem de menor oferta de títulos e apresentam níveis mais baixos de satisfação. Já as categorias e mecânicas revelam fidelidade de nichos específicos, mas não asseguram avaliações elevadas de forma consistente.  
Em síntese, os achados reforçam que fatores como complexidade, duração e público-alvo exercem influência significativa na percepção de qualidade dos jogos de tabuleiro, oferecendo subsídios para decisões estratégicas de editoras, desenvolvedores e comunidades.  

 
