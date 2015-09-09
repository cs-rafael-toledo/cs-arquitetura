# Arquitetura Android

O objetivo deste estudo de caso é fomentarmos a discussão sobre padrões arquiteturais de uma aplicação Android, levando em consideração pontos como testabilidade, complexidade de código, desempenho, tamanho de APK, dentre outros fatores.

O projeto será constituído de um root já configurado com algumas ferramentas e relatórios (como PMD, Findbugs, Checkstyle, Jacoco) que deverá ser integrado ao projeto para garantir uma melhor consistência.

Devido ao número de participantes, a melhor forma de trabalharmos é através de Pull Requests que serão analisadas ao projeto. Assim evitamos o problema de todo mundo fazendo commits na master.

**Importante:** para todas as abordagens propostas, é essencial e obrigatória a presença de testes!

Arquiteturas:
  - **MVC** - somente Android SDK
  - **MVC** - com Android Annotations
  - **MVC** - com Dagger ?
  - **MVC** - com RxJava ?
  - **MVP** - somente Android SDK
  - **MVP** - com Android Annotations
  - **MVP** - com Dagger / RxJava
  - **ALIEN** - Flow?
  - **Kotlin?**

Outras arquiteturas podem ser propostas e adicionadas ao projeto.

Cada uma das implementações deverá criar um aplicativo simples de e-commerce. O backend (doc pendente) será apenas um mock de implementação e contará apenas com:

  - **Home:** endpoint que retorna as categorias básicas de um e-commerce (homem, mulher, criança, etc)
  - **Catálogo:** endpoint que retornará a lista de produtos. Será possível filtrar esta lista.
  - **Sign-in / Sign-up:** criação e login de usuários

Com o tempo podemos evoluir o backend para ter detalhe de produto e carrinho, além de um cadastro mais completo.
