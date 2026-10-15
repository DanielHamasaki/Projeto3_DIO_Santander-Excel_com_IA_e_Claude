# 🎮 Dashboard de Vendas do Xbox com Excel

Projeto desenvolvido para o desafio **“Criando um Dashboard de Vendas do Xbox com Excel”**, do curso **Santander — Excel com IA e Claude**, na plataforma DIO.

O objetivo é organizar dados de assinaturas do Xbox Game Pass e apoiar a análise de vendas por tipo de plano, renovação automática e compras de complementos, como EA Play Season Pass e Minecraft Season Pass.

## 📂 Estrutura do arquivo

O arquivo `Projeto3_XBOX_DIO_Santander-Excel_com_IA_e_Claude.xlsx` está organizado em quatro planilhas:

- **Assets** — reúne referências visuais do dashboard, incluindo paleta de cores e elementos gráficos.
- **Bases** — contém a base de dados de assinantes, com identificador, nome, plano, data de início, renovação automática, preço da assinatura, periodicidade, complementos, cupons e valor total.
- **Cálculos** — registra as perguntas de negócio e os resultados das análises.
- **Dashboard** — área destinada à apresentação visual dos resultados, com identidade visual relacionada ao Xbox.

## 📊 Perguntas de negócio analisadas

A planilha `Cálculos` apresenta análises para responder às seguintes perguntas:

1. Qual é o faturamento total das vendas de planos anuais, considerando as assinaturas agregadas?
2. Qual é o faturamento dos planos anuais, separado entre assinaturas com e sem renovação automática?
3. Qual é o total de vendas do **EA Play Season Pass**?
4. Qual é o total de vendas do **Minecraft Season Pass**?

Os resultados são organizados por categorias, como tipo de assinatura e renovação automática, para facilitar a leitura dos dados.

## 🧰 Recursos do Excel identificados no arquivo

- Base de dados estruturada em tabela (`Tabela1`)
- Tabelas de resumo para consolidação dos resultados
- Agregação de valores por categoria
- Função `GETPIVOTDATA` para recuperar valores de tabelas dinâmicas
- Organização dos dados em planilhas separadas para base, cálculos, recursos visuais e dashboard
- Identidade visual personalizada com paleta de cores e elementos gráficos

## 🗂️ Campos presentes na base de dados

A planilha `Bases` contém informações como:

- ID e nome do assinante
- Plano contratado (`Core`, `Standard` ou `Ultimate`)
- Data de início da assinatura
- Renovação automática
- Preço da assinatura e periodicidade (`Monthly`, `Quarterly` ou `Annual`)
- Adesão ao EA Play Season Pass e respectivo preço
- Adesão ao Minecraft Season Pass e respectivo preço
- Valor de cupom
- Valor total

## 🎯 Objetivo do projeto

Praticar a organização e análise de dados no Excel, transformando registros de assinaturas em informações úteis para responder a perguntas de negócio relacionadas às vendas.

## 🛠️ Ferramenta

- Microsoft Excel

---

**Observação:** projeto educacional para prática de análise de dados. Os resultados refletem os dados contidos na planilha fornecida.
