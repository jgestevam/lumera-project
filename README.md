# Lumera Project

Plataforma web que transforma a letra de uma música em uma apresentação de slides pronta para projeção em cultos e eventos religiosos.

![status](https://img.shields.io/badge/status-em%20desenvolvimento-yellow)
![versão](https://img.shields.io/badge/vers%C3%A3o-0.1.0-blue)

## Sobre

O Lumera Project atende equipes de igrejas responsáveis pela produção e projeção de conteúdo visual durante cultos e eventos. A proposta é entregar uma ferramenta simples para montar apresentações musicais em poucos segundos.

Este é um projeto acadêmico desenvolvido por estudantes.

## O problema

Equipes de projeção raramente recebem a lista de músicas com antecedência. Quando o culto está começando, alguém precisa buscar letras e imagens manualmente, colar tudo em um editor de slides e formatar cada tela sob pressão. O resultado costuma ser apresentação incompleta, letra errada e atraso durante o louvor.

Ferramentas genéricas de apresentação não resolvem porque exigem trabalho manual repetitivo a cada música nova.

## A solução

Uma aplicação web onde o usuário cola a letra da música em uma caixa de texto e clica em um botão para gerar a apresentação completa. O sistema divide o conteúdo em slides e aplica um template visual, escolhido manualmente ou de forma automática.

As apresentações ficam salvas na conta do usuário. Em versões futuras poderão ser publicadas, formando uma biblioteca coletiva que reduz ainda mais o tempo de preparo das equipes.

## Público-alvo

- Equipes de mídia
- Operadores responsáveis pela projeção de slides
- Ministérios de louvor
- Igrejas de pequeno, médio e grande porte
- Organizadores de eventos

## Objetivos

O objetivo geral é desenvolver uma plataforma web que facilite e agilize a criação de apresentações de slides para uso em cultos e eventos religiosos.

- Reduzir o tempo necessário para criar uma apresentação
- Facilitar a inserção e a organização de letras musicais
- Disponibilizar templates de slides prontos
- Armazenar as apresentações criadas pelo usuário
- Melhorar a organização e a produtividade das equipes

## Escopo

### Primeira versão

- Criação de apresentações
- Inserção de letras através de uma caixa de texto
- Escolha manual de templates
- Seleção automática de template
- Visualização da apresentação gerada
- Edição básica dos slides
- Salvamento das apresentações

### Funcionalidades futuras

- Biblioteca pública de apresentações
- Compartilhamento de slides entre usuários
- Publicação de templates criados pela comunidade
- Busca por apresentações já criadas
- Exportação para PowerPoint e PDF

## Stack tecnológica

### Definido

- Banco de dados, autenticação e armazenamento com Supabase
- Hospedagem do frontend na Vercel
- Apoio de IA no desenvolvimento com Claude, Codex e Grok

### A definir

- Linguagem de programação
- Framework do frontend
- Biblioteca de estilos e componentes
- Ferramenta de testes automatizados

Todo código gerado com apoio de IA passa por revisão humana antes do merge. Nenhuma credencial ou dado real de usuário é enviado para esses assistentes.

## Fluxo de trabalho

O projeto usa duas branches fixas.

| Branch | Uso |
| --- | --- |
| `main` | Produção, protegida e sempre estável |
| `dev` | Desenvolvimento e testes, recebe o trabalho do time |

### Ciclo de contribuição

1. Atualize a `dev` antes de começar
2. Faça commits pequenos e descritivos na `dev`
3. Teste no deploy de preview gerado pela Vercel
4. Envie para a `main` somente quando a versão estiver estável e validada pelo time

## Metodologia

O time trabalha com Scrum adaptado ao calendário da disciplina, em sprints de duas semanas, com daily assíncrona no grupo e revisão ao fim de cada sprint. As tarefas ficam registradas em issues e organizadas no GitHub Projects.

## Equipe

| Integrante | Função |
| --- | --- |
| Matheus Gabriel | Scrum e Backend |
| João Guilherme | Scrum, Backend e Aplicação Web |
| João Renato | Design e criação da marca |
| Tallyson | Frontend |

## Roadmap

| Etapa | Situação |
| --- | --- |
| Definição de escopo e requisitos | Concluído |
| Escolha da linguagem e do framework | Em andamento |
| Identidade visual e protótipo de interface | Em andamento |
| Modelagem do banco no Supabase | Planejado |
| Motor de geração de slides | Planejado |
| Autenticação e salvamento de apresentações | Planejado |
| Deploy da primeira versão na Vercel | Planejado |
| Biblioteca pública e compartilhamento | Planejado |
