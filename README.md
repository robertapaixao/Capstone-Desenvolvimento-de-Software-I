# Sistema de Compra e Aluguel de Veículos

## Sobre o projeto

Este projeto está sendo desenvolvido como atividade da disciplina de **Desenvolvimento de Software I**. O objetivo é criar um sistema em Python para gerenciar as operações de compra, venda e aluguel de veículos.

O sistema busca facilitar o controle das informações dos clientes, vendedores e veículos, além de organizar as transações, calcular valores e comissões e registrar as operações realizadas.

## Funcionalidades

O sistema contará com as seguintes funcionalidades:

### Cadastro
- Cadastro de clientes.
- Cadastro de vendedores.
- Cadastro de veículos.
- Registro de modelo, placa, preço e disponibilidade dos veículos.

### Aluguel de veículos
- Registro do aluguel.
- Identificação do cliente e do vendedor.
- Seleção do veículo.
- Registro do preço e da quantidade de dias.
- Controle das datas e horários de retirada e devolução.
- Aplicação de cupons de desconto.
- Geração de identificador único para cada aluguel.

### Compra e venda de veículos
- Registro das operações de compra e venda.
- Identificação do cliente e do vendedor.
- Registro do modelo e da placa do veículo.
- Controle do preço e da data da operação.
- Aplicação de cupons de desconto.
- Geração de identificador único para cada compra.

### Comissão dos vendedores
O sistema realizará o cálculo automático da comissão do vendedor de acordo com a porcentagem estabelecida sobre o valor da operação.

**Fórmula:**

`Comissão = (Valor da operação × Percentual de comissão) / 100`

### Garantia e reembolso
- Registro de garantias contra danos.
- Controle de possíveis solicitações de reembolso.
- Registro das informações relacionadas às garantias.

### Notas fiscais e histórico
- Emissão de notas fiscais ou comprovantes.
- Consulta ao histórico de compras e aluguéis.

## Tecnologias utilizadas

- **Linguagem de programação:** Python
- **Gerenciamento do projeto:** JIRA
- **Controle de versão:** Git e GitHub
- **Metodologia de desenvolvimento:** Scrum

## Planejamento do projeto – Sprints

O desenvolvimento será dividido em quatro Sprints:

### Sprint 1 – Estrutura inicial e cadastros
- Criação da estrutura inicial do projeto.
- Desenvolvimento do menu principal.
- Cadastro de clientes.
- Cadastro de vendedores.
- Cadastro de veículos.

### Sprint 2 – Aluguel de veículos
- Registro dos aluguéis.
- Controle de datas e horários.
- Cálculo dos valores de aluguel.

### Sprint 3 – Compra, venda e comissões
- Registro de compras e vendas.
- Aplicação de cupons de desconto.
- Geração de identificadores únicos.
- Cálculo das comissões dos vendedores.

### Sprint 4 – Garantias e finalização
- Controle de garantias e reembolsos.
- Emissão de notas fiscais.
- Histórico de operações.
- Testes e correções do sistema.

## Equipe de desenvolvimento

Projeto desenvolvido por:

- Jenifer Gonçalves da Silva
- Roberta Flaviane Soares Paixão
- Patrick Ryan Oliveira

**Scrum Master da primeira semana:** Jenifer Gonçalves da Silva.

A função de Scrum Master será alternada semanalmente entre os integrantes da equipe.

## Organização do projeto

O Product Backlog reúne todas as funcionalidades planejadas para o sistema, enquanto os Sprints organizam as atividades que serão desenvolvidas em cada etapa.

O acompanhamento das tarefas será realizado pelo JIRA, e o código-fonte ficará disponível neste repositório do GitHub.

## Disciplina

**Desenvolvimento de Software I**

Projeto acadêmico desenvolvido como parte das atividades da disciplina.
