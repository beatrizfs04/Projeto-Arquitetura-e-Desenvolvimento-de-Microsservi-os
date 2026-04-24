# Projeto-Final-Microservicos
## O que foi feito?
### Descrição Geral e Requisitos Técnicos:
- As comunicações entre os diferentes serviços podem ser feitas de forma assíncrona ou síncrona, deixando a sua escolha da responsabilidade do(s) estudante(s).
- O modelo de colaboração entre os serviços deve ser o modelo Request/Response.
- O sistema deve ser desenvolvimento recorrendo ao estilo arquitetural Representational State Transfer (REST).
- A arquitetura de integração adotada deve ser a com orquestração, onde se assume a existência de um serviço central ou orquestrador.
- A escolha da Base de Dados a ser utilizada pelo sistema é da responsabilidade do(s) estudante(s) (e.g., MariaDB ou MongoDB).
- Todos os serviços desenvolvidos devem ser disponibilidade de forma individual em Docker Containers e devidamente integrados num ambiente local Kubernetes através da plataforma Minikube.

### Funcionalidades Mínimas:
- **(FM01) Serviço Orquestador:** Este microsserviço deve ser responsável pela integração de todos os serviços. É para este serviço que todos os pedidos devem ser enviados, que por sua vez, reenvia para os serviços descritos nas funcionalidades mínimas FM02, FM03 e FM04.
- **(FM02) Serviço de Autenticação:** Este microsserviço deve ser responsável pela autenticação dos utilizadores. É sugiro a utilização de JSON Web Tokens (JWT) para a gestão de tokens de acesso após uma autenticação bem-sucedida.
- **(FM03) Serviço de Utilizadores:** Este microsserviço deve permitir a gestão dos utilizadores, como a criação, edição e exclusão de contas do utilizador.
- **(FM04) Serviço de Tarefas:** Este microsserviço deve permitir a gestão das tarefas criadas pelos utilizadores. Os utilizadores podem criar, atualizar, e excluir as suas tarefas por meio deste serviço.

### Funcionalidades Adicionais:
- **(FA01) Serviço de Notificações:** Este serviço deve permitir o envio de notificações aos utilizadores, por exemplo, quando se verifica a data limite de conclusão de uma tarefa.
- **(FA02) Graphical User Interface:** O sistema deve fornece uma Graphical User Interface via uma aplicação Web.

## Quem participou?
Este projeto foi realizado por 3 alunos da Lincenciatura de Informática Web, Móvel e na Nuvem.
- Beatriz Santos 
- Manoela Azevedo 
- Rodrigo Paiva 
- Tiago Fonseca 

## Que linguagens de programação e tecnologias foram utilizadas?
- HTML
- JavaScript
- CSS
- PowerShell
- Docker
