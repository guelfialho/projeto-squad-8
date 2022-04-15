# ROBSON - SQUAD 12 :rocket: :rocket:

<h1 align="center">
    <img alt="My Turn" src="frontend/src/assets/svg/logo.svg"/>
</h1>

<ol>
    <li><a href="#sobre">Sobre</a></li>
        <li> <a href="#especificacoes">Especificações</a></li>
        <li> <a href="#comorodaroprojeto">Como Rodar o Projeto?</a> </li>
        <li> <a href="#resultados"> Resultados de Desenvolvimento</a> </li>
        <li> <a href="#features">Features</a> </li>
        <li> <a href="#conteudoxterno">Conteúdo externo</a></li>
        <li> <a href="#nossaequipe">Nossa Equipe</a></li>
    <li><a href="#licenca">Licença</a></li>
</ol>

<h2 id="sobre">Sobre</h2> 

O ROBSON - <b>R</b>ede <b>O</b>timizada de <b>B</b>usca e <b>S</b>olução "<b>O</b>range <b>N</b>etworking" - foi um projeto desenvolvido pelo Squad 12 para o Hackathon do Programa de Formação da [FCamara](https://digital.fcamara.com.br/programadeformacao) season 3. O objetivo desse projeto foi a construção de uma uma plataforma onde você encontra pessoas da tecnologia com conhecimentos diversos para tirar suas dúvidas sobre a área ou te orientar no aprendizado de novas habilidades. Na <b>ROBSON</b>, pessoas com diferentes níveis de experiência poderão se encontrar para trocar experiências, sanar dúvidas e criar networking, sempre priorizando o aprendizado. Sem mais dor de cabeça para encontrar ajuda, com o registro das habilidades dos colaboradores de forma fácil, intuitiva e veloz junto com nosso sistema de filtragem por skills os #SangueLaranja terão na plataforma da ROBSON a solução ideal para conexão das pessoas com foco no aprendizado.

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

#Em seguida deixeinicie a aplicação através do comando abaixo:
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
* Tela de visualizar o perfil de outro #SangueLaranja com as opções de contato, agendamento de mentoria (plataforma Calendly), LinkedIn, Portifólio. <b>VAMO CONECTAR!<b/>
* Tela de perfil para editar os dados do usuário com comunicação com o banco de dados na nuvem;
* Tela de ambientes de estudos coletivos (Crowndlearning) - No momento as salas são no discord, imaginamos o desenvolvimento da funcionalidade dentro da própria plataforma no futuro.

[Detalhamento dos resultados](resultados-desenvolvimento.md)

<h2 id="features">Features</h2>

* O que será que pensamos para o futuro da nossa aplicação...? :sunglasses:
    * **01** - Criação de banco de dados dinâmico utilizando modelo conceitual e em camadas.
    * **02** - Criação de perfil do administrador.
    * **03** - Emissão de relatórios de ocupação (acesso para o perfil de administrador).

<h2 id="conteudoxterno">Conteúdo Externo</h2> 

* :wink: Ficou curioso e quer saber como foi a idealização do My Turn de maneira rápida? Se liga no nosso [vídeo de funcionalidades](https://youtu.be/v7VXScbpCMg)! 
* :black_nib: Também foi escrito um [artigo](https://medium.com/@anapssouza/voltando-ao-escrit%C3%B3rio-em-seguran%C3%A7a-estudo-de-caso-fcamara-bbdf6de9a00e) relatando todo o processo de desenvolvimento feito pela nossa dupla de UX Design. 
* :yellow_heart: Nosso [Pitch](https://drive.google.com/file/d/1BqQAbJBO9QZUIt8zK1JFG_LoLW7MZW79/view?usp=sharing).

<h2 id="nossaequipe">Nossa Equipe</h2> 


|:woman_cartwheeling:|Nome|*No Programa de Formação eu...*|Contatos|
|--|--|:--:|--|
|<img src="assets/images/ana.png" width="300"><br>*UX Designer*| Ana Paula Souto| *"...Vi que em 14 dias é possível aprender e passar por milhares de coisas, desde trabalhar na prática com um squad, reconhecer as minhas funções e entender as de cada um, até fazer grandes amizades e conhecer grandes potenciais"* | [Linkedin](https://www.linkedin.com/in/ana-paula-souto-de-souza-a496681a4) [Email](anapssouza@live.com)
|<img src="assets/images/eirene.png" width="300"><br>*Desenvolvedora*| Eirene Fireman | *"...Descobri que CSS é bem mais difícil do que aparenta ser, saí do 0 com React a "até que sei alguma coisa", e percebi, na prática, a importância de fazer com que uma aplicação atenda o maior número possível de usuários. Além disso, pude enfrentar desafios super inesperados ao lado de uma equipe sensacional na qual todos exerceram seus papéis com excelência!"* | [Github](https://github.com/eireneof) [Linkedin](https://www.linkedin.com/in/eirene-fireman-16384618b/) [Email](eof@ic.ufal.br) |
| <img src="assets/images/lilian.png" width="300"><br>*Desenvolvedora* | Lílian Martins Fritzen | *"...Senti que tudo passou a fazer mais sentido quando conheci o Pai Flex-Box, amei a liberdade que ele dá a seus filhos. React com suas possibilidades delicinhas e o Typescript, ahh esse sim, tinhoso que só, mas gosto também. De nomes diferentes de restaurantes a vontade de encontrar essa equipe maravilhosa, Squad-8, vocês só reforçaram o quanto escuta ativa, comprometimento e empatia fazem qualquer projeto ser um sucesso. Obrigada!"* | [Github](https://github.com/lilianmartinsfritzen) [Linkedin](https://www.linkedin.com/in/lilian-martins-fritzen/) [Email](liliancmartinsfritzen@gmail.com) |
| <img src="assets/images/pedro.png" width="300"><br>*UX Designer* | Pedro Emerenciano | *"...Co-criei com pessoas incríveis, aprendi a trabalhar mais em equipe e que 15 dias passam voando!"* | [Linkedin](https://www.linkedin.com/in/pedro-emerenciano/) [Email](pemerenciano@outlook.com)

<h2 id="licenca">Licença</h2>

[LICENSE](https://github.com/lilianmartinsfritzen/projeto-squad-8/blob/main/LICENSE)

<hr>

<p> Feito com muito 🧡 pelo Squad-8<br> #FuturosSangueLaranja 🚀 <p>
