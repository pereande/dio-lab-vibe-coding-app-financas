# PRD — FinanceAI: App de Organização de Finanças Pessoais com IA Conversacional

---

## 🧭 Contexto

Quero criar um aplicativo mobile-first chamado **FinanceAI**, que permite ao usuário controlar suas finanças pessoais de forma simples e natural — por meio de uma conversa com um agente de IA chamado **Finn**.

A experiência deve parecer uma troca de mensagens com um consultor financeiro amigo: sem formulários, sem planilhas, sem complicação.

---

## 🚨 Problema

A maioria das pessoas abandona aplicativos financeiros após poucos dias de uso porque:

- Exigem entrada manual excessiva de dados (data, categoria, valor, descrição)
- A interface é fria, burocrática e pouco motivadora
- Não oferecem orientação personalizada — só registram o que o usuário já sabe
- Faltam recomendações automáticas e planos de economia adaptáveis

**Resultado:** o usuário sente que o app trabalha *para a planilha*, não *para ele*.

---

## 🎯 Público-Alvo

**Persona principal:** Adultos entre 20–35 anos, iniciantes no controle financeiro, acostumados com apps de mensagens (WhatsApp, Instagram) e que nunca conseguiram manter um app financeiro por mais de 2 semanas.

**Características:**
- Renda variável ou fixa baixa/média
- Quer organização, mas não quer complexidade
- Confia mais em conversas do que em dashboards

---

## ✨ Funcionalidades-Chave (MVP)

### 1. Chat Financeiro com o Agente Finn
O usuário registra gastos em linguagem natural, como se estivesse mandando mensagem para um amigo.

> **Usuário:** "Gastei 45 reais no almoço hoje"
> **Finn:** "Anotado! 🍽️ Alimentação: R$ 45,00 — você já usou 68% do seu limite mensal nessa categoria."

### 2. Classificação Automática de Transações
A IA identifica a categoria do gasto automaticamente (alimentação, transporte, lazer, saúde, etc.) sem que o usuário precise selecionar nada.

### 3. Metas Financeiras Personalizadas
O usuário define objetivos em linguagem natural:

> "Quero juntar R$ 1.500 até o fim do ano para uma viagem"

O Finn cria um plano de economia semanal/mensal e acompanha o progresso.

### 4. Agente Finn — Dicas Proativas de Economia
Com base nos padrões de gasto do usuário, o Finn envia alertas e sugestões personalizadas:

> "Vi que você gastou R$ 320 em delivery esse mês — 40% a mais que no mês passado. Quer que eu sugira um plano para reduzir?"

### 5. Relatórios Simples e Visuais
Dashboard minimalista com:
- Resumo mensal por categoria (gráfico de rosca)
- Progresso das metas (barra de progresso)
- Comparativo mês a mês

---

## 🤖 Agente Finn — Definição de Comportamento

**Tom de voz:** Amigável, direto, encorajador. Fala como um amigo que entende de finanças — não como um banco ou contador.

**Personalidade:**
- Usa emojis com moderação para tornar a conversa leve
- Nunca julga os gastos do usuário
- Celebra conquistas (meta batida, semana sem gastos extras)
- Faz perguntas simples quando precisa de contexto

**Exemplos de comportamento:**
- Gasto registrado → confirma + informa saldo da categoria
- Limite quase atingido → alerta gentil
- Meta cumprida → parabeniza e sugere nova meta
- Sem registros há 3 dias → lembrete motivacional

---

## 🗺️ Fluxo de Telas (Conceitual)

```
[Onboarding]
    ↓ Nome + renda mensal via chat
[Home / Chat com Finn]
    ↓ Registrar gasto | Ver extrato | Definir meta
[Dashboard]
    ↓ Resumo visual do mês
[Metas]
    ↓ Lista de objetivos + progresso
[Relatório Mensal]
    ↓ Categorias + comparativo
```

---

## 📦 Entregável Esperado da IA (Lovable / Copilot)

Com base neste PRD, peço que você:

1. **Gere o plano de MVP** com as 5 funcionalidades priorizadas, recursos técnicos necessários e estimativa de complexidade.
2. **Crie o fluxo conceitual de telas** simulando a jornada completa do usuário — do onboarding até o primeiro relatório.
3. **Defina o comportamento detalhado do Agente Finn:** tom, exemplos de diálogo, regras de resposta e gatilhos de proatividade.
4. **Proponha um plano de validação inicial:** como medir se o MVP está resolvendo o problema (métricas, testes com usuário).

**Tom de resposta:** educativo, acessível, em português do Brasil.
**Formato:** use seções claras, exemplos de diálogo onde cabível, e listas objetivas.

---

## 📐 Requisitos Técnicos (referência para a IA)

| Componente | Tecnologia Sugerida |
|---|---|
| Frontend | React Native (mobile) ou React (web MVP) |
| Backend | Node.js + API REST |
| IA / NLP | Claude API ou OpenAI GPT |
| Banco de dados | Supabase (PostgreSQL) |
| Autenticação | Google OAuth |

---

## ✅ Critérios de Sucesso do MVP

- Usuário consegue registrar um gasto em menos de 10 segundos
- Taxa de retorno ao app após 7 dias ≥ 40%
- 80% dos gastos classificados corretamente pela IA sem edição manual
- Pelo menos 1 meta criada por usuário na primeira semana

---
Link para Teste : https://meet-finn-finance.base44.app

*PRD desenvolvido como parte do Bootcamp DIO — Desafio: App de Organização de Finanças Pessoais com Vibe Coding*
