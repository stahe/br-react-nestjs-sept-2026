# RdvMedecins - Um exemplo cliente/servidor com NestJS e React

Este repositório acompanha um curso sobre a reconstrução de uma aplicação cliente/servidor de agendamento de consultas médicas (`RdvMedecins`) com ferramentas modernas. Ele contém apenas este README; o curso completo está disponível online.

## 📖 Leia o curso

**[https://stahe.github.io/br-react-nestjs-sept-2026](https://stahe.github.io/br-react-nestjs-sept-2026)**

## Sobre

Este documento adapta um curso original de 2014 (*Um exemplo cliente/servidor - AngularJS 1.x / Spring 4*) às tecnologias atuais:
- O servidor, escrito em Java com Spring MVC, é substituído por um servidor **NestJS** (TypeScript);
- o cliente **AngularJS 1.x** é substituído por um cliente **React** (componentes de função, hooks);
- as funcionalidades principais e o banco de dados permanecem, em princípio, inalterados, com o acréscimo de autenticação baseada em papéis (JWT), que não existia no original.

Este curso foi escrito com a ajuda da IA Claude (Anthropic), que gerou a maior parte do código e das explicações; o autor testou e validou todo o curso seguindo o documento gerado.

## Conteúdo do curso

1. **Introdução** - Objetivos, pré-requisitos, arquitetura geral da aplicação
2. **Capítulo 1** - Configuração do ambiente de desenvolvimento
3. **Capítulo 2** - Introdução ao NestJS
4. **Capítulo 3** - O servidor NestJS da aplicação RdvMedecins
5. **Capítulo 4** - Introdução ao React
6. **Capítulo 5** - O cliente React da aplicação RdvMedecins
7. **Capítulo 6** - Conclusão e próximos passos

## Tecnologias abordadas

- **Servidor**: NestJS, TypeORM, MySQL, autenticação JWT (`@nestjs/passport`, `@nestjs/jwt`), controle de acesso baseado em papéis
- **Cliente**: React 19, Vite, TypeScript, hooks, i18next (internacionalização francês/inglês), Bootstrap

## Pré-requisitos

Nenhum conhecimento prévio de NestJS ou React é necessário. Um conhecimento básico de JavaScript, HTTP e linha de comando é suficiente para concluir o curso com sucesso.

## Autores

IA Claude (principalmente) e Serge Tahé (teste do código e revisão do curso)
