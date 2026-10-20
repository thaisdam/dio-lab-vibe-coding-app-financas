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

🔗 **Acesse o app:** [PlanTha no Lovable](https://plantha.lovable.app/)

### Prompt utilizado no Lovable

```txt
Crie um aplicativo mobile-first chamado PlanTha, em português do Brasil, focado em organização financeira pessoal por meio de conversa com uma assistente de IA.

FUNCIONALIDADE PRINCIPAL

Um chat onde o usuário registra receitas, despesas e metas usando linguagem natural (ex.: "gastei R$ 25 no lanche"). A assistente interpreta a mensagem, categoriza a transação automaticamente e responde de forma amigável (ex.: "Despesa registrada: R$ 25 em Alimentação 🍔").

Como é um protótipo, simule as respostas da IA e use dados fictícios realistas para demonstrar o funcionamento.

CATEGORIAS

Alimentação, Transporte, Moradia, Lazer, Saúde, Educação, Compras, Assinaturas, Salário e Outros.

TELAS (5)

1. Onboarding: apresentação do app, benefícios e botão "Começar".

2. Chat (tela principal): histórico de conversa, campo de mensagem e botões de sugestões rápidas.

3. Resumo Financeiro: saldo, receitas, despesas, maior categoria de gasto e gráfico por categoria.

4. Metas: lista de metas com valor, valor acumulado, barra de progresso (%) e valor restante.

5. Perfil: configurações, notificações e privacidade.

Inclua uma barra de navegação inferior com ícones e texto.

ALERTAS INTELIGENTES

Mensagens amigáveis no chat, como "Você já usou 85% do orçamento de Lazer" ou "Faltam R$ 80 para sua meta mensal!".

IDENTIDADE VISUAL

Estilo fofo, minimalista e acolhedor, com cantos arredondados e tema claro.

Cores: rosa pastel #F8BBD0, azul pastel #B3E5FC, amarelo pastel #FFF3B0, destaque #6C63FF e texto escuro #3A3346.

Fontes: Poppins para títulos e Inter para textos.

ACESSIBILIDADE

Alto contraste entre texto e fundo, fontes legíveis, ícones sempre acompanhados de texto e informações que não dependam apenas de cores.

PERSONALIDADE DA ASSISTENTE

Empática, motivadora, clara e sem termos técnicos, focada em ajudar iniciantes a criar bons hábitos financeiros.
```

### 📱 Telas do App

**Onboarding**

<img width="1920" height="1020" alt="onboarding" src="https://github.com/user-attachments/assets/56b300cf-ce20-49b3-8a9d-ad72a928c441" />


**Chat com a Tha**

<img width="1920" height="1020" alt="chat" src="https://github.com/user-attachments/assets/4f8488e7-164c-407c-a03d-a1ba6552bffb" />


**Resumo Financeiro**

<img width="1920" height="1020" alt="resumo" src="https://github.com/user-attachments/assets/b10b3efc-b2a0-4de0-b2f4-fd2236df65d5" />


**Metas**

<img width="1920" height="1020" alt="metas" src="https://github.com/user-attachments/assets/d3242a52-51ff-41eb-a322-2f621164303f" />


**Perfil**

<img width="1920" height="1020" alt="perfil" src="https://github.com/user-attachments/assets/fef07948-9121-4768-85a2-b50455ab5fd3" />


### 🛠️ Corrigindo erros com a IA

Ao navegar pelas telas, o app apresentou o erro "This page didn't load".
Usei a função "Corrigir erro" do Lovable e a IA resolveu o problema.

<img width="1920" height="1020" alt="erro" src="https://github.com/user-attachments/assets/37c5bd74-a9e9-414d-ae65-f8e94f41c421" />



## 💡 Conceito do App

(vamos escrever depois)

## 🧠 O que aprendi

(vamos escrever no final)
