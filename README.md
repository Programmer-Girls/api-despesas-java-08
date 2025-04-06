# Controle de Gastos Pessoais - API RESTful 📌📈

**Arquitetura:** O Sistema de Controle de Gastos Pessoais será desenvolvido com uma arquitetura monolítica baseada no padrão RESTful e utilizando os princípios do Domain-Driven Design (DDD) para uma modelagem eficiente. 
A estrutura inicial do sistema permitirá evolução ágil, possibilitando uma futura transição para microsserviços, caso necessário. Além disso, serão seguidas boas práticas de desenvolvimento, como Clean Code, SOLID e Test-Driven Development (TDD), garantindo um código limpo, modular, testável e de fácil manutenção.
A API será responsável por gerenciar usuários, despesas, categorias, métodos de pagamento e geração de relatórios financeiros, garantindo segurança e integridade dos dados através de autenticação JWT e validações no backend.

<br>

**Objetivo:** O objetivo deste projeto é desenvolver um sistema de controle de gastos pessoais que permita aos usuários gerenciar suas finanças de forma eficiente. Inicialmente, a plataforma oferecerá funcionalidades essenciais, como o cadastro de usuários, registro de despesas, categorização de gastos, métodos de pagamento e geração de relatórios financeiros através de operações CRUD.
Além disso, o sistema possibilitará consultas personalizadas, permitindo que os usuários filtrem despesas por categoria, período e valor, além de obter um panorama detalhado de seus hábitos financeiros. A lógica de negócios garantirá a validação de dados, segurança na autenticação via JWT e armazenamento seguro de senhas.
A longo prazo, o sistema será aprimorado para incluir integrações com serviços externos, notificações automáticas sobre padrões de gastos e recursos avançados de análise financeira. O foco será garantir alta performance, segurança e escalabilidade, permitindo que a plataforma cresça conforme as necessidades dos usuários.

## Resumo Técnico

<br>

## Diagrama de Classes

 
![Diagramas de rede - Página 1](https://github.com/user-attachments/assets/0789d462-40c2-492b-8fcc-d463d0361d10)

<br>
<br>

## Banco de Dados

Detalhe a estrutura das tabelas no banco de dados (relacional ou não relacional). Explique as relações entre as entidades, como Usuário e Despesa.


<br>

## Como realizar a organização dentro do seu Fork 📂

**Branches de Funcionalidades:** Para cada tarefa ou funcionalidade específica, crie uma branch separada. Isso facilita o trabalho
colaborativo e mantém o código organizado, evitando sobrecarga na branch principal. Algumas convenções de nome para as branches:

- feature/()

**Pull Requests (PRs):** Ao finalizar uma tarefa, crie um Pull Request para mesclar as alterações da sua branch de funcionalidades
na branch principal (main) do repositório principal. Certifique-se de que o PR está associado à issue correspondente, para que todos possam acompanhar o progresso da tarefa.
