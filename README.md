# 🐾 Petfood — Abastecimento recorrente para pets

**Seu pet nunca mais vai ficar sem ração!**

A Petfood é uma plataforma de gerenciamento de abastecimento recorrente de ração e petiscos para cães e gatos, inicialmente voltada para tutores de Campo Grande/MS.

A proposta é simplificar a reposição de alimentos para animais de estimação por meio de solicitações de assinatura, entregas programadas e atendimento pelo WhatsApp.

## 🌐 Aplicação publicada

**[Acessar Petfood](https://pawpantry-customer-companion.lovable.app)**

---

# 1. 💡 A dor escolhida e a oportunidade de negócio

Tutores de cães e gatos precisam comprar ração e petiscos frequentemente. Esse processo pode gerar dificuldades no dia a dia, como:

- Esquecimento da reposição dos alimentos.
- Falta de tempo para ir até um pet shop.
- Compras emergenciais quando a ração acaba.
- Dificuldade para organizar o consumo de vários animais.
- Falta de praticidade na reposição recorrente.

A Petfood surgiu para resolver esse problema por meio de um serviço de abastecimento recorrente.

Em vez de esperar a ração acabar para realizar uma nova compra, o tutor pode organizar previamente a reposição dos produtos e receber suas entregas conforme a frequência desejada.

### Por que essa dor vale um negócio?

A alimentação dos animais é uma necessidade recorrente. Diferentemente de produtos comprados ocasionalmente, a ração possui uma frequência natural de reposição.

Isso cria uma oportunidade para um modelo de negócio baseado em recorrência, conveniência e relacionamento contínuo com os clientes.

**Solução proposta:** uma plataforma que permite ao tutor cadastrar seus pets, informar suas preferências alimentares e solicitar um plano de abastecimento personalizado.

O atendimento e a confirmação comercial acontecem pelo WhatsApp.

---

# 2. 📊 Tamanho de mercado e Business Model Canvas

## 2.1 Dimensionamento do mercado

**Mercado inicial: Campo Grande/MS**

Como referência para dimensionamento, foi utilizado o levantamento municipal de cães e gatos, que contabilizou aproximadamente 287.768 animais.

Esse número representa animais, e não quantidade de clientes ou residências.

### TAM — Total Addressable Market

Mercado total potencial de alimentação para cães e gatos.

Referência: população estimada de 287.768 cães e gatos em Campo Grande.

### SAM — Serviceable Available Market

Tutores de cães e gatos que compram ração e petiscos, possuem perfil de compra compatível com a plataforma e podem ser atendidos pela operação.

### SOM — Serviceable Obtainable Market

Meta inicial de validação: conquistar os primeiros 100 assinantes.

O objetivo é começar em Campo Grande, validar a demanda e avaliar a possibilidade de expansão.

*Observação: SAM e SOM são hipóteses estratégicas, não estatísticas oficiais. O número de animais utilizado no TAM não deve ser interpretado como quantidade de clientes potenciais individuais.*

## 2.2 Business Model Canvas

| Bloco | Descrição |
|---|---|
| **Segmentos de clientes** | Tutores de cães e gatos, famílias com múltiplos pets e consumidores que valorizam praticidade. |
| **Proposta de valor** | Abastecimento recorrente de ração e petiscos, com praticidade, personalização e entregas programadas. |
| **Canais** | Site, Instagram, WhatsApp e divulgação local. |
| **Relacionamento com clientes** | Atendimento humanizado, acompanhamento pelo WhatsApp e gerenciamento das solicitações. |
| **Fontes de receita** | Assinaturas de ração, vendas adicionais de petiscos e produtos complementares. |
| **Recursos principais** | Plataforma web, backend em nuvem, banco de dados e fornecedores parceiros. |
| **Atividades principais** | Gestão de solicitações, clientes, assinaturas e entregas. |
| **Parceiros principais** | Distribuidores de ração, pet shops e entregadores. |
| **Estrutura de custos** | Aquisição de produtos, logística, tecnologia, divulgação e taxas operacionais. |

---

# 3. 🎯 Tese que o MVP testa e o que ficou manual

## 3.1 Hipótese principal

A hipótese que a Petfood pretende validar é:

**Tutores de cães e gatos em Campo Grande têm interesse em contratar um serviço de abastecimento recorrente de ração e petiscos, valorizando a praticidade de receber os produtos em casa e gerenciar suas reposições pelo WhatsApp.**

O MVP busca descobrir se existe interesse real nesse modelo de negócio antes de investir em automações e integrações mais complexas.

### O que queremos descobrir?

- Existe interesse real nesse modelo de assinatura?
- Os tutores estão dispostos a preencher um formulário para solicitar o serviço?
- Quais produtos são mais procurados?
- Qual frequência de reposição é mais desejada?
- Os clientes demonstram interesse em manter uma relação recorrente com a empresa?

## 3.2 Funcionalidades desenvolvidas no MVP

- Landing page de apresentação da Petfood.
- Formulário de solicitação de assinatura.
- Cadastro de tutores e pets.
- Registro das preferências de alimentação.
- Notificação de novos leads por e-mail.
- Painel administrativo.
- Gerenciamento de solicitações.
- Cadastro manual de clientes.
- Gerenciamento de assinaturas.
- Controle básico de entregas.
- Contato com clientes pelo WhatsApp.

## 3.3 O que ficou manual de propósito?

Para reduzir a complexidade inicial e validar primeiro a demanda comercial, algumas operações foram mantidas manuais.

| Processo | Funcionamento no MVP |
|---|---|
| Recebimento de solicitações | Automático pelo formulário. |
| Armazenamento de dados | Automático no backend. |
| Notificação de novos leads | Automática, após configuração do serviço de e-mail. |
| Negociação comercial | Manual pelo WhatsApp. |
| Definição de preços | Manual durante a negociação. |
| Confirmação da assinatura | Manual pelo administrador. |
| Pagamento | Manual, por meio de link enviado ao cliente. |
| Compra dos produtos | Manual com fornecedores. |
| Organização das entregas | Gerenciada pelo painel administrativo. |

Essa decisão permite testar a proposta de valor sem precisar desenvolver inicialmente um sistema completo de pagamentos, estoque e logística.

**O objetivo é validar a demanda antes de automatizar toda a operação.**

---

# 4. 🤖 Mega prompt e correções solicitadas

O desenvolvimento da Petfood utilizou o ChatGPT como parceiro de planejamento e o Lovable como ferramenta de construção da aplicação.

## 4.1 Utilização do ChatGPT

O ChatGPT foi utilizado para:

- Estruturar a ideia de negócio.
- Identificar a dor e a oportunidade de mercado.
- Dimensionar o mercado potencial.
- Desenvolver o Business Model Canvas.
- Definir a hipótese principal do MVP.
- Planejar as funcionalidades.
- Elaborar o mega prompt para o Lovable.
- Analisar problemas e planejar correções.

## 4.2 Mega prompt utilizado

O mega prompt foi elaborado em Markdown, descrevendo:

- Contexto e objetivo do negócio.
- Identidade visual e paleta de cores.
- Experiência do cliente.
- Formulário de solicitação de assinatura.
- Painel administrativo.
- Gerenciamento de leads, clientes, assinaturas e entregas.
- Estrutura do banco de dados.
- Requisitos de segurança.
- Critérios de aceitação do MVP.

### Prompt inicial

[INSERIR AQUI O MEGA PROMPT UTILIZADO NO LOVABLE]

## 4.3 Correções solicitadas durante o desenvolvimento

Nesta seção serão documentados os problemas encontrados durante os testes e os respectivos prompts enviados ao Lovable para corrigi-los.

| Problema identificado | Correção solicitada | Resultado |
|---|---|---|
| [Adicionar problema encontrado] | [Adicionar prompt de correção] | [Adicionar resultado do teste] |
| [Adicionar problema encontrado] | [Adicionar prompt de correção] | [Adicionar resultado do teste] |
| [Adicionar problema encontrado] | [Adicionar prompt de correção] | [Adicionar resultado do teste] |

*Os registros serão preenchidos conforme os testes reais da aplicação forem realizados.*

---

# 5. 🖥️ Screenshots e evidências da aplicação

As imagens abaixo demonstram a interface e as funcionalidades desenvolvidas no MVP.

## 5.1 Landing page

<img width="1920" height="1040" alt="image" src="https://github.com/user-attachments/assets/acfcab08-b13f-4c27-9781-0ae475e0faa5" />


![Landing page Petfood](screenshots/landing-page.png)

## 5.2 Formulário de solicitação de assinatura

<img width="1920" height="1040" alt="image" src="https://github.com/user-attachments/assets/e4fa6941-4516-43f3-aa61-6c9251aeec61" />

![Formulário Petfood](screenshots/formulario.png)

## 5.3 Confirmação de solicitação

<img width="1920" height="1040" alt="image" src="https://github.com/user-attachments/assets/c400f53b-3b02-439f-961d-fe7099334ce0" />

![Confirmação Petfood](screenshots/confirmacao.png)

## 5.4 Dashboard administrativo

<img width="1920" height="1040" alt="image" src="https://github.com/user-attachments/assets/6579634a-27fa-4e9b-ac4d-64cb1b2745aa" />

![Dashboard Petfood](screenshots/dashboard.png)

## 5.5 Gerenciamento de leads e clientes

<img width="1919" height="1031" alt="image" src="https://github.com/user-attachments/assets/ba7c20b4-54a7-4c0e-ae5c-555d180f9ee6" />


![Gerenciamento Petfood](screenshots/leads.png)

## 5.6 Gerenciamento de assinaturas e entregas

<img width="1920" height="1040" alt="image" src="https://github.com/user-attachments/assets/774d2e58-c502-4070-bfaf-7ca68b679bfc" />
<img width="1918" height="1040" alt="image" src="https://github.com/user-attachments/assets/cef6919f-0fda-497d-a953-274495ef9166" />


![Assinaturas Petfood](screenshots/assinaturas.png)

---

# 6. 🛠️ Tecnologias utilizadas

- **Lovable:** desenvolvimento da aplicação.
- **Lovable Cloud:** infraestrutura e backend.
- **PostgreSQL:** banco de dados.
- **Lovable Cloud Auth:** autenticação administrativa.
- **Edge Functions:** processamento de operações no backend.
- **Resend:** serviço de envio de notificações por e-mail, quando configurado.
- **GitHub:** versionamento e disponibilização do código-fonte.

---

# 7. 🚀 Possibilidades de evolução

Após validar a hipótese inicial, a Petfood poderá evoluir com:

- Pagamentos digitais.
- Cobrança recorrente via cartão e Pix.
- Chatbot integrado ao WhatsApp utilizando n8n.
- Notificações automáticas de reposição.
- Integração com distribuidores.
- Gestão de estoque.
- Roteirização de entregas.
- Expansão para outras cidades.

---

# 8. Considerações finais

A Petfood representa a transformação de uma oportunidade de negócio em um produto digital funcional.

O MVP foi planejado para testar uma hipótese comercial específica, priorizando as funcionalidades essenciais e mantendo manualmente os processos que não precisam ser automatizados nesta primeira etapa.

A proposta é validar a demanda, aprender com os primeiros usuários e evoluir o produto com base em evidências reais.

**Projeto desenvolvido como parte do desafio da DIO.** 🐾
