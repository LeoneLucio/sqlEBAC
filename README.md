

---

# Projeto de Análise de Crédito com SQL, AWS Athena e Python

Este projeto foca na análise de crédito para cartões, usando **SQL no AWS Athena** para explorar dados armazenados no **S3** e **Python** para visualizações e insights adicionais.

## ⚙️ Ferramentas Utilizadas

- **SQL no AWS Athena**: Para consultas rápidas e escaláveis.
- **AWS S3**: Armazenamento dos dados CSV e resultados.
- **Python (Pandas, Matplotlib, Seaborn)**: Análise e visualização de dados.

## 🗂️ Estrutura do Projeto

```
├── projeto
│   ├── credit.csv             # Dados principais
│   ├── querys                 # Consultas SQL
│   └── README.md              # Documentação
```

## 📊 Principais Insights

- **Perfil de Transações**: Homens com salários menores que $40K têm um valor médio de transação mais alto.
- **Limite de Crédito vs. Salário**: Quanto maior a renda, maior o limite de crédito.
- **Produtos Adquiridos**: Clientes compram, em média, 4,35 produtos.

## 📝 Como Reproduzir

1. **Clone o repositório**:
   ```bash
   git clone https://github.com/seu-usuario/projeto-analise-credito
   cd projeto-analise-credito
   ```

2. **Configure o ambiente Python**:
   ```bash
   conda create -n seu-ambiente python=3.10
   conda activate seu-ambiente
   pip install -r requirements.txt
   ```

3. **Execute as consultas no AWS Athena** e faça a análise dos resultados com Python.

## 👋 Sobre Mim

Leone Lúcio, desenvolvedor Python e estudante de Data Science. Focado em projetos de análise de dados e cloud computing. Feedbacks são sempre bem-vindos!

--- 
