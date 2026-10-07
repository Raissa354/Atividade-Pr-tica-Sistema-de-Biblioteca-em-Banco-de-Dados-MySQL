
# 📚 Banco de Dados - Sistema de Biblioteca

Este projeto foi desenvolvido para uma atividade de Banco de Dados, utilizando **MySQL** e **phpMyAdmin**.

O objetivo é criar um banco de dados simples para organizar informações de alunos, livros e empréstimos.

## 🗄️ Banco de Dados

O banco criado se chama `biblioteca`.

Ele possui três tabelas:

- 👤 `aluno`
- 📖 `livro`
- 📚 `emprestimo`

## 👤 Tabela Aluno

A tabela `aluno` é responsável por guardar os dados dos alunos.

Ela possui:

- ID do aluno
- Nome
- E-mail
- Curso

Foram cadastrados alguns alunos para testar o funcionamento do banco.

## 📖 Tabela Livro

A tabela `livro` guarda as informações dos livros da biblioteca.

Ela possui:

- ID do livro
- Título
- Autor
- Ano de publicação

Alguns livros cadastrados foram **Dom Casmurro**, **O Cortiço** e **Clean Code**.

## 📚 Tabela Empréstimo

A tabela `emprestimo` registra os livros que foram emprestados pelos alunos.

Ela possui:

- ID do empréstimo
- Data do empréstimo
- Data de devolução
- ID do aluno
- ID do livro

Essa tabela também faz a ligação entre os alunos e os livros.

## 🔗 Relacionamentos

O banco possui dois relacionamentos principais:

- Um aluno pode realizar vários empréstimos.
- Um livro pode aparecer em vários empréstimos.

A tabela `emprestimo` utiliza `id_aluno` e `id_livro` como chaves estrangeiras.
```

ALUNO 1 ───── N EMPRESTIMO N ───── 1 LIVRO

```

## 🔄 Operações realizadas

Neste projeto foram utilizados os principais comandos SQL:

- `CREATE` para criar o banco e as tabelas;
- `INSERT` para cadastrar alunos, livros e empréstimos;
- `SELECT` para consultar os dados;
- `INNER JOIN` para juntar informações das tabelas;
- `UPDATE` para alterar informações;
- `DELETE` para excluir registros.

## 🛠️ Tecnologias utilizadas

- MySQL
- phpMyAdmin
- SQL
- Draw.io

## 🎯 Objetivo da atividade

A atividade tem como objetivo praticar a criação de um banco de dados, criação de tabelas, relacionamentos entre tabelas e utilização dos comandos básicos de SQL.

O projeto representa um sistema simples de biblioteca, onde é possível cadastrar alunos e livros e registrar os empréstimos realizados.

<img width="918" height="284" alt="Captura de tela 2026-10-07 144308" src="https://github.com/user-attachments/assets/8cd1ac70-fe63-4b7d-9ab0-abc5536cea96" />

<img width="228" height="195" alt="Captura de tela 2026-10-07 141451" src="https://github.com/user-attachments/assets/7d1fe8a8-97e7-482f-a0a4-e9edca158137" />

<img width="569" height="170" alt="Captura de tela 2026-10-07 142133" src="https://github.com/user-attachments/assets/6d4a121c-29a6-4c50-8db0-5b4b4df3b35d" />

<img width="488" height="131" alt="Captura de tela 2026-10-07 142209" src="https://github.com/user-attachments/assets/9dd23356-0a83-4e6d-900f-74180e053665" />

<img width="497" height="190" alt="Captura de tela 2026-10-07 142317" src="https://github.com/user-attachments/assets/51a27f34-8526-40e1-972a-799c1f532edf" />

<img width="708" height="116" alt="Captura de tela 2026-10-07 142348" src="https://github.com/user-attachments/assets/5aabff12-97e8-4bfc-b022-419a57ba7c1f" />

<img width="654" height="147" alt="Captura de tela 2026-10-07 142426" src="https://github.com/user-attachments/assets/0ff01d12-267c-451c-9bb6-458462522817" />

<img width="756" height="147" alt="Captura de tela 2026-10-07 142451" src="https://github.com/user-attachments/assets/9c9b41e1-aefc-49a8-91dc-b52614989d8e" />

<img width="960" height="112" alt="Captura de tela 2026-10-07 142554" src="https://github.com/user-attachments/assets/73678470-ee14-474c-ad72-c9d7b535c5b8" />

<img width="978" height="108" alt="Captura de tela 2026-10-07 142730" src="https://github.com/user-attachments/assets/f31a57de-1775-409e-95a4-37a037d0a9d3" />

<img width="330" height="119" alt="Captura de tela 2026-10-07 142803" src="https://github.com/user-attachments/assets/7e1bc038-e912-4db9-a1a0-5937f5e2b087" />

<img width="988" height="100" alt="Captura de tela 2026-10-07 142833" src="https://github.com/user-attachments/assets/7feb53c1-fef2-4231-9c5c-7a74e4d673d8" />

<img width="280" height="97" alt="Captura de tela 2026-10-07 142858" src="https://github.com/user-attachments/assets/11290ea9-4216-4af5-ad04-76578fbe0389" />

<img width="734" height="78" alt="Captura de tela 2026-10-07 142937" src="https://github.com/user-attachments/assets/50557273-a28d-41eb-a6eb-39263ffe0b04" />
