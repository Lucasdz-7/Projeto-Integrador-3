# 📌 MVP - SprintCoders

## 🎯 Objetivo do MVP

> O MVP tem como objetivo validar a criação de um **dashboard interativo em Power BI** voltado à análise de dados de **Análise de Segurança Viária no Brasil**.

### 🧩 Problema que resolve
Falta de uma ferramenta unificada e visual para análise dos dados da segurança viária, e correlação de crescimento da frota de veículos pesados e sinistros de trânsito fatais .

### 💡 Hipótese a ser validada
Um dashboard interativo em Power BI facilita a compreensão dos indicadores e apoia decisões estratégicas.

### 🚀 Valor entregue ao usuário
Visualização clara e dinâmica de métricas como mortalidade, sinistros, frota, população e tendências, auxiliando na análise e formulação de políticas públicas de segurança viária.

---

## 📝 Descrição da Solução

> Nesta etapa, será desenvolvido um protótipo funcional de dashboard interativo, integrando dados públicos da PRF e do SENATRAN (2023–2024), estruturados em Python, para análise de indicadores como sinistros, óbitos e frota de veículos, apoiando a geração de insights em segurança viária.

### ⚙️ Funcionalidades principais
- Coleta e tratamento de dados da PRF e SENATRAN.
- Consolidação dos dados em dataframe para análise.
- Desenvolvimento de visualizações iniciais no Power BI.
- Criação de métricas de segurança viária em nível estadual e nacional  

### ⚠️ Limitações conhecidas
- O MVP apresenta apenas indicadores iniciais, sem implementação de filtros avançados ou atualização automática dos dados.
- A base de dados está limitada ao período de 2023 a 2024 e às fontes integradas na primeira sprint (PRF e SENATRAN).  

### 🎯 Escopo reduzido
- O foco do MVP é validar a integração dos dados da PRF e SENATRAN e sua visualização em um único ambiente, priorizando clareza, funcionalidades básicas e viabilidade técnica.

---

## 👥 Personas / Usuários-Alvo
- **ONSV:** (Observatório Nacional de Segurança Viária): utiliza a plataforma para analisar dados de sinistros, mortalidade e frota de veículos, permitindo identificar padrões, comparar indicadores entre estados e apoiar a tomada de decisão em segurança viária.. 
---

## 🔑 User Stories (Backlog do MVP)

| ID  | User Story                                                                                                                       | Prioridade | Estimativa  |
|-----|----------------------------------------------------------------------------------------------------------------------------------|------------|-------------|
| US1 | Como Coordenador do Projeto: Quero acessar e estruturar dados da PRF (2023–2024) sobre sinistros e óbitos para uso no dashboard. | Alta       | 3 pontos    |
| US2 | Como Coordenador do Projeto: Quero acessar e estruturar dados do SENATRAN (2023–2024) sobre frota de veículos pesados.           | Alta       | 3 pontos    |
| US3 | Como Coordenador do Projeto: Quero analisar a correlação entre frota e óbitos utilizando o método de Pearson..                   | Alta       | 1 pontos    |
| US4 | Como Coordenador do Projeto: Quero Consolidar os dados de frota, óbitos e sinistros em um único dataframe.                       | Média      | 3 pontos    |
| US5 | Como Coordenador do Projeto: Quero desenvolver um protótipo inicial do dashboard para visualização dos dados.                    | Baixa      | 5 pontos    |


---

## 📅 Sprint(s) Relacionadas
| Sprint | Entregas Principais                          | Status   |
|--------|----------------------------------------------|----------|
| 01     | Coleta e tratamento de dados (PRF e SENATRAN)| Concluído|
| 01     | Consolidação e estruturação dos dados        | Concluído|
| 01     | Protótipo do Dashboard Power BI              | Concluído |

---

## 📊 Critérios de Aceitação
- O MVP deve permitir a visualização da estrutura da base de dados utilizada no projeto, bem como um protótipo funcional do dashboard.
- O sistema deve integrar e apresentar dados de sinistros, óbitos e frota de veículos provenientes da PRF e do SENATRAN.
- Métricas apresentadas devem incluir: quantidade de sinistros, número de óbitos, tamanho da frota, indicadores por estado e análises comparativas entre regiões. 

---

## 📈 Métricas de Validação
- Feedback qualitativo: foi positivo, indicando o que foi desenvolvido e orientando nos pontos a melhorar.

---

## 🚀 Próximos Passos
- Prosseguir com o desenvolvimento do projeto incrementando todo o conteúdo realizado
  
---

## 📂 Anexos / Evidências
- Protótipo inicial do dashboard
![Protótipo Inicial](.sprint01png)
- Vídeo (MVP): [Clique aqui para assistir](https://www.youtube.com/watch?v=lXKVnO3EobU)

 
