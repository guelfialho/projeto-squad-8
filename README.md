# ROBSON - SQUAD 12 :rocket: :rocket:
<ol>
    <li><a href="#sobre">Sobre</a></li>
        <li> <a href="#especificacoes">Especificações</a></li>
        <li> <a href="#comorodaroprojeto">Como Rodar o Projeto?</a> </li>
        <li> <a href="#resultados"> Resultados de Desenvolvimento</a> </li>
        <li> <a href="#features">Features</a> </li>
        <li> <a href="#conteudoxterno">Conteúdo externo</a></li>
        <li> <a href="#nossaequipe">Nossa Equipe</a></li>
</ol>

<h2 id="sobre">Sobre</h2> 

<img alt ="Error" src="https://user-images.githubusercontent.com/102808373/163622420-613cb404-4fe6-4fb3-8be2-f1603fca6d4a.svg">

A ROBSON - <b>R</b>ede <b>O</b>timizada de <b>B</b>usca e <b>S</b>olução "<b>O</b>range <b>N</b>etworking" - foi um projeto desenvolvido pelo Squad 12 para o Hackathon do Programa de Formação da [FCamara](https://digital.fcamara.com.br/programadeformacao) season 3. O objetivo desse projeto foi a construção de uma uma plataforma onde você encontra pessoas da tecnologia com conhecimentos diversos para tirar suas dúvidas sobre a área ou te orientar no aprendizado de novas habilidades. 

Na <b>ROBSON</b>, pessoas com diferentes níveis de experiência poderão se encontrar para trocar experiências, sanar dúvidas e criar networking, sempre priorizando o aprendizado. Sem mais dor de cabeça para encontrar ajuda, com o registro das habilidades dos colaboradores de forma fácil, intuitiva e veloz junto com nosso sistema de filtragem por skills os #SangueLaranja terão na plataforma da <b>ROBSON</b> a solução ideal para conexão das pessoas com foco no aprendizado.

<h2 id="especificacoes">Especificações</h2> 

<b>--></b> No backend utilizamos: 
    <ul>
    <li>cors: v.2.8.5</li>
    <li>dotenv: v.16.0.0</li>
    <li>express: v.4.17.1</li>
    <li>mongoose: v.6.0.7</li>
    <li>nodemon: v.2.0.13</li>
    <li>MongoDB</li>
    </ul>
 <b>--></b> No frontend utilizamos: 
      <ul>
    <li> axios: v.0.26.1</li>
    <li> bootstrap: v.4.6.1</li>
    <li> react: v.16.12.0</li>
    <li> react-router-dom: v.6.3.0</li>
    </ul>
    
 <b>--></b> Você pode verificar todas as dependências utilizadas no projeto no arquivo Package.json tanto na pasta de backend quanto na pasta de frontend. 
    
 
<h2 id="comorodaroprojeto">Como rodar o projeto?</h2>

<b>Você precisará:</b>
<ul>
    <li>Node JS - versão 16.13.1 (obrigatório)</li>
    <li>Visual Studio Code (recomendado)</li>
    <li>Git bash </li>
    <li>Windowns 10 ou superior</li>
</ul>

``` bash
#Clone este repositório no terminal:
$ git clone https://github.com/FcamaraSquad12/ProjetoSquad12.git
``` 
*OBS: Para que a aplicação funcione como esperado, você deve deixar o frontend e o backend rodando simultaneamente (abra dois terminais):*

``` bash

#Com o primeiro terminal, abra a pasta backend e execute o comando:
$ npm install
ou
$ yarn install

#Em seguida inicie a aplicação através do comando abaixo:
$ npm start
ou
$ yarn start

#A aplicação (backend) será aberta na porta:3001 - acesse http://localhost:3001. 
```
Agora que o backend está ativo, é necessário repetir o processo para o frontend: 

```bash
#No segundo terminal, abra a pasta frontend e execute o comando:
$ npm install
ou
$ yarn install

#Em seguida inicie a aplicação através do comando abaixo:
$ npm start
ou
$ yarn start

#A aplicação(frontend) será aberta na porta:3000 - acesse http://localhost:3000. 
```

Agora que tanto o backend quanto o frontend estão rodando, você precisará acessar o sistema. Para isso, você pode se cadastrar como #SangueLaranja na tela de login -> cadastre-se (lembre de anotar seu e-mail e senha cadastrado, no momento não temos um sistema de recuperação de senha ativo). 

Caso não queira ou tenha alguma dificuldade em acessar o sistema, você poderá usar um usuário convidado:

``` bash

email: convidado@fcamara.com.br
senha: 123456

```

<h2 id="resultados">Resultados de Desenvolvimento</h2>

* Implementação da interface com HTML, CSS, Bootstrap e React;
* Sistema de login (autenticação com o banco de dados na nuvem);
* Sistema de cadastro de colaboradores conectado ao banco de dados na nuvem;
* Registro das habilidades dos colaboradores de forma fácil;
* Tela de home com os cards de todos os colaboradores cadastrados;
* Filtragem dos #SangueLaranja (cards) por skills, nome ou cargo. 
* Tela de visualizar o perfil de outro #SangueLaranja com as opções de contato, agendamento de mentoria (plataforma Calendly), LinkedIn, Portifólio. <b>VAMO CONECTAR!</b>
* Tela de perfil para editar os dados do usuário com comunicação com o banco de dados na nuvem;
* Tela de ambientes de estudos coletivos (Crowndlearning) - No momento as salas são no discord, imaginamos o desenvolvimento da funcionalidade dentro da própria plataforma no futuro.

<h2 id="features">Features</h2>

* O que será que pensamos para o futuro da nossa aplicação...? :sunglasses:
    * **01** - Criação de salas de crowndlearning(aprendizado coletivo) nativo da plataforma.
    * **02** - Criação de sistema de agendamento de mentoria nativo da plataforma.
    * **03** - Autenticação com token JWT
    * **04** - Deploy
    * **05** - Adicionar camadas de proteção contra erros do usuário.

<h2 id="conteudoxterno">Conteúdo Externo</h2> 

* [Pitch](https://www.youtube.com/watch?v=uFu-gMvcEFo)
* Video de funcionalidades
* Artigo

<h2 id="nossaequipe">Nossa Equipe</h2> 


|:rocket:|Nome | Contatos|
|--|--|--|
|<img src="https://user-images.githubusercontent.com/100007542/163568018-ddfb28a9-8cfe-4eea-b9f1-f1c71dc43fb8.jpg" width="300"><br>*Desenvolvedor WEB*| Miguel Fialho| [Linkedin](https://www.linkedin.com/in/guelfialho/) 
|<img src="https://user-images.githubusercontent.com/100007542/163568233-25c46283-b574-4492-9b93-f36c0bb776c5.jpg" width="300"><br>*Desenvolvedor WEB*| Wellington Henrique| [Linkedin](https://www.linkedin.com/in/wellingtonhlc/)
|<img src="https://user-images.githubusercontent.com/100007542/163568393-67d6a3bb-20a7-4198-9bbc-9d95dcbf14c5.jpg" width="300"><br>*Desenvolvedor WEB*| Edmilson Gomes| [Linkedin](https://www.linkedin.com/in/edmilsondmx/) 
|<img src="https://user-images.githubusercontent.com/100007542/163568265-93618c14-73db-401d-8a31-57f83ef3f60d.jpg" width="300"><br>*UX/UI Designer*| Gustavo Kappey| [Linkedin](https://www.linkedin.com/in/gkappey/) 
|<img src="https://user-images.githubusercontent.com/100007542/163568327-eed4bd44-1703-45d4-81d0-1838a28a1961.jpg" width="300"><br>*UX/UI Designer*| Gustavo Gomes| [Linkedin](https://www.linkedin.com/in/guvboas/) 
|<img src="https://user-images.githubusercontent.com/100007542/163568158-8aede2bb-745b-43a6-adab-6a4e9c782080.jpg" width="300"><br>*UX/UI Designer*| Natan Ferreira| [Linkedin](https://www.linkedin.com/in/natan-ferreira/)

<hr>

<p> Projeto do grande Squad-12!<br> <p>
