# 📊 Análise de Dados - Combustíveis 2024 🇧🇷  

Projeto da disciplina de **Data Warehouse**, com foco em análise de dados utilizando Python e ferramentas de apoio para modelagem e exploração de dados de combustíveis no Brasil em 2024.

## 🧰 Ferramentas Utilizadas

- **Python**: linguagem principal para o tratamento de dados, análise e visualização.  
- **Google Colab**: ambiente usado para desenvolvimento e testes em nuvem.  
- **VSCode**: editor de código para organização e desenvolvimento local.  
- **XAMPP**: ambiente de servidor local para rodar o banco de dados MySQL.  
- **phpMyAdmin**: interface gráfica para gerenciamento do banco de dados no *localhost*.  
- **Miro**: ferramenta usada para a construção do modelo dimensional (modelo estrela).  

## 🗃️ Estrutura do Projeto

- `análises pyhton (combustíveis 2024 Br).ipynb`: notebook com o processo de tratamento, análise e geração de gráficos.  
- `modelo_dimensional.png` *(se aplicável)*: imagem do modelo dimensional elaborado no Miro.  
- Banco de dados criado e gerenciado no phpMyAdmin, com tabelas populadas via scripts SQL.

## ⚙️ Etapas do Projeto

1. **Modelagem Dimensional**: criação do modelo estrela no Miro, com fatos e dimensões definidas.  
2. **Tratamento de Dados**: uso de Python para limpeza, transformação e normalização.  
3. **Carregamento**: dados inseridos no MySQL via XAMPP/phpMyAdmin.  
4. **Consulta e Análise**: integração entre Python e MySQL com `mysql.connector` para consultas em SQL.  
5. **Visualizações**: criação de gráficos com bibliotecas como `matplotlib`, `seaborn` ou `plotly`.

## 💻 Como Executar

1. Instale o XAMPP e inicie o Apache + MySQL.
2. Acesse o phpMyAdmin em `http://localhost/phpmyadmin` e importe o banco
3. Para importar o banco você primeiro extraia o arquivo rar (dados_combustiveis.rar)
4. Execute o notebook localmente no VSCode.
5. Verifique se a conexão com o banco está correta (usuário, senha e porta do MySQL), lembrando que não haverá senha ficara em aspas vazio mesmo

## 📌 Observações

- Este projeto foi desenvolvido como parte da avaliação da disciplina de **Data Warehouse**.
- O objetivo principal é aplicar o conhecimento de modelagem dimensional e análise de dados ETL com Python.
- O dataset utilizado refere-se a dados reais de preço de combustíveis no Brasil em 2024 da ANP do site https://dados.gov.br/home
