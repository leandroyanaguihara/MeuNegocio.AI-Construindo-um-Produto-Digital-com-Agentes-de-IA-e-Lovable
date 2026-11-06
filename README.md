# 🐾 Petfood — Abastecimento recorrente para pets

**Seu pet nunca mais vai ficar sem ração!**

A Petfood é uma plataforma de gerenciamento de abastecimento recorrente de ração e petiscos para cães e gatos, desenvolvida inicialmente para atender tutores de Campo Grande/MS.

O projeto nasceu da proposta de simplificar a reposição de alimentos para animais de estimação por meio de solicitações de assinatura, entregas programadas e atendimento pelo WhatsApp.

## 🌐 Aplicação

- **Aplicação publicada:** [INSERIR LINK DO LOVABLE]
- **Repositório:** [INSERIR LINK DO GITHUB]

---

## 1. 💡 A dor escolhida

Tutores de cães e gatos precisam comprar ração e petiscos frequentemente. Esse processo pode gerar alguns problemas:

- Esquecimento da reposição dos alimentos.
- Falta de tempo para ir até um pet shop.
- Compras emergenciais quando a ração acaba.
- Dificuldade para organizar o consumo de vários animais.
- Falta de praticidade na reposição recorrente.

A Petfood surgiu para resolver esse problema por meio de um serviço de abastecimento recorrente.

Em vez de esperar a ração acabar para realizar uma nova compra, o tutor pode organizar previamente a reposição dos produtos.

### Por que essa dor vale um negócio?

A alimentação dos animais é uma necessidade recorrente. Diferentemente de produtos comprados ocasionalmente, a ração possui uma frequência natural de reposição.

Isso cria uma oportunidade para um modelo de negócio baseado em recorrência, conveniência e relacionamento contínuo com os clientes.

---

## 2. 📊 Tamanho de mercado

### Mercado inicial: Campo Grande/MS

O levantamento municipal de cães e gatos utilizado como referência contabilizou aproximadamente 287.768 animais.

Esse número representa animais, não quantidade de clientes ou residências.

### TAM — Total Addressable Market

Mercado total potencial de alimentação para cães e gatos.

Referência: população estimada de cães e gatos de Campo Grande.

### SAM — Serviceable Available Market

Tutores de cães e gatos que compram ração e petiscos, possuem perfil de compra compatível com a plataforma e podem ser atendidos pela operação.

### SOM — Serviceable Obtainable Market

Meta inicial de validação: conquistar os primeiros 100 assinantes.

O objetivo é começar em Campo Grande, validar a demanda e avaliar a possibilidade de expansão.

*Observação: SAM e SOM são hipóteses estratégicas, não estatísticas oficiais. Os números e fontes utilizados no dimensionamento devem ser documentados em conjunto com suas respectivas referências.*

---

## 3. 🧩 Business Model Canvas

| Bloco | Descrição |
|---|---|
| Segmentos de clientes | Tutores de cães e gatos. |
| Proposta de valor | Abastecimento recorrente de ração e petiscos, com praticidade e entregas programadas. |
| Canais | Site, Instagram e WhatsApp. |
| Relacionamento | Atendimento humanizado e acompanhamento pelo WhatsApp. |
| Fontes de receita | Assinaturas e vendas complementares de produtos. |
| Recursos principais | Plataforma web, backend em nuvem e fornecedores parceiros. |
| Atividades principais | Gestão de solicitações, clientes, assinaturas e entregas. |
| Parceiros principais | Distribuidores, pet shops e entregadores. |
| Estrutura de custos | Produtos, logística, tecnologia, divulgação e taxas operacionais. |

---

## 4. 🎯 Tese que o MVP pretende validar

A hipótese principal da Petfood é:

**Tutores de cães e gatos em Campo Grande têm interesse em contratar um serviço de abastecimento recorrente de ração e petiscos, valorizando a praticidade de receber os produtos em casa e gerenciar suas reposições pelo WhatsApp.**

### O que queremos descobrir?

- Existe interesse real nesse modelo de assinatura?
- Os tutores estão dispostos a preencher um formulário para solicitar o serviço?
- Quais produtos são mais procurados?
- Qual frequência de reposição é mais desejada?
- Os clientes demonstram interesse em manter uma relação recorrente com a empresa?

### O que o MVP oferece?

- Landing page de apresentação.
- Formulário personalizado de solicitação.
- Cadastro de tutores e pets.
- Notificação de novos leads.
- Painel administrativo.
- Gerenciamento de clientes.
- Gerenciamento de assinaturas.
- Controle básico de entregas.
- Contato pelo WhatsApp.

### O que ficou manual de propósito?

Para reduzir a complexidade inicial e validar primeiro a demanda comercial, algumas operações foram mantidas manuais:

- Negociação com o cliente.
- Definição dos preços.
- Confirmação da assinatura.
- Envio do link de pagamento.
- Compra dos produtos.
- Organização das entregas.

O MVP não possui checkout ou cobrança recorrente integrada.

A decisão permite testar a proposta de valor antes de investir em automações e integrações mais complexas.

---

## 5. 🤖 Desenvolvimento com Inteligência Artificial

O desenvolvimento foi planejado utilizando o ChatGPT como parceiro de planejamento e o Lovable como ferramenta de construção do produto.

### Papel do ChatGPT

- Estruturação da ideia de negócio.
- Pesquisa e dimensionamento do mercado.
- Desenvolvimento do Business Model Canvas.
- Definição da hipótese do MVP.
- Planejamento das funcionalidades.
- Elaboração do mega prompt.
- Análise dos problemas encontrados durante os testes.
- Elaboração dos prompts de correção.

### Papel do Lovable

- Construção da interface.
- Desenvolvimento das funcionalidades.
- Configuração do backend.
- Estruturação do banco de dados.
- Implementação da autenticação.
- Integração com serviços externos.

### Mega prompt utilizado

O prompt completo utilizado para construir o MVP está disponível em:

[`docs/mega-prompt.md`](docs/mega-prompt.md)

### Correções realizadas

Os problemas identificados durante os testes e os respectivos prompts utilizados para corrigi-los estão documentados em:

[`docs/correcoes.md`](docs/correcoes.md)

---

## 6. 🛠️ Tecnologias utilizadas

- Lovable.
- Lovable Cloud.
- PostgreSQL.
- Autenticação do Lovable Cloud.
- Edge Functions.
- Resend para notificações por e-mail.
- GitHub para versionamento.

---

## 7. 🖥️ Evidências do projeto

### Landing page

![Landing page da Petfood](screenshots/landing-page.png)

### Formulário de solicitação

![Formulário da Petfood](screenshots/formulario.png)

### Dashboard administrativo

![Dashboard da Petfood](screenshots/dashboard.png)

### Gerenciamento de leads

![Gerenciamento de leads](screenshots/leads.png)

### Gerenciamento de assinaturas

![Gerenciamento de assinaturas](screenshots/assinaturas.png)

---

## 8. 🚀 Próximas evoluções

Após a validação da hipótese inicial, a Petfood poderá evoluir com:

- Pagamentos digitais.
- Assinaturas com cobrança recorrente.
- Integração com chatbot de WhatsApp utilizando n8n.
- Notificações automáticas de reposição.
- Integração com fornecedores.
- Gestão de estoque.
- Roteirização de entregas.
- Expansão para outras cidades.

---

## 9. 📌 Considerações finais

A Petfood representa a transformação de uma oportunidade de negócio em um produto digital funcional.

O MVP foi planejado para testar uma hipótese comercial específica, priorizando as funcionalidades essenciais e mantendo manualmente os processos que não precisam ser automatizados neste primeiro momento.

O objetivo é validar a demanda, aprender com os primeiros usuários e evoluir o produto com base em evidências reais.

**Projeto desenvolvido como parte do desafio da DIO.**
