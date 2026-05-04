# Atividade-Avaliativa-C-📚 ControleBiblioteca

Sistema simples de console desenvolvido em C# utilizando os conceitos de Programação Orientada a Objetos (POO).

🎯 Objetivo

Simular o funcionamento básico de uma biblioteca escolar, permitindo:

Cadastro de livros
Cadastro de alunos
Exibição de dados
Simulação de empréstimo de livros
🧠 Conceitos aplicados

O projeto utiliza os principais pilares da POO:

Classes e Objetos
Atributos
Métodos
Construtores
Encapsulamento básico
Listas (List<T>)
🏗️ Estrutura do Sistema
📖 Classe Livro

Responsável por representar os livros da biblioteca.

Atributos:

Titulo
Autor
AnoPublicacao
Disponivel

Métodos:

ExibirDetalhes() → mostra as informações do livro
Emprestar() → altera o status para emprestado
👨‍🎓 Classe Aluno

Representa os alunos da escola.

Atributos:

Nome
Matricula
Turma

Métodos:

ExibirDados() → exibe as informações do aluno
⚙️ Funcionalidades
Criação de objetos com construtor padrão e com parâmetros
Armazenamento de livros em uma lista (List<Livro>)
Exibição de todos os livros cadastrados
Simulação de empréstimo de um livro
Exibição do aluno responsável pelo empréstimo
▶️ Execução do Programa

Ao executar o sistema, o console exibirá:

Lista de livros cadastrados 📚
Situação de cada livro (Disponível ou Emprestado)
Dados do aluno responsável pelo empréstimo 👤
🧪 Exemplo de saída
LISTA DE LIVROS CADASTRADOS
Título: Harry Potter e a Pedra Filosofal | Autor: J.K. Rowling | Ano: 1997 | Situação: Disponível
Título: Senhor dos Anéis | Autor: J.R.R. Tolkien | Ano: 1954 | Situação: Emprestado
Título: Sem título | Autor: Desconhecido | Ano: 0 | Situação: Disponível

ALUNO RESPONSÁVEL PELO EMPRÉSTIMO
Nome: Dionata | Matrícula: 2026002 | Turma: Informática
🚀 Tecnologias utilizadas
Linguagem: C#
Plataforma: .NET (Console Application)
👨‍💻 Autor
Dionata
📌 Observações

Este projeto foi desenvolvido com fins educacionais para prática de conceitos de Programação Orientada a Objetos.
