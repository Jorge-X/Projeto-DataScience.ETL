# Projeto-DataScience.ETL
### Analise de arquivo CSV: Os clientes estão cancelando os cartões, descobri possíveis causas desses cancelamentos  e fiz um relatório. 

## Atividades empenhadas no projeto:

### Análise de Dados (Data Analysis):
Exploração dos dados do arquivo CSV para entender sua estrutura, variáveis e conteúdo.
Identificação de padrões, tendências e insights nos dados relacionados a cancelamentos de cartões de crédito.
Pré-processamento de Dados (Data Preprocessing):

### Python Programming:
Uso da linguagem Python para todas as etapas, desde a leitura do CSV até a geração de gráficos e análises.

### ETL (Extract, Transform, Load):
Extração dos dados do arquivo CSV.
Transformação dos dados para prepará-los para análise e visualização.
Carregamento dos dados processados para o ambiente de análise.

### Aprendizado de Máquina (Machine Learning):
Aplicação de técnicas de aprendizado de máquina para identificar padrões ou prever cancelamentos de cartões de crédito.
Treinamento de modelos preditivos usando algoritmos como Regressão, Classificação, etc.

### Limpeza dos dados, incluindo tratamento de valores ausentes, duplicados ou inconsistentes.
Normalização ou padronização de dados para garantir uniformidade.
Conversão de tipos de dados, se necessário.

### Visualização de Dados (Data Visualization):
Geração de gráficos (como gráficos de barras) para representar os dados de forma visual e compreensível.
Utilização de ferramentas como plotly.

### Compreensão do Domínio:
Entendimento do domínio de cartões de crédito e dos fatores que podem levar ao cancelamento.

### Comunicação e Relatório:
Compartilhamento dos insights obtidos por meio de apresentações, relatórios ou outros meios de comunicação.

# Conclusão:
## Entre as principais causas estão:

### Contatos frequentes:
#### As clientes que têm mais de 2 contatos com a empresa têm alto risco de cancelar os cartões. Nesse caso, no segundo contato, 403 clientes cancelaram, e no terceiro, 681 clientes cancelaram.
A possível solução nesse caso seria proporcionar um melhor atendimento a esses clientes, evitando possíveis cancelamentos.

### Inatividade:
#### Os clientes a partir de 1 ano de inatividade têm fortes chances de cancelar o cartão. 100 clientes inativos por um ano cancelam. Em 2 anos, o número cresce exponencialmente para 505 clientes cancelando.
A possível solução seria apresentar mais propostas ao cliente, incentivando-o a utilizar mais o seu cartão e, consequentemente, fidelizá-lo.

### Produtos contratados:
#### Quanto mais produtos os clientes contratam, menores são as chances de cancelamento. A partir de 3 produtos cadastrados, os clientes têm menores chances de cancelar seus cartões.
Uma possível solução seria incentivar os clientes a contratarem produtos por meio de estratégias de marketing e um bom atendimento, fidelizando-os.
