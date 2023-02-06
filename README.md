# Projeto Web Services

[![NPM](https://img.shields.io/npm/l/react)](https://github.com/ricardoadevmelo/workshop-springboot3-jpa/blob/main/LICENCE) 

# Propósito do projeto:

:small_orange_diamond: Criar projeto Spring Boot Java <br/>
:small_orange_diamond: Implementar modelo de domínio <br/>
:small_orange_diamond: Estruturar camadas lógicas: resource, service, repository <br/>
:small_orange_diamond: Configurar banco de dados de teste (H2) <br/>
:small_orange_diamond: Povoar o banco de dados <br/>
:small_orange_diamond: CRUD - Create, Retrieve, Update, Delete <br/>
:small_orange_diamond: Tratamento de exceções <br/>


A aplicação destina-se a elaborar as entidades do negócio com vários tipos de relacionamentos de "um para muitos", "muitos para um" e vice-versa, usnado o modelo divididos em camadas lógicas que funciona no servidor, usando-se a camada Resource (controladores REST - Representational State Transfer, que são as interfaces da aplicação com o "Back End", os quais irão receber as requisições e vão responder de acordo com o comportamento do sistema), a camada de Serviços e a camada de Acesso a dados, bem como, essa pilha de camadas comunicam-se com as camadas de Entidades.
<br/>
Configurado o banco de dados relacional para testes e povoado o banco de dados, adminstramos o "CRUD" que são as operações de cadastro completo da entidade para criar, recuperar, atualizar e deletar, assim como, gerenciar os erros preventivos com o tratamento de exceções.
Logo, com a implementação do modelo de domínio, instanciou-se os objetos e criou-se a base de dados relacional, registrando-se automaticamente.
<br/>
Para o panorama do projeto, utilizou-se as ferramentas como o Spring Boot, o framework usado para criar a apliação, o Apache Tomcat, o conteúdo Web para usar a aplicação, o Maven, como gerenciador de dependências, o banco de dados H2 para testes, o Postman, para testar as requisições, e após, desenvoveu-se toda a aplicação e testou-se, gerando-se o ambiente de produção no banco de dados relacional, com o Postgrees.

## Layout:
![Mobile 1](https://github.com/ricardoadevmelo/assets/blob/main/workshop-springboot3-jpa/modelo%20layout1.jpg)

## Camadas Lógicas:
![Mobile 1](https://github.com/ricardoadevmelo/assets/blob/main/workshop-springboot3-jpa/logical%20layers.jpg)

## Modelos conceituais:

:one: <br /> <br />
![Modelo Conceitual](https://github.com/ricardoadevmelo/assets/blob/main/workshop-springboot3-jpa/Domain%20Model%20.jpg) <br />

:two: <br /> <br />
![Modelo Conceitual](https://github.com/ricardoadevmelo/assets/blob/main/workshop-springboot3-jpa/Domain%20Instance%20.jpg) <br />

# Tecnologias utilizadas:
## Back end
:small_orange_diamond: Java <br/>
:small_orange_diamond: Spring Boot <br/>
:small_orange_diamond: Apache Tomcat <br/>
:small_orange_diamond: Maven <br/>
:small_orange_diamond: H2 <br/>
:small_orange_diamond: Postman <br/>
:small_orange_diamond: PostgreSQL <br/>

# Como executar o projeto:

Pré-requisitos: <br />

:small_orange_diamond: Java <br/>
:small_orange_diamond: Spring Boot <br/>
:small_orange_diamond: Apache Tomcat <br/>
:small_orange_diamond: Maven <br/>
:small_orange_diamond: H2 <br/>

```bash
# clonar repositório: 
git clone git@github.com:ricardoadevmelo/workshop-springboot3-jpa.git
```

# Autor: <br />
Ricardo Alves Melo <br />
https://www.linkedin.com/in/ricardo-alves-melo-3971b9265/

# Agradecimentos: <br />

Professor: Nélio Alves. <br />
https://devsuperior.com.br/cursos <br />
https://www.linkedin.com/in/nelio-alves/?originalSubdomain=br
