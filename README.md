# Portal de Agendamento de Visitas - Avaí F.C.

## Sobre o projeto

Este projeto é um protótipo/ piloto navegável desenvolvido para a disciplina **Projeto Integrador Multidisciplinar e Extensionista - PIME**, do curso de **Análise e Desenvolvimento de Sistemas** do Centro Universitário Belas Artes de São Paulo.

A proposta tem como objetivo simular uma aplicação web para o agendamento de visitas ao estádio da Ressacada, dentro do contexto do projeto social **Paz e Harmonia no Futebol**, vinculado ao Avaí Futebol Clube.

O protótipo foi desenvolvido como uma entrega inicial de frontend, com foco na validação visual e navegável da jornada do usuário. Nesta etapa, ainda não há integração com backend, banco de dados ou autenticação real.

## Objetivo do piloto

O objetivo deste piloto é validar a navegação principal da aplicação web, permitindo que uma instituição interessada simule o processo de solicitação de visita ao estádio.

O fluxo testado contempla:

1. Tela de boas-vindas;
2. Tela de login visual/simulado;
3. Página inicial com eventos;
4. Formulário de agendamento;
5. Escolha de data e horário;
6. Tela de confirmação da solicitação.

## Problema identificado

O projeto social Paz e Harmonia no Futebol recebe solicitações de escolas, ONGs, projetos sociais e instituições educacionais interessadas em realizar visitas formativas ao estádio da Ressacada.

Atualmente, parte desse processo pode ocorrer por meio de conversas, mensagens e registros manuais. Isso pode dificultar a organização das informações, o acompanhamento das solicitações e a padronização do atendimento.

Diante disso, a aplicação propõe um canal inicial para centralizar o processo de solicitação de visitas.

## Solução proposta

A solução proposta é uma aplicação web responsiva para facilitar o agendamento de visitas ao estádio. Nesta primeira versão, o sistema funciona como um protótipo navegável, simulando o preenchimento dos dados da instituição, a escolha de data e horário e a confirmação da solicitação.

A aplicação foi pensada inicialmente para web, pretendemos futuramente evoluir para:

* Integração com backend;
* Banco de dados;
* Painel administrativo;
* Envio automático de e-mails;
* Módulo de feedback das instituições;
* Dashboard de indicadores sociais;
* Versão mobile.

## Tecnologias utilizadas

Nesta versão inicial, foram utilizadas tecnologias básicas de frontend:

* HTML5;
* CSS3;
* JavaScript.

O projeto foi desenvolvido em arquivo único, com o objetivo de simplificar a entrega do piloto navegável e facilitar a execução local.

## Estrutura do projeto

```txt
pime-agendamento-avai/
│
└── index.html
```

O arquivo `index.html` contém toda a estrutura do protótipo, incluindo:

* marcação HTML;
* estilos CSS;
* lógica de navegação em JavaScript.

## Como executar o projeto

Para executar o protótipo localmente:

1. Faça o download ou clone este repositório;
2. Abra a pasta do projeto;
3. Clique duas vezes no arquivo `index.html`;
4. O protótipo será aberto no navegador.


## Fluxo de navegação

O protótipo simula a seguinte jornada:

```txt
Boas-vindas → Login → Home → Agendar visita → Formulário → Data e horário → Confirmação
```

Durante o fluxo, o usuário informa dados como:

* nome;
* e-mail;
* telefone;
* nome da instituição;
* e-mail da instituição;
* telefone da instituição;
* endereço;
* perfil dos visitantes;
* data desejada;
* horário desejado.

Ao final, a aplicação exibe uma tela de confirmação com o resumo da solicitação.

## Limitações da versão atual

Esta versão é apenas um piloto navegável de frontend. Portanto, algumas funcionalidades ainda não estão implementadas:

* não há banco de dados;
* não há login real;
* não há envio real de formulário;
* não há envio automático de e-mail;
* não há painel administrativo;
* os dados não são persistidos em servidor;
* a confirmação da solicitação é apenas visual.

Essas limitações fazem parte do escopo atual do piloto e serão consideradas em etapas futuras do projeto.

## Planejamento futuro

Para as próximas versões, o projeto poderá evoluir com:

* criação de backend;
* integração com banco de dados relacional;
* cadastro real de instituições;
* autenticação de usuários administrativos;
* painel para gestão dos agendamentos;
* controle de status das solicitações;
* envio de confirmação por e-mail;
* módulo de feedback após a visita;
* dashboard com indicadores sociais;
* versão mobile nativa ou PWA.

## Integrantes

* Felipe Fernando Schaitel
* Laíse Neves
* Angelo Fontoura

## Entidade parceira

A entidade parceira do projeto é o **Avaí Futebol Clube**, por meio da Coordenação de Projetos Sociais, Comunitários e Filantrópicos, no contexto do projeto **Paz e Harmonia no Futebol**.

## Status do projeto

Protótipo navegável em desenvolvimento.

Versão atual: piloto frontend para validação visual e teste do fluxo principal de agendamento.

## Observação acadêmica

Este projeto foi desenvolvido com finalidade acadêmica, como parte da entrega da disciplina Projeto Integrador Multidisciplinar e Extensionista - PIME. A versão atual não representa uma aplicação oficial em produção do Avaí Futebol Clube.
