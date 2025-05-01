# 📊 Análise de Dados de Acidentes em Rodovias Federais


- **Paulo Eduardo de Brito Oliveira**  

---

## 📌 Contexto do Projeto
Este projeto visa analisar dados de acidentes em rodovias federais brasileiras no período de 2018 a 2020. O foco principal é identificar padrões e causas para subsidiar ações preventivas e orientar a **expansão estratégica das operações na região Sudeste**, com o objetivo de **aumentar a segurança viária**.

---

## 🔍 Metodologia

### 🔗 Fonte de Dados
- Dados públicos disponíveis em:  
  [Portal da PRF](https://www.gov.br/prf/pt-br/acesso-a-informacao/dados-abertos/dados-abertos-acidentes)

### 🛠 Ferramentas Utilizadas
- Power BI
- Linguagem DAX
- Templates empresariais privados (EmpowerLogistics)
- PySpark
---

## 📈 Desenvolvimento do Dashboard

### 🎯 Objetivos Principais
1. **Quantificação de Ocorrências**  
   - Total de acidentes por ano, mês, dia da semana e horário.
   - Distribuição por estado e BR.

2. **Dados de Vítimas**  
   - Total de mortos, feridos leves, feridos graves e ilesos.

3. **Geolocalização**  
   - Mapa interativo com latitude e longitude dos acidentes.

4. **Análise de Causas**  
   - Principais causas de acidentes (top 7).

5. **Acidentes Graves**  
   - Foco em ocorrências com 3 ou mais óbitos.

### 🧰 Funcionalidades Adicionais
- Filtros por **ano, mês, estado, tipo de acidente e classificação**.
- Métricas customizáveis via DAX.
- Relacionamentos dinâmicos entre tabelas.
- Possibilidade de expansão com novas análises e insights.

---

## 📂 Dicionário de Dados (Principais Variáveis)

| Variável               | Descrição                                                                 |
|------------------------|--------------------------------------------------------------------------|
| `id`                   | Identificador único do acidente                                          |
| `data_hora`            | Data e hora do acidente                                                  |
| `uf`                   | Estado da ocorrência                                                     |
| `br`                   | Número da rodovia federal                                                |
| `km`                   | Quilômetro exato do acidente                                             |
| `municipio`            | Município da ocorrência                                                  |
| `causa_acidente`       | Causa principal identificada                                             |
| `tipo_acidente`        | Tipo do acidente (colisão, capotamento etc.)                             |
| `classificacao_acidente`| Gravidade do acidente (sem vítimas, feridos, fatais)                    |
| `fase_dia`             | Fase do dia (manhã, tarde, noite)                                        |
| `sentido_via`          | Sentido da pista no momento do acidente                                  |
| `condicao_meteorologica`| Condições climáticas                                                     |
| `tipo_pista`           | Tipo de pista (simples, dupla etc.)                                      |
| `tracado_via`          | Curvas, retas, interseções                                               |
| `pessoas`              | Total de pessoas envolvidas                                              |
| `mortos`               | Total de mortes                                                          |
| `feridos_leves`        | Total de feridos leves                                                   |
| `feridos_graves`       | Total de feridos graves                                                  |
| `ilesos`               | Total de ilesos                                                          |
| `veiculos`             | Total de veículos envolvidos                                             |
| `latitude` / `longitude` | Coordenadas geográficas do local                                       |

---

## 📊 Principais Análises do Dashboard

### 🔴 Acidentes com Vítimas Fatais
- **MG** como estado com maior número de óbitos.
- Maior concentração entre **17h e 19h**.
- Principal causa: **falta de atenção**.

### 🟧 Acidentes com Feridos
- Pico de acidentes em horários de tráfego intenso.
- Principais causas: desatenção, velocidade e ingestão de álcool.

### 🟩 Acidentes Sem Vítimas
- Destaque para falhas mecânicas como causa predominante.
- Indica necessidade de **manutenção preventiva**.

### ⚖️ Análise Comparativa
- Estados com maior volume de acidentes.
- Dias da semana e horários com maior incidência.
- Comparação entre tipos de pista e traçado viário.

---

## ✅ Conclusões e Recomendações

### 🔎 Conclusões
- Padrões temporais e geográficos claros nos dados.
- Causas humanas (desatenção, imprudência) predominam.
- Necessidade de melhoria em trechos críticos de pista simples.

### 💡 Recomendações
- **Campanhas educativas** nas rodovias com maior índice de acidentes.
- Investimentos em **infraestrutura viária** e duplicações.
- **Aumento da fiscalização** em horários de pico.
- Incentivo à **manutenção regular de veículos**.

---

## 🧠 Métodos Utilizados no Power BI

| Recurso               | Descrição                                                                 |
|-----------------------|---------------------------------------------------------------------------|
| **DAX**               | Linguagem usada para medidas e cálculos dinâmicos                         |
| **Calendário**        | Tabela de datas para análise temporal eficiente                           |
| **Relacionamentos**   | Integração entre tabelas para permitir filtros cruzados                   |
| **Medidas**           | KPIs dinâmicos (ex: total mortos, feridos, acidentes graves etc.)         |
| **Templates Empresariais** | Estrutura padrão interna utilizada para layout e consistência         |

