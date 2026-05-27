# 💸 FinanceAI — App de Organização de Finanças Pessoais com Vibe Coding

> Desafio de projeto desenvolvido como parte do Bootcamp **"Primeiros Passos com Inteligência Artificial"** da [DIO](https://dio.me) — trilha **Agentes e Vibe Coding: Criando Produtos e Automações com IA**.

---

## 📌 Sobre o Projeto

O **FinanceAI** é o conceito de um aplicativo mobile de organização financeira pessoal que funciona por meio de **conversas naturais com um agente de IA chamado Finn**.

A proposta resolve um problema real: a maioria das pessoas abandona aplicativos financeiros porque eles exigem muita entrada manual de dados e oferecem pouca personalização. O FinanceAI transforma o controle financeiro em uma conversa simples — como mandar mensagem para um amigo que entende de finanças.

> Este projeto foi desenvolvido inteiramente com a metodologia **Vibe Coding**: usando IA como parceira criativa, sem escrever uma linha de código.

---

## 🤖 O que é Vibe Coding?

Vibe Coding é uma forma de desenvolver com IA baseada em conversas naturais e bem estruturadas. Em vez de escrever código linha por linha, você aprende a **guiar a IA descrevendo suas ideias com clareza e intenção**.

```
Você mostra a vibe → a IA transforma em solução
```

---

## 📄 PRD — Product Requirements Document (Prompt Final)

> Este foi o prompt principal usado para guiar a IA na construção do conceito do app.

```markdown
# Contexto
Quero criar um aplicativo mobile-first chamado FinanceAI, que permite ao usuário 
controlar suas finanças pessoais de forma simples e natural — por meio de uma 
conversa com um agente de IA chamado Finn.

A experiência deve parecer uma troca de mensagens com um consultor financeiro amigo: 
sem formulários, sem planilhas, sem complicação.

# Problema
A maioria das pessoas abandona aplicativos financeiros após poucos dias de uso porque:
- Exigem entrada manual excessiva de dados
- A interface é fria, burocrática e pouco motivadora
- Não oferecem orientação personalizada
- Faltam recomendações automáticas e planos de economia adaptáveis

# Público-Alvo
Adultos entre 20–35 anos, iniciantes no controle financeiro, acostumados com apps 
de mensagens (WhatsApp, Instagram) e que nunca conseguiram manter um app financeiro 
por mais de 2 semanas.

# Funcionalidades-Chave (MVP)
1. Chat financeiro com o Agente Finn em linguagem natural
2. Classificação automática de transações por categoria
3. Metas financeiras personalizadas criadas via conversa
4. Dicas proativas de economia baseadas no perfil do usuário
5. Dashboard visual simples com resumo mensal e comparativos

# Agente Finn — Comportamento
- Tom amigável, direto e encorajador (como um amigo que entende de finanças)
- Usa emojis com moderação para tornar a conversa leve
- Nunca julga os gastos do usuário
- Celebra conquistas e metas cumpridas
- Faz alertas gentis quando limites estão próximos

# Entregável Esperado da IA
1. Plano de MVP com as 5 funcionalidades priorizadas
2. Fluxo conceitual de telas simulando a jornada do usuário
3. Comportamento detalhado do Agente Finn com exemplos de diálogo
4. Plano de validação inicial com métricas de sucesso

Tom de resposta: educativo, acessível, em português do Brasil.
```

---

## 🗺️ Fluxo de Telas — MVP

```
[Onboarding via Chat]
    ↓ Nome + renda mensal + 1ª meta
    
[Home — Chat com o Finn]
    ↓ Registrar gastos | Criar metas | Receber insights
    
[Dashboard]
    ↓ Resumo visual do mês por categoria
    
[Metas]
    ↓ Lista de objetivos + progresso + plano semanal
    
[Relatório Mensal]
    ↓ Comparativo mês a mês + análise do Finn
```

---

## 💬 Exemplos de Diálogo com o Finn

**Registro de gasto:**
```
Usuário: Gastei 45 reais no almoço hoje
Finn:    Anotado! 🍽️ Alimentação: R$ 45,00
         Você já usou 68% do seu limite mensal nessa categoria.
```

**Criação de meta:**
```
Usuário: Quero juntar R$ 1.500 para uma viagem até dezembro
Finn:    Ótimo objetivo! 🎯 Para isso, você precisa guardar 
         R$ 214/mês. Posso criar o plano agora?
```

**Insight proativo:**
```
Finn:    ⚠️ Você gastou R$ 320 em delivery esse mês — 40% a mais 
         que no anterior. Quer que eu sugira um plano de redução?
```

**Meta cumprida:**
```
Finn:    🎉 Parabéns! Você bateu sua meta de economia essa semana!
         Quer aumentar a meta do próximo mês?
```

---

## 📦 Plano de MVP

| # | Funcionalidade | Prioridade | Complexidade |
|---|---|---|---|
| 1 | Chat com registro de gastos em linguagem natural | Alta | Média |
| 2 | Classificação automática de categorias por IA | Alta | Média |
| 3 | Criação e acompanhamento de metas via conversa | Alta | Média |
| 4 | Insights e dicas proativas do Finn | Média | Alta |
| 5 | Dashboard visual com resumo e comparativos | Média | Baixa |

### Tecnologias Sugeridas

| Componente | Tecnologia |
|---|---|
| Frontend | React Native (mobile) / React (web MVP) |
| Backend | Node.js + API REST |
| IA / NLP | Claude API ou OpenAI GPT |
| Banco de dados | Supabase (PostgreSQL) |
| Autenticação | Google OAuth |

---

## ✅ Critérios de Sucesso do MVP

- ⏱️ Registrar um gasto em menos de **10 segundos**
- 🔁 Taxa de retorno ao app após 7 dias ≥ **40%**
- 🤖 **80%** dos gastos classificados corretamente pela IA sem edição manual
- 🎯 Pelo menos **1 meta** criada por usuário na primeira semana

---

## 🖼️ Prints das Interações com a IA

> *(Adicione aqui os prints ou GIFs das suas interações com o Lovable ou Copilot)*

| Etapa | Descrição |
|---|---|
| Print 1 | PRD sendo processado pela IA |
| Print 2 | Fluxo de telas gerado |
| Print 3 | Comportamento do Agente Finn definido |
| Print 4 | Plano de MVP retornado |

---

## 🧠 Reflexão sobre o Processo

### O que funcionou bem?

Estruturar o PRD com seções claras (contexto, problema, público, funcionalidades e entregável esperado) fez toda a diferença. A IA respondeu de forma muito mais direcionada quando o prompt tinha **intenção explícita** e **exemplos concretos** — como os diálogos do Agente Finn. Quanto mais específico o prompt, mais específica e útil a resposta.

### O que não funcionou como esperado?

Prompts vagos como "crie um app de finanças" geraram respostas genéricas demais. A IA precisa de **contexto, persona e formato esperado** para entregar algo realmente útil. Também aprendi que pedir tudo de uma vez pode diluir a qualidade — é melhor dividir em etapas.

### O que aprendi sobre conversar com IAs?

- **Clareza é poder:** quanto mais claro o prompt, melhor a entrega
- **A IA é uma parceira, não uma mágica:** ela amplifica suas ideias, mas você precisa ter ideias claras primeiro
- **Iterar é essencial:** raramente o primeiro prompt é o melhor — ajustar e refinar é parte do processo
- **Contexto importa mais que tamanho:** um prompt curto e bem estruturado supera um prompt longo e confuso
- **Tom e formato também são instruções:** dizer "responda em português, com tom educativo e use exemplos" muda completamente o resultado

---

## 🚀 Como Reproduzir Este Projeto

1. Leia o PRD acima e adapte ao seu estilo
2. Acesse o [Lovable](https://lovable.dev) ou o [Microsoft Copilot](https://copilot.microsoft.com)
3. Cole o prompt do PRD e peça o plano inicial do MVP
4. Itere com perguntas específicas (fluxo de telas, comportamento do agente, métricas)
5. Documente as interações com prints
6. Monte seu README e publique no GitHub

---

## 📚 Referências

- [DIO — Digital Innovation One](https://dio.me)
- [Bootcamp: Primeiros Passos com IA](https://dio.me)
- [Lovable — AI App Builder](https://lovable.dev)
- [Microsoft Copilot](https://copilot.microsoft.com)
- [Anthropic Claude](https://claude.ai)

---

*Desenvolvido com 💚 e Vibe Coding | Bootcamp DIO 2025*
