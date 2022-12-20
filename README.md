# edas_notebooks
Armazena notebooks de análises exploratórias de dados públicos


## `funil_conversao.ipybn`

Contém a o código da análise exploratória sobre o funil de conversão de uma escola de cursos online. A base de dados está disponível num arquivo [csv](https://drive.google.com/file/d/1xkUKgrAjKPTInL5YjdE2_oBbjvbPwnM-/view?usp=sharing) juntamente com a [descrição dos campos](https://drive.google.com/file/d/1pNZinucDYEaaLiwZlYeMoptzBT_zL05g/view?usp=sharing). Confira o [vídeo](https://youtu.be/WStBvt7Z_Iw) e a [apresentação de slides](https://docs.google.com/presentation/d/1CvSb98eH0xlF6Ak3iF9o3aLgDn8UiSWC72yJGMUDHeU/edit?usp=sharing) dessa análise.

**Como foi o processo criativo:** Iniciei a análise focando na observação na distribuição dos dados e na matriz de correlação das variáveis. Percebi que a matriz apresentou variáveis com correlações muito baixa. Depois de observar as distribuições comecei a levantar insights (compartilhados na apresentação) e pensar em como apresentar as visualizações e contar uma história utilizando técnicas aprendidas sobre storytelling. Por último, baseado nos dados, pensei em algumas sugestões para dar ao time de marketing.

**Quais ferramentas foram utilizadas para analisar os dados**
- A base de dados disponibilizada por um arquivo csv foi salva no google bigquery para realizar consultas por meio de SQL
- Foi utilizado o google colab como notebook de exploração dos dados devido a facilidade de compartilhamento e conexão com o bigquery
- Foram utilizados a linguagem python com as bibliotecas pandas, seaborn e plotly para o desenvolvimento da análise exploratória
