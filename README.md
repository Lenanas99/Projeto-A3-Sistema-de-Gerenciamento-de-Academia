# Projeto-A3-Sistema-de-Gerenciamento-de-Academia
Objetivo do Projeto: Desenvolver um sistema básico em Java com persistência de dados em banco de dados SQL, que permite o cadastro, consulta, atualização e exclusão (CRUD) de alunos e seus treinos. A interface deverá atender a critérios de organização, funcionalidade e documentação.

O Sistema de Gestão para Academia (A3) é uma aplicação desktop desenvolvida em Java com persistência de dados em SQLite. O objetivo principal do projeto é criar uma solução simples, eficiente e fácil de usar para gerenciar alunos e seus respectivos treinos, oferecendo uma interface simples e armazenamento local em banco de dados. Essa aplicação permite o cadastro de novos alunos, edição de alunos já cadastrados e exclusão cadastro, a aplicação possui uma segunda tela onde através da listagem de alunos é possível selecionar um cadastro e adicionar treinos, através do banco de dados sempre é possível consultar o historico de treinos de cada aluno.


Principais funcionalidades do sistema:

  1.Cadastro de alunos: A aplicação permite registrar dados completos de cada aluno;
  
  2.Cadastro de Treinos: Cada aluno pode possuir diversos treinos associados, é possivel selecionar um aluno e vizualizar todo o historico de treinos do mesmo;
  
  3.Banco de Dados SQLite integrado: O sistema utiliza o arquivo gym.db, criado automaticamente no diretório do projeto - Tabelas utilizadas: students e trainings;
  
  4.Interface Gráfica (Swing): O sistema possui janelas (JFrames e JDialogs) organizadas e acessíveis através de botões, dessa forma o usuario possui acesso a tela principal, tela de cadatro dos alunos e a tela de cadastro dos treinos;
  
  5.Máscaras e Validações: Utilizando de mascaras nos campos o sistema garante a inserção dos dados de forma correta dentro do banco de dados.


Ferramentas utilizadas:
  Linguagem Java - Desenvolvimento através do software NetBeans IDE 27;
  Swing para a interface gráfica;
  SQL Lite para o banco de Dados;
  JDBC SQLite para a conexão com banco de dados;
  MaskFormatter - Mascara para os campos de inserção de dados.


  #Passa à passo de configuração para execução:

1)Requisitos:
  
  ->NetBeans IDE 27 instalado

  ->Driver JDBC SQLLITE - sqlite-jdbc-3.51.0.0.jar

2)Preparação do NetBeans e Banco de Dados

  ->Baixe o JAR do driver SQLite (sqlite-jdbc-3.51.0.0.jar)

  ->Dentro do NetBeans vá em Properties -> Libraries -> Add JAR/Folder -> Procure o arquivo do SQLite e selecione a opção abrir.

4)Código:

  ->No software NetBeans inicie um novo projeto e arquivo

  ->Copie o código de dentro desse repositorio e cole dentro projeto/arquivo criado no NetBeans

5)Rodar a aplicação:

->Em cima do arquivo do projeto na lateral esquerda, clique com o botão direito e selecione a opção "RUN"
  

