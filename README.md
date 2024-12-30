# App

GymPass style app

## RFs (Requisitos Funcionais)
 - [  ] Deve ser possível realizar um cadastro;
 - [  ] Deve ser possível se autenticar;
 - [  ] Deve ser possível obter o perfil de um usuário logado;
 - [  ] Deve ser possível obter o número de check-ins realizados pelo usuário logado
 - [  ] Deve ser possível o usuário obter seu histórico de check-ins
 - [  ] Deve ser possível o usuário buscar academias próximas
 - [  ] Deve ser possível o usuário realizar buscas por academia pelo nome
 - [  ] Deve ser possível o usuário realizar check-in em uma academia
 - [  ] Deve ser possível validar o check-in de um usuário
 - [  ] Deve ser possível cadastrar uma academia

## RNs (Regras de Negócio)
 - [  ] O usuário não deve poder se cadastrar com um e-mail duplicado
 - [  ] O usuário não deve poder realizar mais de um check-in por dia
 - [  ] O usuário não pode fazer check-in se não estiver perto (100m) da academia
 - [  ] O check-in só poderá ser validado até 20 minutos após sua criação
 - [  ] O check-in só poderá ser validado por administradores
 - [  ] A academia só poderá ser cadastrada por administradores

## RNFs (Requisitos Não Funcionais)
 - [  ] A senha do usuário deverá ser criptografada
 - [  ] Os dados da aplicação precisam estar persistidos em um banco de dados PostgresSQL
 - [  ] Todas as listas de dados precisam estar páginadas com até 20 itens por página
 - [  ] O usuário deve ser identificado por um JWT (JSON Web Token)
 