## 🎯 Objetivo do MVP
> Tratar e desenvolver na plataforma Power BI, dados que permitam acompanhar a movimentação das principais cargas dos municípios paulista.
- Qual problema resolve? Dados de fontes públicas (IBAMA) consolidados e tratados, eliminando a inconsistência em dashboards de logística e gestão de riscos.
- Qual hipótese será validada?A integração entre tratamento de dados via Python e visualização no Power BI permite que gestores identifiquem concentrações de fluxo de carga e otimizem a logística regional.
- Qual valor será entregue ao usuário final? Tomada de decisão fundamentada em fontes oficiais para monitoramento logístico, com foco geográfico em municípios paulistas.

---

## 📝 Descrição da Solução
É um dashboard no Power BI integrado a bases de dados do IBAMA, focado no monitoramento de cargas movimentadas.

- Funcionalidades principais incluí:Visualização do volume de cargas movimentadas.
- Limitações conhecidas:Dependência da frequência de atualização das bases públicas do IBAMA.
- Escopo reduzido:Foco inicial em municípios paulistas e métricas de concentração logística.
---

## 👥 Personas / Usuários-Alvo
- **Persona 1:** Gestor de Operações Logísticas: Precisa centralizar dados brutos para monitorar a conformidade e o fluxo das cargas.
- **Persona 2:** Analista de Logística: Busca identificar tendências de movimentação para planejar rotas e otimizar o deslocamento de equipes regionais.
 

---

## 🔑 User Stories (Backlog do MVP)
| ID  | User Story                                                                 | Prioridade | Estimativa |
|-----|-----------------------------------------------------------------------------|------------|------------|
| 1    | Alta       | Como gestor, quero que os dados sejam importados da bases publicas do ibama, para que as informações sejam de confiança.                                | 4          | 1      |
| 2    | Média      | Como gestor,quero que os dados passem por um tratamento em linguagem de programação(Python),para garantir consistencia no dashboard.                    | 8          | 1      |
| 3    | Alta       | Como gestor,quero que os dados sejam apresentados em gráficos,para facilitar a interpretação e análise.                                                 | 8          | 1      |
| 4    | Média      | Como gestor,quero que o gráfico mostre as principais cargas movimentadas, para garantir o cumprimento das normas técnicas de transportes.                         |  6          | 1      |
| 5    | Alta       | Como gestor, quero que as métricas sejam dos municípios paulista, para identificar polos regionais de maior risco e otimizar o deslocamento das equipes regionais.     | 4         | 1      |
---

## 📅 Sprint(s) Relacionadas
| Sprint | Entregas Principais                          | Status   |
|--------|----------------------------------------------|----------|
| 01     | Limpeza inicial dos dados CSV (Python),e dashboard com os dados dos municípios em ascenção,estagnação e declínio no mercado.                        | Concluído|
| 02     | Dashboard interativo,que contenha módulos de busca e filtros,para análise específica.                           | Finalizado |

---

## 📊 Critérios de Aceitação
- O dashboard deve exibir dados originados exclusivamente da base tratada do IBAMA. 
- O sistema deve registrar, base de dados de municípios.
- Métricas coletadas: Uso de filtros em análise.

---

## 📈 Métricas de Validação
- Número de usuários que testaram o dashboard  
- Feedback qualitativo (positivo/negativo)  
- IRedução de tempo na identificação de polos logísticos.

  
## 🚀 Próximos Passos
- Melhorias planejadas após feedback  
- Ajustes de usabilidade  
- Expansão de funcionalidades para próximo incremento  

---

## 📂 Anexos / Evidências
- Slides da API
- Requisitos do cliente
- Colab (Python):

