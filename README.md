Descrição em Português:
Este programa Java implementa um sistema de gerenciamento de mídia, onde é possível cadastrar e manipular informações sobre filmes, séries e seus respectivos episódios. Ele utiliza o conceito de orientação a objetos, interfaces e herança para organizar os dados e operações.

Componentes principais:
Titulo: Classe base que representa características comuns entre filmes e séries, como nome, ano de lançamento, duração e avaliação.

Filme: Subclasse de Titulo que representa um filme, podendo implementar a interface Classificavel.

Serie: Subclasse de Titulo, com atributos específicos como número de temporadas, episódios por temporada, etc.

Episodio: Representa um episódio de uma série, vinculado a um título principal.

Classificavel: Interface usada para definir um contrato de itens que podem ser classificados (com base na avaliação).

calculadoraDeTempo: Classe que calcula o tempo total de exibição dos títulos adicionados, somando a duração de todos.

Principal: Classe com o método main, responsável por iniciar a aplicação, criando objetos e exibindo dados no console.

Conceitos aplicados:
Programação Orientada a Objetos (POO)

Encapsulamento, herança e polimorfismo

Interface para generalização de comportamentos

--------------------------------------------------------------------------------------------------------

Description in English:
This Java program implements a media management system, allowing users to register and handle information about movies, series, and their episodes. It applies object-oriented programming principles, interfaces, and inheritance to organize data and operations.

Main components:
Titulo: Base class representing common features of movies and series, such as name, release year, duration, and rating.

Filme: Subclass of Titulo, represents a movie and can implement the Classificavel interface.

Serie: Subclass of Titulo, with specific attributes like number of seasons, episodes per season, etc.

Episodio: Represents an episode from a series, linked to a main title.

Classificavel: Interface used to define a contract for items that can be rated (based on evaluation).

calculadoraDeTempo: Class that calculates the total playback time of added titles by summing their durations.

Principal: Class with the main method that starts the application, creating objects and displaying data in the console.

Key concepts:
Object-Oriented Programming (OOP)

Encapsulation, inheritance, and polymorphism

Interface abstraction for common behaviors
