# Quita.IA - Fintech de Quitação Inteligente de Dívidas

> **Status do Projeto:** Em Desenvolvimento (Evolução por Fases)

O **Quita.IA** é uma solução digital estratégica desenvolvida para centralizar débitos, calcular o nível de endividamento do usuário e gerar planos inteligentes de descompressão financeira[cite: 5, 6]. O grande diferencial da plataforma é a aplicação automatizada do **Método Avalanche** (priorização baseada na maior taxa de juros) e ferramentas preditivas de simulação de aportes[cite: 5, 6].

Este repositório documenta a evolução completa do produto, integrando engenharia de requisitos, modelagem arquitetural de banco de dados e engenharia de front-end.

---

## Roadmap de Desenvolvimento (Evolução do Projeto)

Para demonstrar o ciclo completo de engenharia de software, o projeto foi dividido em marcos estratégicos:

- [x] **Fase 1 & 2 - Engenharia de Requisitos & UX:** Concepção do Épico, escrita e validação de *User Stories* com critérios de aceitação sob a metodologia INVEST[cite: 5]. Desenho das primeiras interfaces e fluxos de navegação.
- [x] **Fase 3 - Arquitetura de Dados:** Criação dos Modelos Lógico e Físico de dados e mapeamento do script DDL estruturado em conformidade com as regras de normalização para o Oracle Database[cite: 6].
- [x] **Fase 4 - Protótipo Front-End Responsivo:** Tradução das telas desenhadas em código semântico utilizando HTML5 estruturado e estilização moderna via utilitários do Tailwind CSS (com expansão de tema para Dark Mode)[cite: 4].
- [ ] **Próximas Fases - Engenharia de Back-End:** Implementação das regras de negócio, cálculo real do Índice de Sufoco Financeiro (ISF) e persistência dinâmica das tabelas no banco de dados[cite: 5, 6].

---

## Engenharia de Requisitos (Visão de Produto)

O escopo atual do sistema é sustentado por 5 *User Stories* principais mapeadas no MVP[cite: 5]:
1. **Centralização de Débitos:** Cadastro e agrupamento obrigatório de credores, valores e vencimentos[cite: 5].
2. **Dashboard de Visão Consolidada:** Sumarização do montante total ativo e impactos no orçamento mensal[cite: 5].
3. **Algoritmo Avalanche:** Ordenação automatizada com foco na redução do Custo Efetivo Total (maiores juros primeiro)[cite: 5].
4. **Simulador de Impacto:** Cálculo matemático de projeção para redução do tempo de endividamento em meses baseado em aportes adicionais[cite: 5].
5. **Mapeamento de Risco (ISF):** Cruzamento de dados de renda versus parcelas com alertas visuais semafóricos (Verde, Amarelo e Vermelho)[cite: 5].

---

## Arquitetura do Banco de Dados

A persistência do ecossistema foi normalizada em **8 tabelas relacionais** estruturadas especificamente para Oracle Database, contendo restrições (*constraints*) explícitas de validação e integridade[cite: 6]:

* `TB_USUARIO`: Gestão cadastral e controle de planos de acesso[cite: 6].
* `TB_DIVIDA` & `TB_TIPO_DIVIDA`: Centralização dos débitos associados às categorias do mercado[cite: 6].
* `TB_ISF` & `TB_FAIXA_RISCO`: Mapeamento e classificação dos níveis de risco de sufoco financeiro[cite: 6].
* `TB_RECOMENDACAO`: Alocação de inteligência preditiva associada especificamente à faixa de risco do usuário[cite: 6].
* `TB_SIMULACAO` & `TB_META`: Histórico de cenários testados e acompanhamento de metas de quitação[cite: 6].

*(Os diagramas lógicos/físicos e scripts DDL estão salvos na pasta raiz do repositório para consulta técnica)[cite: 4, 6].*

---

## Tecnologias e Ferramentas Utilizadas

* **Metodologias Ágeis:** Especificação INVEST / User Stories[cite: 5].
* **Modelagem de Dados:** Oracle SQL Developer / Data Modeler (Padrão Oracle Database)[cite: 6].
* **Construção de Interface:** HTML5 Semântico[cite: 4].
* **Estilização & Design System:** Tailwind CSS (Customização de paleta com injeção de scripts utilitários)[cite: 4].
* **Ícones & Fontes:** FontAwesome Icons / Google Fonts (Inter)[cite: 4].
* **Versionamento:** Git & GitHub[cite: 4].

---

## Autora

* **Stella Stoffelshaus Augusto**[cite: 5, 6]
* **RM:** 570666[cite: 5, 6]
* **Curso:** Análise e Desenvolvimento de Sistemas - FIAP[cite: 5, 6]
