```markdown
# 🎮 AcessiQuiz Cloud — Edição Escolar & AEE

> **Plataforma de gamificação e telemetria cognitiva em tempo real para apoio ao Atendimento Educacional Especializado (AEE) e inclusão escolar.**

---

## 📋 Sobre o Projeto

O **AcessiQuiz Cloud** é uma solução digital desenvolvida para responder aos desafios pedagógicos da
neurodivergência (como TEA e TDAH) tanto no contexto da educação escolar regular quanto nas salas de
recursos multifuncionais do **AEE (Atendimento Educacional Especializado)**.

Ao contrário de quizzes tradicionais que geram pressão por tempo e ansiedade, o AcessiQuiz funciona como
um ambiente de acolhimento tátil e visual. Enquanto o **usuário ativo** joga e responde a estímulos baseados
nas **Funções Executivas** (Controle Inibitório, Planejamento e Flexibilidade Cognitiva), o sistema realiza uma
**telemetria bidirecional em tempo real** enviando métricas diretamente para a nuvem da **Google Cloud
Platform (Firebase)**.

---

## ✨ Funcionalidades Principais

* **Identificação Inclusiva por Sessão:** Permite que professores e terapeutas insiram o nome do usuário antes
do início. Cada execução gera um ID único (`sessaoID`), isolando os dados clínicos para evitar o cruzamento indevido
de históricos.
* **Estímulos Neuropsicopedagógicos:** Perguntas e alternativas estruturadas a partir de matrizes científicas de
avaliação (Ex: Paradigma de Stroop para controle inibitório, sequenciamento lógico para planejamento).
* **Design Responsivo e Tátil:** Interface totalmente adaptada para dispositivos móveis (smartphones e tablets)
com botões grandes, contraste acessível e ícones de suporte visual (*FontAwesome*).
* **Dashboard Clínico Integrado:** Um painel reativo que limpa o gráfico automaticamente a cada novo usuário ativo
e mantém uma **Tabela de Histórico Comparativo** global para análises de evolução a longo prazo.

---

## 🛠️ Tecnologias Utilizadas

* **Frontend do Jogo e Painel:** HTML5, CSS3 (Variáveis nativas e efeitos de feedback tátil) e JavaScript
Moderno (ES6+ Modules).
* **Banco de Dados e Telemetria:** [Google Firebase Firestore](https://firebase.google.com/) (Persistência e
escuta reativa via `onSnapshot` em nuvem).
* **Renderização de Dados:** [Chart.js](https://www.chartjs.org/) (Gráficos de linha dinâmicos e cronológicos).
* **Ícones e Identidade:** FontAwesome 6.5.1.

---

## 📂 Estrutura de Arquivos

---

## 📂 Estrutura de Arquivos

```bash
├── index.html          # Interface do Jogo (Acesso do Aluno/Usuário)
├── dashboard.html      # Painel Analítico (Acesso do Especialista/Professor)
└── README.md           # Documentação do projeto (Este arquivo)
