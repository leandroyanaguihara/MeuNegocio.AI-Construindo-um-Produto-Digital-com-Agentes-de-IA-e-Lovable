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

```text

### Prompt inicial

# PETFOOD — Construção do MVP Full Stack

## 1. CONTEXTO DO PROJETO

Desenvolva uma aplicação web responsiva chamada **Petfood**, uma plataforma de gerenciamento de abastecimento recorrente de ração e petiscos para cães e gatos.

O negócio começa em Campo Grande/MS e tem como proposta central gerenciar o abastecimento recorrente dos animais de estimação, oferecendo conveniência aos tutores por meio de assinaturas personalizadas e entregas programadas.

O posicionamento da marca não é simplesmente uma loja virtual de ração. É um serviço que ajuda os tutores a nunca deixarem a alimentação de seus pets acabar.

O projeto deve ser construído como um MVP funcional, com frontend, backend, banco de dados e infraestrutura em nuvem.

## 2. TECNOLOGIA E INFRAESTRUTURA

Utilize prioritariamente os recursos nativos do Lovable Cloud.

Quero aproveitar a infraestrutura disponível na plataforma, evitando dependências externas desnecessárias.

Utilize:

- Lovable Cloud como infraestrutura principal.
- Banco de dados PostgreSQL.
- Autenticação segura para administradores.
- Backend para processamento e gerenciamento dos dados.
- Edge Functions quando necessárias.
- Sistema de armazenamento em nuvem, caso existam imagens de produtos ou arquivos.
- Integração de envio de e-mails para notificações.
- Políticas de segurança e controle de acesso ao banco de dados.
- Row Level Security (RLS).
- Variáveis e secrets para credenciais e configurações sensíveis.

Não simule operações que deveriam acontecer no backend.

Não deixe dados importantes armazenados somente no navegador.

Não utilize credenciais fictícias para integrações.

Caso alguma configuração dependa de credenciais ou ativação externa, prepare a estrutura e informe exatamente o que precisa ser configurado.

## 3. IDENTIDADE VISUAL

Nome da solução: **Petfood**

Criar uma identidade visual moderna, amigável, profissional e acolhedora.

Paleta de cores:

- Salmão: #F28C85
- Azul: #77A9D6
- Roxo: #9274C8
- Verde-água: #83CFC2
- Branco: #FFFFFF
- Cinza claro: #F5F6FA
- Texto principal: #303344

Utilizar as quatro cores principais de maneira equilibrada.

O salmão deve transmitir acolhimento e proximidade.

O azul deve transmitir confiança.

O roxo deve representar tecnologia e personalidade.

O verde-água deve transmitir cuidado, saúde e tranquilidade.

Design com:
- Interface clean.
- Cantos arredondados.
- Cards com sombras suaves.
- Ícones modernos.
- Tipografia legível.
- Boa hierarquia visual.
- Microinterações discretas.
- Layout responsivo para desktop e celular.

Criar uma identidade própria para a Petfood, evitando aparência de template genérico.

## 4. ÁREA PÚBLICA — EXPERIÊNCIA DO CLIENTE

### Página inicial

Criar uma landing page com:

Header:
- Logo Petfood.
- Início.
- Como funciona.
- Nossos produtos.
- Assinatura.
- Contato.
- Botão "Quero assinar".

No canto superior direito, adicionar um ícone de engrenagem (⚙) para acesso à área administrativa.

Esse ícone deve direcionar para a rota /admin/login.

Não exibir informações administrativas na área pública.

### Hero section

Título principal:

"Seu pet nunca mais vai ficar sem ração!"

Subtítulo:

"Receba ração e petiscos na frequência ideal para seu pet. Mais praticidade para você, mais cuidado para quem faz parte da sua família."

Botão principal:
"Quero conhecer a Petfood"

Botão secundário:
"Como funciona?"

Utilizar ilustrações ou fotografias de cães e gatos em uma composição visual agradável.

### Seção: Como funciona

Apresentar quatro etapas:

1. Cadastre seu pet.
2. Escolha a alimentação e os produtos.
3. Defina a frequência de abastecimento.
4. Receba tudo em casa.

Deixar claro que, nesta primeira versão, a solicitação da assinatura é feita pelo site e a confirmação acontece posteriormente pelo WhatsApp.

### Seção: Benefícios

- Nunca ficar sem ração.
- Entregas programadas.
- Planos personalizados.
- Mais praticidade no dia a dia.
- Atendimento humanizado.
- Facilidade para gerenciar o abastecimento.

### Seção: Produtos

Apresentar categorias:

- Ração para cães.
- Ração para gatos.
- Petiscos para cães.
- Petiscos para gatos.
- Produtos complementares.

Inicialmente, utilizar produtos demonstrativos claramente identificados como exemplos, sem inventar preços, descontos ou disponibilidade real.

Preparar estrutura para cadastrar produtos reais pelo painel administrativo.

## 5. FORMULÁRIO DE SOLICITAÇÃO DE ASSINATURA

Criar uma página /assinar com um formulário dividido em etapas.

### Etapa 1 — Dados do tutor

Campos:
- Nome completo.
- E-mail.
- WhatsApp.
- CEP.
- Endereço.
- Número.
- Complemento.
- Bairro.
- Cidade.

A cidade deve vir preenchida inicialmente como Campo Grande e o estado como MS, permitindo alteração se necessário.

### Etapa 2 — Dados do pet

Permitir cadastrar um ou mais animais.

Campos:
- Nome do pet.
- Espécie: cachorro ou gato.
- Raça (opcional).
- Idade.
- Peso aproximado.
- Porte.
- Observações.

### Etapa 3 — Alimentação

Campos:
- Tipo de produto desejado.
- Marca de preferência.
- Produto ou ração desejada.
- Quantidade ou tamanho da embalagem.
- Frequência de reposição: 15, 30 ou 45 dias.
- Petiscos adicionais.
- Observações.

Não inventar catálogo, marcas, preços ou disponibilidade.

### Etapa 4 — Confirmação

Exibir resumo da solicitação:

- Dados do tutor.
- Endereço.
- Animais cadastrados.
- Produtos desejados.
- Frequência de entrega.

Botão:

"Enviar solicitação de assinatura"

IMPORTANTE:

Não implementar cobrança digital nesta primeira versão.

Não integrar checkout, cartão de crédito ou pagamento recorrente neste MVP.

Ao enviar, salvar os dados no banco de dados e registrar uma nova solicitação com status "Novo lead".

Exibir mensagem de sucesso:

"Recebemos sua solicitação! Nossa equipe entrará em contato pelo WhatsApp para confirmar os produtos, valores e detalhes da sua assinatura."

## 6. NOTIFICAÇÃO DE NOVO CLIENTE

Quando alguém enviar o formulário:

1. Registrar a solicitação no banco de dados.
2. Registrar os dados do tutor e dos pets.
3. Criar uma solicitação com status "Novo lead".
4. Enviar uma notificação por e-mail ao administrador.
5. Registrar a data e hora da solicitação.

O e-mail deve conter:

Assunto: Nova solicitação de assinatura — Petfood

Corpo:
- Nome do tutor.
- WhatsApp.
- E-mail.
- Cidade e bairro.
- Nome e espécie dos pets.
- Produtos desejados.
- Frequência pretendida.
- Link para abrir o cadastro no painel administrativo.

O endereço de e-mail do administrador deve ser configurável.

Não inventar endereço de e-mail nem credenciais SMTP.

Caso seja necessária uma configuração de provedor de e-mail, preparar a integração e informar quais secrets e configurações precisam ser adicionados.

A falha no envio do e-mail não pode apagar ou impedir o registro da solicitação no banco de dados.

## 7. PAINEL ADMINISTRATIVO

Criar uma área administrativa em /admin.

O acesso deve ser protegido por autenticação.

Apenas usuários autorizados como administradores podem acessar essa área.

O ícone de engrenagem no header público deve abrir /admin/login.

Criar uma interface administrativa moderna, com menu lateral e dashboard principal.

### Menu lateral

- Dashboard.
- Clientes.
- Solicitações.
- Assinaturas.
- Pets.
- Produtos.
- Entregas.
- Configurações.
- Sair.

### Dashboard

Exibir cards com indicadores:

- Total de clientes.
- Clientes ativos.
- Novas solicitações.
- Assinaturas ativas.
- Entregas previstas.
- Solicitações aguardando contato.

Criar gráficos de:
- Evolução de clientes.
- Novas solicitações por período.
- Distribuição de assinaturas por frequência.
- Produtos mais solicitados.

Todos os indicadores devem ser calculados a partir dos dados reais do banco.

Quando não houver dados, mostrar estados vazios amigáveis em vez de inventar números.

### Clientes

Criar tabela com:

- Nome.
- WhatsApp.
- E-mail.
- Quantidade de pets.
- Status.
- Data de cadastro.
- Ações.

Permitir:

- Cadastrar clientes manualmente.
- Editar clientes.
- Consultar detalhes.
- Ativar clientes.
- Pausar clientes.
- Inativar clientes.
- Pesquisar por nome, telefone ou e-mail.

### Solicitações

Criar uma área para administrar todos os formulários recebidos.

Status possíveis:

- Novo lead.
- Aguardando contato.
- Em negociação.
- Aguardando confirmação.
- Aprovado.
- Recusado.

Permitir abrir cada solicitação e visualizar todos os dados enviados.

Adicionar botão:

"Conversar pelo WhatsApp"

O botão deve abrir uma conversa com o telefone do cliente, utilizando um link wa.me e uma mensagem inicial pré-preenchida.

Exemplo:

"Olá! Aqui é da Petfood. Recebemos sua solicitação de assinatura para seu pet e gostaríamos de conversar sobre os detalhes."

Adicionar também botão para converter uma solicitação aprovada em cliente.

### Assinaturas

Criar gerenciamento manual de assinaturas.

Campos:
- Cliente.
- Pets vinculados.
- Produtos.
- Quantidade.
- Frequência.
- Data de início.
- Próxima entrega.
- Valor acordado.
- Status.

Status:
- Ativa.
- Pausada.
- Cancelada.
- Pendente de confirmação.

O administrador poderá criar, editar, pausar e cancelar assinaturas.

A ativação deve ser feita manualmente pelo administrador após a negociação pelo WhatsApp.

Não criar cobranças automáticas nesta versão.

### Produtos

Criar cadastro e gerenciamento de produtos.

Campos:
- Nome.
- Categoria.
- Espécie indicada.
- Marca.
- Descrição.
- Peso ou volume.
- Imagem.
- Preço.
- Disponibilidade.

Permitir cadastrar, editar e desativar produtos.

### Entregas

Criar controle básico de entregas.

Campos:
- Cliente.
- Endereço.
- Produtos.
- Data prevista.
- Status da entrega.

Status:
- Programada.
- Em preparação.
- Saiu para entrega.
- Entregue.
- Cancelada.

Criar filtros por data e status.

## 8. CADASTRO MANUAL DE CLIENTES ATIVOS

Este recurso é fundamental para o MVP.

Como ainda não haverá assinatura digital nem cobrança online, o administrador precisa conseguir cadastrar diretamente um cliente que já negociou e confirmou pelo WhatsApp.

Criar botão destacado:

"+ Novo cliente"

O cadastro deve permitir preencher:

- Dados pessoais.
- Endereço.
- Dados dos pets.
- Produtos contratados.
- Frequência.
- Valor acordado.
- Data de início.
- Próxima entrega.

Ao salvar, permitir criar a assinatura vinculada ao cliente e definir seu status como "Ativa".

O dashboard deve atualizar automaticamente seus indicadores.

## 9. BANCO DE DADOS

Criar estrutura relacional no PostgreSQL.

Tabelas sugeridas:

- profiles: usuários administrativos e suas permissões.
- customers: dados dos tutores.
- pets: animais vinculados aos clientes.
- products: catálogo de produtos.
- subscription_requests: solicitações públicas.
- subscriptions: assinaturas.
- subscription_items: produtos de cada assinatura.
- deliveries: entregas.
- notifications: histórico de notificações.
- settings: configurações gerais.

Criar relacionamentos e chaves estrangeiras adequados.

Utilizar UUID como identificadores.

Criar timestamps de criação e atualização.

Criar índices para pesquisas frequentes.

Implementar RLS em todas as tabelas que contenham dados privados.

Visitantes públicos só podem enviar solicitações pelo formulário, sem permissão para consultar clientes, assinaturas ou informações administrativas.

Administradores autenticados e autorizados podem gerenciar os registros.

Não permitir que qualquer pessoa consiga se tornar administradora por meio do formulário público.

## 10. SEGURANÇA E REGRAS DE NEGÓCIO

- Não expor credenciais no frontend.
- Não permitir acesso público ao painel.
- Validar os campos do formulário no frontend e backend.
- Proteger dados pessoais dos clientes.
- Evitar solicitações duplicadas acidentais.
- Criar logs de operações administrativas importantes.
- Implementar tratamento de erros.
- Não excluir solicitações ou clientes automaticamente.
- Não utilizar dados fictícios como se fossem reais.
- Não implementar pagamentos sem solicitação explícita.
- Não ativar assinaturas automaticamente a partir do formulário público.

## 11. EXPERIÊNCIA E RESPONSIVIDADE

A aplicação deve funcionar perfeitamente em:

- Desktop.
- Notebook.
- Tablet.
- Smartphone.

No celular, o formulário deve ser fácil de preencher.

O painel administrativo deve possuir menu adaptável.

Criar estados de carregamento, mensagens de sucesso, mensagens de erro e telas vazias.

## 12. RESULTADO ESPERADO

Entregar um MVP funcional do Petfood com:

1. Landing page pública.
2. Formulário completo de solicitação de assinatura.
3. Cadastro de um ou mais pets.
4. Persistência dos dados no Lovable Cloud.
5. Notificação de novos leads por e-mail.
6. Login administrativo seguro.
7. Dashboard com dados reais.
8. Cadastro manual de clientes ativos.
9. Gerenciamento de solicitações.
10. Gerenciamento de assinaturas.
11. Cadastro de produtos.
12. Controle básico de entregas.
13. Integração de contato pelo WhatsApp.

## 13. ORIENTAÇÃO DE DESENVOLVIMENTO

Desenvolva o projeto por etapas, preservando a consistência da arquitetura.

Primeiro, configure o Lovable Cloud, o banco de dados e a autenticação.

Depois, construa a interface pública e o formulário.

Em seguida, implemente o painel administrativo e seus módulos.

Por último, configure as notificações por e-mail e valide os fluxos completos.

Não entregue somente telas estáticas ou protótipos visuais.

Quero funcionalidades reais, persistência real no banco e permissões funcionando.

Antes de considerar concluído, teste:

- Envio de solicitação pública.
- Persistência dos dados.
- Notificação por e-mail.
- Login administrativo.
- Cadastro manual de cliente.
- Ativação de assinatura.
- Atualização dos indicadores do dashboard.
- Abertura de conversa no WhatsApp.

O objetivo é entregar uma primeira versão utilizável comercialmente em Campo Grande/MS, preparada para evoluir futuramente para pagamentos recorrentes, automações e chatbot integrado ao WhatsApp.

```

---

# 5. 🖥️ Screenshots e evidências da aplicação

As imagens abaixo demonstram a interface e as funcionalidades desenvolvidas no MVP.

## 5.1 Landing page

<img width="1920" height="1040" alt="image" src="https://github.com/user-attachments/assets/acfcab08-b13f-4c27-9781-0ae475e0faa5" />

## 5.2 Formulário de solicitação de assinatura

<img width="1920" height="1040" alt="image" src="https://github.com/user-attachments/assets/e4fa6941-4516-43f3-aa61-6c9251aeec61" />

## 5.3 Confirmação de solicitação

<img width="1920" height="1040" alt="image" src="https://github.com/user-attachments/assets/c400f53b-3b02-439f-961d-fe7099334ce0" />

## 5.4 Dashboard administrativo

<img width="1920" height="1040" alt="image" src="https://github.com/user-attachments/assets/6579634a-27fa-4e9b-ac4d-64cb1b2745aa" />

## 5.5 Gerenciamento de leads e clientes

<img width="1919" height="1031" alt="image" src="https://github.com/user-attachments/assets/ba7c20b4-54a7-4c0e-ae5c-555d180f9ee6" />

## 5.6 Gerenciamento de assinaturas e entregas

<img width="1920" height="1040" alt="image" src="https://github.com/user-attachments/assets/774d2e58-c502-4070-bfaf-7ca68b679bfc" />
<img width="1918" height="1040" alt="image" src="https://github.com/user-attachments/assets/cef6919f-0fda-497d-a953-274495ef9166" />

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
