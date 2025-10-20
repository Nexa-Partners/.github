# 💰 Nexa – Plataforma de Gestão Financeira Pessoal

O **Nexa** é uma plataforma **SaaS** voltada para o **gerenciamento financeiro pessoal**, projetada para ajudar indivíduos a registrar despesas, acompanhar receitas e monitorar investimentos de forma prática e segura.  

Nosso objetivo é **simplificar o controle financeiro**, **automatizar cálculos** e oferecer uma **visão clara da saúde econômica do usuário** — tudo com uma **interface moderna e intuitiva**.

---

## ⚡ Visão Rápida

- **Público-alvo:** pessoas físicas que desejam controlar melhor suas finanças, acompanhar ganhos e investir de forma inteligente.  
- **Proposta de valor:** gerenciamento unificado de contas, despesas, receitas e investimentos, com relatórios detalhados e insights automáticos.  
- **Estado:** ideia validada, backend em desenvolvimento com **Go (Fiber)** e **PostgreSQL via Supabase**.  
- **🎯 Objetivo:** **MVP funcional até novembro de 2025.**

---

## 💼 O que entregamos (principais funcionalidades)

### 🧾 Gestão Financeira Completa
- Registro manual e categorizado de despesas e receitas.  
- Filtros por data, categoria, tipo e forma de pagamento (Pix, cartão, dinheiro).  
- Upload opcional de nota fiscal/foto.

### 📈 Controle de Investimentos
- Cálculo de rentabilidade mensal e anual.  
- Visualização de carteira (ações, fundos, criptos, renda fixa).  
- Relatórios de evolução patrimonial e comparativos históricos.

### 📊 Relatórios e Dashboards
- Gráficos interativos de fluxo de caixa, categorias e metas.  
- Indicadores de saldo atual, ganhos/perdas e metas atingidas.  
- Geração de relatórios por período e exportação em CSV/PDF.

### 🎯 Metas e Orçamentos
- Criação de limites mensais de gasto e metas de economia.  
- Alertas automáticos por e-mail ao atingir o limite definido.

### ⚙️ Configurações e Segurança
- Login seguro com autenticação **JWT**.  
- Preferências de tema (claro/escuro).  
- Backup automático e criptografia de dados sensíveis.

---

## 💡 Por que isso importa

Muitos aplicativos financeiros são **complexos ou focados em bancos específicos**.  
O **Nexa** busca ser **acessível e independente**, permitindo que qualquer pessoa acompanhe sua vida financeira de forma **simples e organizada** — com **dados centralizados**, **visual limpo** e **análises úteis**.  

Em tempos de **aumento do custo de vida** e **maior busca por autonomia financeira**, o Nexa oferece **controle, clareza e inteligência** para o dia a dia.

---

## 🧠 Arquitetura e Stack Técnica

| Camada | Tecnologia |
|--------|-------------|
| **Frontend** | React + Tailwind CSS |
| **Backend** | Go (Fiber) |
| **Banco de Dados** | PostgreSQL via Supabase |
| **Autenticação** | JWT |
| **CI/CD** | GitHub Actions |
| **Infraestrutura** | Docker |
| **Serviços de E-mail** | SendGrid / Mailgun |

---

## 🧩 Repositórios e Organização

- **Backend:** [`nexa-backend`](#)
- **Frontend:** [`nexa-frontend`](#)

Gestão de tarefas via **GitHub Projects (Kanban)**, com **sprints quinzenais** e acompanhamento de progresso.  
Toda a **documentação e wireframes** serão centralizados no **repositório principal**.

---

## 🗓️ Roadmap & Cronograma

| Entrega | Escopo | Data Alvo |
|----------|---------|------------|
| **CRUD de usuários** | Criação, autenticação e segurança JWT | 15 de agosto de 2025 |
| **Módulo de lançamentos** | CRUD de receitas e despesas com filtros e categorias | 30 de setembro de 2025 |
| **Módulo de investimentos** | Registro e cálculo de rendimentos mensais e anuais | 31 de outubro de 2025 |
| **MVP completo** | Lançamentos + Investimentos + Dashboard + Metas em produção | 30 de novembro de 2025 |

---

> 📘 **Documento base:** rascunho inicial desenvolvido durante a aula, evoluído para formato de documentação oficial da organização **Nexa**.
