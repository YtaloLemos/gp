# GP

Sistema web para gerenciamento de produtos desenvolvidos em parceria com a [Sistech Informática]().
#### Backend
  * [Java 8]() 
  * [Jersey (REST)]()
  * [Spring BOOT]() 
  * [Spring Data]() 
  * [Spring Security]() 
  
#### Front-end
  * [AngularJS]() 
  * [Bower]() 
  * [Grunt]() 
  * [Karma]()
  * [Jasmine]() 
  * [Protractor]()

#### Banco 
  * [PostgresSQL]()

#### Servidor de aplicação
  * [Tomcat]()
  
#### Build
  * [Maven]()
  
#### A fazer
- Adicionar validações (campo obrigatório)
- Adicionar spring security com login
- Criar pesquisa na listagem (por descrição e código)
- Adicionar handle para capturar e exibir exeções em um toast
- Criar crud de usuário, grupo e cliente
- Criar cadastro e diretivas de permissões de usuários
- Executar grunt build no build do maven
- Disponibilizar demo da aplicação
- Adicionar testes com junit, karma e protractor

#### Como executar 

É necessário possuir o maven e o git instalados.

```sh
$ git clone [repositorio]
$ cd gp
$ mvn spring-boot:run
```


