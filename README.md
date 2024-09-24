# PAINEL-GERENCIAL-MARKETING-POWERBI

# Painel Gerencial Automatizado - Agência de Marketing Digital

Este repositório contém um projeto de criação de um painel gerencial automatizado utilizando Power BI, desenvolvido para uma agência de marketing digital. O painel permite o acompanhamento de indicadores de desempenho de campanhas e ajuda na tomada de decisões estratégicas para alcançar metas trimestrais.

## Contexto

A agência precisa monitorar e otimizar o desempenho de suas campanhas para atingir uma meta ambiciosa no trimestre. Para isso, criamos um dashboard no Power BI que acompanha métricas chave, como receita, número de usuários ativos, compradores, e visualizações por plataforma.

## Objetivo

- **Monitorar os KPIs das campanhas de marketing digital.**
- **Identificar oportunidades de otimização e melhores planos de ação para atingir as metas.**

## Dataset

Os dados fornecidos incluem o desempenho de campanhas no mês de março de 2023, com as seguintes colunas:
- **Data**: Período analisado.
- **Receita Total**: Valor total de receita gerada.
- **Receita Média por Compra**: Receita média por transação.
- **Compradores Totais**: Número total de compradores únicos.
- **Visualizações**: Quantidade total de visualizações.
- **Compradores por Origem**: Compradores segmentados por canal de origem.
- **Usuários por Cidade**: Usuários segmentados por cidade.
- **Usuários Ativos por Gênero**: Segmentação de usuários ativos por gênero.
- **Usuários Ativos por Plataforma**: Segmentação por plataforma usada.

## Etapas de Desenvolvimento

### 1. Preparação dos Dados:
- Importação e limpeza da base de dados.
- Criação de colunas calculadas, como % de visualizações (visualizações/usuários ativos).

### 2. Construção dos Gráficos:
- **Gráficos do Tipo Cartão:**
   - Receita Total
   - Receita Média por Compra
   - Total de Compradores
   - Total de Visualizações
- **Gráficos do Tipo Pizza:**
   - Usuários Ativos por Gênero
   - Usuários Ativos por Plataforma
- **Gráficos do Tipo Barra:**
   - Compradores por Origem
   - Usuários Ativos por Cidade
- **Gráficos do Tipo Linha:**
   - Compradores por Dia
   - % de Visualizações por Data

### 3. Organização do Painel:
- Criação de duas páginas de dashboard para a visualização eficiente das métricas.
- Filtros para permitir a seleção de períodos de tempo e visualização personalizada.

## Ferramentas Utilizadas

- **Power BI**
- **Excel (para preparação dos dados)**
- **DAX (para cálculos e colunas calculadas)**

## Como Rodar o Projeto

1. Clone este repositório.
2. Importe os dados no Power BI.
3. Siga os passos descritos para criar as visualizações e o painel.

## Licença
