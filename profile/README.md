# Mavon

<p align="center">
  <img src="./assets/mavonLogo.png.png" alt="Logo Mavon" width="200px">
</p>

**Plataforma de apoio para pequenos e médios negócios**

Mavon é uma plataforma SaaS pensada para facilitar a operação de pequenos e médios negócios (consultórios, salões, estúdios, clínicas). Através de formulários de agendamento adaptados para cada tipo de parceiro e de um painel administrativo rico em dados, queremos automatizar rotinas, reduzir custos operacionais e melhorar a experiência entre negócio e cliente.

---

## Visão rápida

* **Público-alvo:** pequenos e médios negócios (ex.: dentistas, médicos, barbeiros, podólogos).
* **Proposta de valor:** agendamento automático via formulário personalizado, painel com métricas operacionais e ferramentas de comunicação (envio de e-mail para feedback e notificações).
* **Estado:** ideia validada. Ainda sem implementação — objetivo: MVP até novembro de 2025.

---

## O que entregamos (principais funcionalidades)

* **Formulário de agendamento adaptativo** por tipo de parceiro (campos customizáveis, duração do serviço, capacidade por profissional, validações).
* **Painel de agendamentos**: visão, criação, edição, cancelamento, atribuição de profissionais, histórico de atendimentos e informações do cliente.
* **Dashboard do proprietário**: métricas e insights (horários de pico, horários vazios, clientes frequentes, taxa de ocupação, relatórios por período).
* **Sistema de e-mail pós-serviço**: envio automático de pedido de avaliação/feedback após confirmação do atendimento.
* **Autenticação básica** para proprietários e staff.

---

## Por que isso importa

Muitos sistemas completos atendem grandes empresas; entretanto, pequenas e médias empresas têm dificuldade em acessar soluções acessíveis e com foco prático. Mavon busca preencher essa lacuna, entregando automação e inteligência simples que gerem economia e mais eficiência operacional — especialmente relevante no contexto de abertura e manutenção de negócios no Brasil.

---

## Interface — Prévia visual

<p align="center">
  <img src="./assets/mavonexample.png.png" alt="Exemplo da interface do Mavon" width="700px">
</p>

---

## Time — donos e papéis

> Todos são proprietários do projeto e atuam como desenvolvedores fullstack. Abaixo, uma tabela visual com papéis principais.

| Nome                                   | Papel principal                                                                 | Responsabilidades chave                                                                                              |
| -------------------------------------- | ------------------------------------------------------------------------------- | -------------------------------------------------------------------------------------------------------------------- |
| **Pedro Henrique Santana Di Oliveira** | Product Lead / Client Liaison | Definição de rumo do produto, contato com clientes/partners, priorização do roadmap, também desenvolvedor fullstack. |
| **Bruno Cesar**                        | Líder Técnico (Tech Lead)                                                   | Arquitetura, decisões técnicas, revisão de código, padrões e qualidade, também desenvolvedor fullstack.              |
| **Marcos De Lima Prado**               | Gerente de Banco de Dados (DB Manager)                                      | Modelagem, migrations, performance e backups do PostgreSQL, também desenvolvedor fullstack.                          |

**Contribuições externas:** no momento não há política pública de contribuição — alterações via equipe.

---

## Onde o projeto será desenvolvido e acompanhado

* Repositórios GitHub: `mavon-backend` e `mavon-frontend` (cada um com README próprio).
* Gestão: GitHub Projects (Kanban) para backlog e sprints.
* Ferramentas de referência:

  * **Frontend:** React + Tailwind CSS
  * **Backend:** Spring Boot (Java)
  * **Banco:** PostgreSQL
  * **CI/CD sugerido:** GitHub Actions
  * **E-mail:** provedor SMTP (SendGrid / Mailgun / similar)

---

## Roadmap & Cronograma (metas principais)

Trabalharemos em sprints quinzenais, com reuniões de revisão e reajuste de prazos a cada 2 semanas.

| Entrega                      | Escopo                                                                                                  |                  Data alvo |
| ---------------------------- | ------------------------------------------------------------------------------------------------------- | -------------------------: |
| Formulário adaptativo        | Formulário funcional para tipos de parceiro com validações e integração mínima com backend              |   **15 de agosto de 2025** |
| Dashboard inicial            | Métricas básicas (horários de pico/vagos, clientes frequentes) e visualização por período               | **30 de setembro de 2025** |
| Sistema de e-mail (feedback) | Integração SMTP, templates básicos e disparo pós-serviço                                                |  **31 de outubro de 2025** |
| MVP completo                 | Formulário + Dashboard + Painel de agendamentos + sistema de e-mail em produção com **1 cliente** ativo | **30 de novembro de 2025** |

**Critério de aceitação do MVP:** sistema operacional com pelo menos um cliente em uso real ou ambiente de testes com dados reais; as features principais funcionando conforme descrito.
