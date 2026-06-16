# 🎮 CogniPlay

> **Slogan:** Onde a diversão encontra o desenvolvimento.
> **Propósito:** Plataforma web neuroinclusiva de estimulação cognitiva, focada no pareamento visual, categorização e rastreamento motor com telemetria em tempo real para profissionais, clínicas e famílias.

---

## 🚀 O que mudou nesta versão?

1. **Nova Identidade Visual e Nome:** Migração completa do antigo AcessiQuiz para **CogniPlay**, trazendo um conceito moderno e focado em gamificação terapêutica.
2. **Menu Central de Atividades:** Agora, o aluno e o profissional têm total autonomia. Não é mais necessário jogar em sequência obrigatória; você pode escolher diretamente o tema da sessão logo após o login.
3. **Desafio Ampliado (5 Pares por Tela):** Cada atividade foi expandida para conter **5 pares correspondentes** (totalizando 10 blocos na tela). Isso melhora o treino de atenção sustentada e varredura visual.
4. **Telemetria de Dashboard Inteligente:** O sistema agora salva no banco de dados local (`localStorage`) o nome do aluno acompanhado do tema específico jogado (ex: *Lucas (Mundo dos Animais)*), permitindo uma análise clínica muito mais cirúrgica.

---

## 🧠 Estrutura das Atividades Atuais

O **CogniPlay** conta com 5 grandes eixos de estimulação cognitiva:

* 🍎 **Pareamento de Frutas:** Estímulo perceptual básico através de elementos cotidianos de fácil assimilação.
* 🎨 **Associação de Cores:** Foco em categorização abstrata pura (sem formas ou ícones para dar pistas).
* ⭐ **Lógica de Símbolos:** Atenção focada através da discriminação de formas geométricas e símbolos espaciais.
* 🐶 **Mundo dos Animais:** Estímulo à linguagem, vocabulário e fixação de conceitos do reino animal.
* 😀 **Reconhecendo Emoções:** Alfabetização socioemocional através do pareamento de expressões faciais (Alegria, Surpresa, Calma, Amor e Raiva).

---

## 📊 Arquitetura de Telemetria (Dashboard)

A plataforma é dividida de forma bi-painel no arquivo `dashboard.html`:

### Painel do Profissional (Histórico Clínico)
* **Total de Atendimentos:** Registra o número total de rodadas salvas no dispositivo.
* **Média de Resposta Global:** Calcula o tempo médio em segundos gasto pelos alunos para completar os desafios.
* **Tabela de Logs Dinâmica:** Grava Data, Hora, Nome exato do Aluno, Nome da Atividade escolhida, Tempo exato e Erros cometidos.

### Painel dos Pais (Evolução Acolhedora)
* **Métricas Traduzidas:** Transforma os números puros em respostas de fácil entendimento sobre o tempo e os erros.
* **Nível de Foco Estimado:** Um algoritmo simples que categoriza o momento do aluno entre *Excelente*, *Bom Foco* ou *Em Evolução*.
* **Recado Dinâmico para a Família:** Uma carta devolutiva automatizada e humanizada baseada nos acertos do filho, estimulando o suporte parental e celebrando a persistência da criança.

---

## 🛠️ Tecnologias Utilizadas

* **HTML5** (Estruturação Semântica)
* **CSS3** (Estilização responsiva com variáveis, efeito Glassmorphism e gradientes Neon)
* **SVG Line Drawing** (Renderização dinâmica das linhas de conexão baseadas nas coordenadas dos nós)
* **Vanilla JavaScript** (Lógica de embaralhamento, gerenciamento de estado e manipulação do DOM)
* **Web Storage API** (Persistência local dos dados de telemetria sem necessidade de banco de dados externo)

---

## 💻 Como Executar o Projeto

1. Salve o código do jogo em um arquivo chamado `index.html`.
2. Salve o código do portal de desempenho em um arquivo chamado `dashboard.html` **na mesma pasta**.
3. Dê um duplo clique em `index.html` para abrir o jogo em qualquer navegador (computador, tablet ou celular).
4. Para checar o desempenho, basta abrir o arquivo `dashboard.html` a qualquer momento para ver os gráficos e relatórios atualizados em tempo real!
