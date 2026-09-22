# 🎯 PMDF 2027 — Trello de Estudos Estratégico

Uma aplicação web interativa (Single Page Application - SPA) desenvolvida em **HTML5, CSS3 puro e JavaScript Vanilla**, projetada para otimizar o acompanhamento, planejamento e execução da preparação para o concurso da **Polícia Militar do Distrito Federal (PMDF)**.

O sistema combina a metodologia do **Kanban Cíclico** com métricas de desempenho, controle por níveis de graduação (*faixas de acertos*) e gerenciamento dinâmico do edital.

---

## 📌 Principais Funcionalidades

- 📋 **Quadro Kanban de Metas Semanais:**
  - Organização cronológica (Avançar/Voltar semanas).
  - Cards interativos por tipo de estudo (*Bloco de Estudo, Revisão Diária, Revisão em Bloco, Revisão Geral, Redação, Simulado*).
  - Suporte a **Drag and Drop** (arrastar e soltar) para flexibilizar a rotina de estudos.
  - Bloqueio inteligente de movimentação em revisões fixas.

- 📊 **Dashboard de Métricas e Desempenho:**
  - Métricas configuráveis por período (7 dias, 30 dias ou Todo o período).
  - Mapeamento em tempo real de: total de questões respondidas, porcentagem global de acertos, metas de reforço necessárias e progresso da semana.

- 🏆 **Sistema de Graduação por Faixas:**
  - Sistema de gamificação focado em **questões certas** (evolução a cada 1.000 acertos).
  - Interface visual com indicação das faixas (Branca, Cinza, Amarela, Laranja, Verde, Azul, Roxa, Marrom e Preta).

- ⚙️ **Gerenciador de Matérias e Assuntos:**
  - Modal integrado para **criar, editar, arquivar e restaurar** conteúdos programáticos.
  - Suporte ao edital pré-carregado contendo todas as disciplinas exigidas para o concurso (Direito Administrativo, Constitucional, Penal, Processual Penal, Criminologia, RLM, Português, Legislação da PMDF, etc.).

- 📝 **Lançamento e Histórico de Questões:**
  - Cadastro simplificado com calculador automático de erros e taxa percentual.
  - Tabela de lançamentos recentes com opção de exclusão.

- 🌗 **Modo Claro / Escuro (Dark Mode):**
  - Alternância de tema integrada ao cabeçalho.

- 💾 **Persistência de Dados e Compatibilidade:**
  - Salvamento automático em `localStorage` via mecanismo SafeStorage (compatível com Safari e iOS).
  - Modal de **Reinício Seguro** com confirmação por palavra-chave para prevenção de perda acidental de dados.

📂 Estrutura do Código

├── index.html
│   ├── <head>   -> Variáveis de tema (Dark/Light) e regras de estilo (CSS).
│   ├── <body>   -> Painéis do Dashboard, Quadro Kanban, Formulários e Modais.
│   └── <script> -> Regras de negócio, filas dinâmicas de tópicos e persistência.


📄 Licença

Este projeto é de uso livre para fins educacionais e de apoio a estudos para concursos públicos.
