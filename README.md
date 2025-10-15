# Qlik Sense - Hotel Resort de Luxo

#### 📊 Análise Financeiro 
<img width='950' height='500' src="https://github.com/eduardolima17/Qlik-Sense---Analise-Financeiro---Risort-de-Luxo/blob/main/Painel.png"/>

## 📘 Descrição do Projeto
Este projeto tem como objetivo analisar as **receitas e despesas** de um *Hotel Resort de Luxo*, em São Miguel do Gostoso (RN), utilizando o **Qlik Sense** como ferramenta de Business Intelligence.

O gerente do hotel observou aumento nos custos operacionais e solicitou um **painel financeiro** que permitisse monitorar a lucratividade e identificar oportunidades de melhoria.

---

## 🎯 Objetivos da Análise
- Comparar o **crescimento de receitas vs despesas** ao longo dos anos.  
- Identificar **quais áreas têm maior peso no custo total** (ex.: salários, marketing, manutenção).  
- Analisar **quais receitas são mais lucrativas** (quartos, restaurantes, eventos etc.).  

---

## ⚙️ Etapas Realizadas
1. **Carregamento da base de dados** (`hotel_resort_luxo.xlsx`, aba *Cash Flow*).  
2. **Criação das medidas principais:**
   - `Receita Total`
   - `Despesa Total`
   - `Lucro Líquido = Receita Total - Despesa Total`
   - `Margem de Lucro = (Lucro Líquido / Receita Total) * 100`
3. **Construção de visualizações:**
   - Gráfico de linhas: evolução de receitas e despesas por ano.  
   - Gráfico de barras: distribuição de custos por área.  
   - Gráfico de rosca: participação das receitas por temporada.  
   - KPIs: Receita, Despesa, Lucro e Margem de Lucro.

---

## 📊 Resultados e Insights
- As despesas cresceram mais rápido que as receitas em determinados períodos.  
- O custo de **salários, públicidade, diversas e manutenção** representou a maior parte das despesas.
- **Quarto de Luxo, Restaurante, Quarto com Suíte e Hospedagem de eventos** são as principais fontes de receita do hotel.  
- O painel permitiu visualizar a **margem de lucro por temporada** e detectar períodos críticos.

---

## 🧠 Tecnologias Utilizadas
- Qlik Sense (ETL, modelagem e dashboards)
- Excel (dados brutos)
- Análise financeira e KPIs personalizados
