# 💸 PlanTha – App de Finanças Pessoais com Vibe Coding

Projeto desenvolvido para o Desafio de Projeto da DIO, usando **Vibe Coding**
com o **Copilot** e o **Lovable**. O PlanTha é um app de organização financeira
em que o usuário controla os gastos conversando, como num chat.

---

## 📝 PRD Inicial (meu rascunho)

```txt
# Contexto
Quero criar um aplicativo de Organização de Finanças Pessoais chamado PlanTha,
que funcione por meio de conversas com o usuário, como um chat.
A ideia é facilitar o controle financeiro de forma simples e natural,
sem formulários manuais ou planilhas complexas.

# Problema
Muitas pessoas desistem de controlar seus gastos porque os apps atuais exigem
muita digitação manual, têm telas confusas e não dão recomendações personalizadas.
Quero resolver isso com uma experiência de conversa e sugestões automáticas de economia.

# Público-Alvo
Jovens de 18 a 30 anos que estão começando a vida financeira, recebem
o primeiro salário e não têm costume de anotar gastos.

# Funcionalidades Principais (MVP)
1. Registro de gastos e ganhos pelo chat (ex.: "gastei 25 reais no lanche").
2. Categorização automática das transações (alimentação, transporte, lazer...).
3. Criação e acompanhamento de metas (ex.: "quero guardar R$ 300 este mês").
4. Agente de IA que sugere um plano de economia personalizado.
5. Resumo semanal simples com gráficos e saldo.
6. Alertas amigáveis quando o usuário estiver perto de estourar o limite de uma categoria.

# Requisitos de Experiência
- Linguagem amigável e sem termos técnicos.
- Interface limpa, acessível e fácil de usar no celular.
- Estilo visual fofo, tema claro, com cores pastéis (rosa, azul e amarelo).

# Entregável Esperado da IA
Gerar um plano de MVP contendo:
- Fluxo principal de uso do app (passo a passo do usuário).
- Descrição das telas principais.
- Exemplos de conversas entre o usuário e o agente financeiro.
- Sugestão de identidade visual (cores, tipografia e tom de voz).

```

## ✨ PRD Refinado no Copilot

```txt
### 📌 Visão Geral

O **PlanTha** é um aplicativo de organização financeira pessoal baseado em **IA conversacional**.

O usuário controla sua vida financeira por meio de um chat, registrando gastos, ganhos e metas usando linguagem natural. A IA entende as mensagens, organiza as informações automaticamente e oferece orientações financeiras personalizadas.

> **Proposta de valor:** "Controle suas finanças apenas conversando."

### ❗ Problema

Muitas pessoas abandonam apps financeiros porque:

- Exigem cadastro manual de gastos.
- Possuem interfaces complexas.
- Utilizam linguagem técnica.
- Não fornecem orientação personalizada.

O PlanTha resolve isso com uma experiência simples, conversacional e acessível.

### 👥 Público-Alvo

Jovens de 18 a 30 anos que:

- Estão iniciando sua vida financeira.
- Recebem salário ou renda recorrente.
- Não possuem hábito de controlar gastos.
- Preferem experiências simples e intuitivas.

### 🚀 MVP

#### 1. Registro de Gastos e Receitas
O usuário registra movimentações financeiras enviando mensagens no chat.

> **Usuário:** "Gastei R$ 25 no lanche."
> **IA:** "Despesa registrada: R$ 25 em Alimentação."

#### 2. Categorização Automática
A IA identifica automaticamente a categoria da transação.

**Categorias iniciais:** Alimentação, Transporte, Moradia, Lazer, Saúde, Educação, Compras, Assinaturas, Salário e Outros.

> **Usuário:** "Paguei R$ 40 de Uber."
> **IA:** "Despesa registrada em Transporte."

#### 3. Metas Financeiras
Criação e acompanhamento de metas por conversa.

> **Usuário:** "Quero guardar R$ 300 este mês."
> **IA:** "Meta criada. Vou acompanhar seu progresso até o final do mês."

**Informações exibidas:** valor da meta, valor acumulado, progresso (%) e valor restante.

#### 4. Agente Financeiro com IA
A IA atua como uma assistente financeira pessoal, analisando hábitos e sugerindo melhorias.

> **Usuário:** "Como posso economizar mais?"
> **IA:** "Seus maiores gastos estão em alimentação. Reduzir pedidos por delivery pode ajudar você a alcançar sua meta mais rápido."

#### 5. Resumo Semanal
Visão rápida da situação financeira do usuário.

**Exibe:** receitas, despesas, saldo atual, maior categoria de gasto, progresso das metas e gráfico por categoria.

> "Você recebeu R$ 1.800 e gastou R$ 1.120 nesta semana. Seu saldo atual é de R$ 680."

#### 6. Alertas Inteligentes
Notificações amigáveis sobre comportamentos importantes.

- "Você já utilizou 85% do orçamento de Lazer."
- "Seus gastos desta semana estão acima da média."
- "Faltam R$ 80 para atingir sua meta mensal."

### 🔄 Fluxo Principal

1. Usuário cria a conta.
2. Conversa com a IA pela primeira vez.
3. Registra gastos e receitas pelo chat.
4. Cria metas financeiras.
5. Recebe resumos e recomendações.
6. Acompanha sua evolução ao longo do tempo.

### 📱 Telas Principais

| Tela | Conteúdo |
|---|---|
| **Onboarding** | Apresentação do produto, benefícios principais e botão "Começar" |
| **Chat** (principal) | Histórico de conversa, campo de mensagem e sugestões rápidas |
| **Resumo Financeiro** | Saldo, receitas, despesas, gráficos e categorias |
| **Metas** | Lista de metas, progresso e valores acumulados |
| **Perfil** | Configurações, notificações e privacidade |

### ♿ Acessibilidade e Design Inclusivo

- Mobile-first.
- Alto contraste entre textos e fundos.
- Tipografia legível.
- Suporte a leitores de tela.
- Linguagem simples e inclusiva.
- Ícones sempre acompanhados de texto.
- Não depender apenas de cores para comunicar informações.
- Fluxos simples e com feedback imediato.

### 🎨 Identidade Visual

**Estilo:** amigável, minimalista, acolhedor e "fofo".

| Cor | Código |
|---|---|
| Rosa pastel | `#F8BBD0` |
| Azul pastel | `#B3E5FC` |
| Amarelo pastel | `#FFF3B0` |
| Destaque | `#6C63FF` |
| Texto escuro | `#3A3346` |

**Tipografia:** Poppins (títulos) e Inter (textos).

```

## 🎨 Protótipo no Lovable

(vamos adicionar prints/vídeo no Passo 4)

## 💡 Conceito do App

(vamos escrever depois)

## 🧠 O que aprendi

(vamos escrever no final)
