Projeto de Análise de Crédito com SQL, AWS Athena e Python

Este projeto foi desenvolvido com foco em análise de crédito para cartões usando consultas SQL no AWS Athena, armazenando os dados no S3 e processando-os com Python. O objetivo foi explorar insights sobre perfis de clientes, limites de crédito, faixa salarial, e o comportamento de transações para entender melhor o perfil e os hábitos financeiros de diferentes grupos.

⚙️ Ferramentas e Tecnologias Utilizadas
SQL: Consultas executadas no AWS Athena para exploração e extração de dados.
AWS S3: Armazenamento seguro dos arquivos CSV, tanto dos dados de entrada quanto dos resultados.
AWS Athena: Ambiente utilizado para execução das consultas SQL, proporcionando um fluxo de trabalho rápido e escalável.
Python (Pandas, Matplotlib, Seaborn): Ferramentas de análise e visualização de dados para gerar gráficos e insights adicionais.
🗂️ Estrutura do Projeto
markdown
Copiar código
├── sqlEBAC
│   ├── projeto
│   │   ├── credit.csv                   # Base de dados principal
│   │   ├── querys                       # Pasta contendo as consultas SQL
│   │   │   ├── query1.sql
│   │   │   ├── query2.sql
│   │   │   └── ...
│   └── README.md                        # Arquivo de documentação do projeto
📊 Principais Insights
Abaixo estão alguns dos insights mais relevantes que obtivemos durante o projeto:

Perfil de Transações por Faixa Salarial e Gênero: Homens com salários inferiores a $40K realizaram transações de maior valor em média, o que sugere um perfil de consumo mais elevado nessa faixa.
Limite de Crédito e Nível Salarial: Existe uma relação direta entre faixa salarial e limite de crédito. Clientes com rendas mais altas têm limites mais elevados, especialmente aqueles com salários acima de $120K.
Quantidade de Produtos Adquiridos: Observou-se uma média de 4,35 produtos adquiridos por cliente, variando de forma leve entre diferentes faixas de clientes.
📈 Visualizações e Resultados
Os gráficos foram gerados em Python e refletem os insights principais:

Distribuição de Limites de Crédito: Gráfico de barras mostrando o limite médio de crédito por faixa salarial e gênero.
Valor Médio das Transações: Comparação visual do valor médio das transações entre diferentes faixas de renda.
Quantidade de Produtos Comprados: Histograma mostrando a quantidade média de produtos comprados por clientes com base em gênero e faixa salarial.
🚀 Desafios e Aprendizados
Este projeto me permitiu aprofundar o domínio sobre a integração de dados no ambiente AWS e explorar a versatilidade do Athena para consultas SQL avançadas. A união entre SQL para extração de insights e Python para visualização e análise de dados foi essencial para o desenvolvimento dos resultados.

📝 Como Reproduzir este Projeto
Clone o repositório:

bash
Copiar código
git clone https://github.com/seu-usuario/projeto-analise-credito
cd projeto-analise-credito
Instale as dependências necessárias:

É recomendável criar um ambiente virtual para gerenciar as dependências:
bash
Copiar código
conda create -n seu-ambiente python=3.10
conda activate seu-ambiente
pip install -r requirements.txt
Configuração de Ambiente AWS:

Certifique-se de ter suas credenciais AWS configuradas localmente para acessar o S3 e o Athena.
Execução das Consultas SQL no AWS Athena:

Acesse o AWS Athena, configure o bucket S3 de resultados (ebac-leone-query-results) e execute as consultas SQL armazenadas na pasta querys.
Análise dos Resultados com Python:

Os arquivos de consulta gerados podem ser lidos em Python com Pandas para análise e visualização.
👋 Sobre Mim
Sou um desenvolvedor Python e estudante de Data Science, com um foco crescente na utilização de tecnologias de cloud e análise de dados para transformar informação em ação. Se você gostou do projeto ou tem alguma sugestão, estou disponível para trocar ideias!

