# Desafio de Projeto - Trilha .NET - API e Entity Framework

## Contexto
Construí um sistema gerenciador de tarefas utilizando meus conhecimentos adquiridos no módulo de API e Entity Framework da trilha .NET da DIO.

O sistema permite cadastrar uma lista de tarefas para organizar melhor a rotina diária.

## Detalhes do Projeto
### Modelo de Dados
A classe principal utilizada é a classe `Tarefa`, que possui os seguintes atributos:
- `Id`: Identificador único da tarefa.
- `Titulo`: Título da tarefa.
- `Descricao`: Descrição detalhada da tarefa.
- `Data`: Data de realização da tarefa.
- `Status`: Status atual da tarefa.

### Métodos Implementados
Foram implementados os seguintes métodos para cada endpoint:
- `GET /Tarefa/{id}`: Retorna uma tarefa específica com base no ID fornecido.
- `PUT /Tarefa/{id}`: Atualiza os dados de uma tarefa existente com base no ID fornecido.
- `DELETE /Tarefa/{id}`: Remove uma tarefa específica com base no ID fornecido.
- `GET /Tarefa/ObterTodos`: Retorna todas as tarefas cadastradas no sistema.
- `GET /Tarefa/ObterPorTitulo`: Retorna as tarefas que contenham o título especificado.
- `GET /Tarefa/ObterPorData`: Retorna as tarefas agendadas para a data especificada.
- `GET /Tarefa/ObterPorStatus`: Retorna as tarefas com o status especificado.
- `POST /Tarefa`: Cria uma nova tarefa com base nos dados fornecidos no corpo da requisição.

### Implementação
Desenvolvi a solução utilizando o padrão de arquitetura MVC (Model-View-Controller), garantindo uma estrutura organizada e de fácil manutenção. Utilizei as melhores práticas de desenvolvimento e padrões de projeto.

A integração com o Swagger foi realizada para fornecer uma documentação detalhada dos endpoints e facilitar o teste das funcionalidades.