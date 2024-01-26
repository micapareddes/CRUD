# Sistema de Cadastro de Estudantes em Python

## Visão Geral do Projeto

Este repositório contém um script Python que representa meu primeiro projeto prático no aprendizado de lógica de programação e Python. O script implementa um sistema básico de cadastro de estudantes, focando em uma boa experiência do usuário (UX) no terminal.

## Funcionalidades

- **Adicionar Estudantes**: Permite a inserção de novos estudantes no sistema, capturando informações como CPF, nome, idade, curso e disciplinas.
- **Remover Estudantes**: Oferece a opção de remover estudantes do sistema utilizando o CPF como chave.
- **Consultar Estudantes**: Habilita a visualização dos dados de todos os estudantes cadastrados ou a busca por um estudante específico pelo CPF.

## Como Funciona

- O script inicia apresentando um menu com opções para adicionar, remover ou consultar estudantes.
- `add_students` adiciona um novo estudante após validar os dados inseridos.
- `delete_student` remove um estudante com base no CPF fornecido.
- `consultate_student` permite visualizar todos os estudantes ou buscar um estudante pelo CPF.
- Inclui várias funções de validação para garantir a integridade dos dados.

## Estrutura do Banco de Dados

O sistema utiliza um dicionário Python como banco de dados simples, com o CPF do estudante como chave e uma tupla contendo nome, idade, curso e disciplinas como valor.

## Execução

Para executar o script, é necessário ter Python instalado. O script pode ser executado em um interpretador Python, com interação através do console.

