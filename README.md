# 🚀 Desafio DIO — Automação com AWS Lambda, S3 e DynamoDB (LocalStack)

Este projeto foi desenvolvido como parte do **desafio prático da Digital Innovation One (DIO)**, com o objetivo de aplicar conceitos de **automação de infraestrutura e funções serverless** utilizando **AWS Lambda, S3 e DynamoDB**, simulados localmente via **LocalStack**.

---

## 🧩 Objetivos de Aprendizagem

- Aplicar na prática os conceitos aprendidos sobre automação e funções Lambda.  
- Criar e gerenciar recursos AWS simulados (S3, Lambda, DynamoDB).  
- Documentar de forma clara os processos técnicos.  
- Utilizar o GitHub como ferramenta de portfólio técnico.

---

## ⚙️ Tecnologias Utilizadas

- 🐍 **Python 3.9**  
- ☁️ **AWS LocalStack** (simulador local da AWS)  
- 🧱 **AWS CLI / awslocal**  
- 💾 **DynamoDB**, **S3**, **Lambda**

---

## 🧠 Descrição do Projeto

A automação consiste em:

1. Criar um **bucket S3** para upload de arquivos JSON com dados de notas fiscais.  
2. Criar uma **função Lambda** que é automaticamente disparada quando um novo arquivo é enviado ao bucket.  
3. A Lambda processa o conteúdo do arquivo e **salva os dados na tabela DynamoDB**.  
4. O ambiente é completamente simulado com **LocalStack**, sem custos AWS.

---

📊 Resultados Esperados

Após o upload do arquivo notas_fiscais_2025.json, a função Lambda deve ser acionada automaticamente, processar o conteúdo e gravar as informações na tabela NotasFiscais no DynamoDB.


🖼️ Evidências

(Imagens de execução e logs podem ser incluídas na pasta /images.)
