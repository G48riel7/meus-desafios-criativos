# 🚀 Desafio Criativo: Acelerando Sua Produtividade Pessoal com IA

### Caderno de Engenharia de Prompt | Desafio Criativo DIO

---

## 📌 Contexto e Objetivos

### Por que este tema?

A produtividade pessoal é um dos campos onde a IA generativa mais entrega valor imediato: organizar tarefas, priorizar o que importa e reduzir o tempo gasto em decisões repetitivas. Este caderno documenta o processo de construção, passo a passo, de um **prompt final** capaz de orientar uma IA a gerar um plano de produtividade sob medida — registrando também os ajustes e aprendizados ao longo do caminho.

### Objetivos do Desafio

- [ ] Definir uma intenção clara para o que a IA deve produzir
- [ ] Levantar o contexto pessoal relevante (rotina, gargalos, restrições)
- [ ] Especificar formato e tom da resposta esperada
- [ ] Testar, refinar e documentar versões do prompt
- [ ] Chegar a um prompt final reutilizável

---

## 🧩 Construção Passo a Passo

### Passo 1 — Intenção clara
*O que eu quero que a IA me ajude a fazer?*

```
(escreva aqui sua resposta)
```

### Passo 2 — Contexto
*Qual é o meu cenário atual (rotina, trabalho, estudos)? Qual o maior gargalo da minha produtividade hoje?*

```
(escreva aqui sua resposta)
```

### Passo 3 — Instruções específicas
*Formato desejado (lista, tabela, texto corrido)? Tom (direto, motivacional, técnico)?*

```
(escreva aqui sua resposta)
```

---

## 🧪 Engenharia de Prompts e "Cicatrizes"

Esta seção documenta o processo de elaboração do prompt — acertos, ajustes e lições aprendidas.

---

### 🔵 Rodada 1 — Prompt Inicial (Diagnóstico)

**Objetivo:** Testar uma primeira versão simples, só com a intenção.

#### Prompt 1.1
```
"Me ajude a ser mais produtivo."
```

**Resposta obtida:** Genérica, cheia de dicas óbvias (faça listas, durma bem, evite distrações), sem relação com minha rotina real.

**⚠️ Dificuldade encontrada:** Faltou contexto — a IA não sabia nada sobre minha realidade.

**🔧 Ajuste feito:** Acrescentar contexto pessoal explícito (ver 1.2).

---

#### Prompt 1.2 (versão refinada)
```
"Considerando que [contexto do Passo 2], me ajude a [intenção do Passo 1]."
```

**Resposta obtida:** Mais direcionada, mas ainda sem formato definido — saiu como um texto corrido longo.

**✅ Lição aprendida:** Contexto melhora a relevância, mas não resolve a usabilidade da resposta.

---

### 🟡 Rodada 2 — Prompt com Formato e Tom

**Objetivo:** Tornar a resposta aplicável de fato no dia a dia.

#### Prompt 2.1
```
"Considerando que [contexto], crie um [formato: lista/tabela] para [intenção],
com tom [direto/motivacional/técnico]."
```

**Resposta obtida:** Estrutura usável, fácil de seguir e revisar.

**✅ O que funcionou:** Especificar formato de saída (tabela, bullet points, etc.) muda completamente a aplicabilidade da resposta.

---

### 🔴 Rodada 3 — Troubleshooting (Dificuldades Encontradas)

#### Problema 1: Resposta genérica demais
**Causa:** Prompt sem contexto pessoal.
**Solução:** Sempre incluir rotina, restrições de tempo e gargalo específico.

#### Problema 2: Resposta longa demais para o dia a dia
**Causa:** Falta de limitador no prompt.
**Solução:**
```
"Responda em no máximo X itens" ou "Resuma em uma tabela de até 7 linhas"
```

#### Problema 3: Sugestões pouco realistas para minha rotina
**Causa:** A IA não tinha restrições de tempo/recursos.
**Solução:** Adicionar explicitamente limites reais (ex: "tenho só 1h livre por dia").

---

## 📖 Prompt Final — Entrega

Depois de preencher os Passos 1, 2 e 3 e passar pelas rodadas de ajuste, o prompt final fica assim:

```
Você é um assistente especializado em produtividade pessoal.

Contexto: [respostas do Passo 2]

Tarefa: [respostas do Passo 1]

Instruções de formato: [respostas do Passo 3]

Gere uma resposta clara, prática e aplicável imediatamente à minha rotina.
```

### Exemplo de prompt final preenchido

```
Você é um assistente especializado em produtividade pessoal.

Contexto: Trabalho em horário comercial e estudo à noite. Tenho dificuldade
em priorizar tarefas e costumo me distrair com notificações.

Tarefa: Crie um plano semanal de estudos e trabalho que equilibre minhas
responsabilidades, com blocos de foco e pausas estratégicas.

Instruções de formato: Apresente em formato de tabela, com tom direto e
motivacional, dividido por dia da semana.

Gere uma resposta clara, prática e aplicável imediatamente à minha rotina.
```

---

## 🔁 Prompts Reutilizáveis para Produtividade

Coleção de prompts testados, prontos para reuso em qualquer LLM (Claude, ChatGPT, Gemini etc.):

#### 📌 Organização e Priorização
```
"Liste minhas tarefas de hoje em ordem de prioridade, considerando urgência e impacto: [tarefas]."
```
```
"Transforme esta lista de tarefas soltas em um plano com horários sugeridos: [tarefas]."
```

#### 📌 Planejamento de Rotina
```
"Monte um cronograma semanal equilibrando [atividade A] e [atividade B], com blocos de foco de [X] minutos."
```

#### 📌 Redução de Sobrecarga
```
"Tenho estas tarefas: [lista]. Quais posso eliminar, delegar ou adiar sem grande impacto?"
```

#### 📌 Revisão e Ajuste
```
"Avalie minha semana com base neste resumo: [resumo]. O que ajustar para a próxima?"
```

---

## 🛠️ Ferramentas Utilizadas

- **Claude (Anthropic)** — construção e refinamento dos prompts
- **GitHub** — versionamento e portfólio do desafio
- **DIO** — plataforma do desafio criativo

---

## 👤 Autor

**Gabriel**

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Gabriel_Alves-0077B5?style=flat&logo=linkedin)](https://www.linkedin.com/in/gabriel-alves-06755822b/)
---

⭐ Se este repositório foi útil para você, deixa uma estrela!
