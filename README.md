## Debug Library

Debug Library é uma aplicação fullstack desenvolvida com foco em produtividade, organização e colaboração para desenvolvedores(as). A plataforma permite fazer o cadastro do usuário e criar sua lista de livros personalizados com base em suas avaliacoes.

## Tecnologias Utilizadas

Frontend

- **Vite** – Build tool ultra rápido.

- **React** – Biblioteca JavaScript para interfaces modernas.

- **Typescript** – Superset de JavaScript tipado.

**TailwindCSS** – Framework utilitário de CSS.


## Backend

A critério da equipe

## Metodologias Ágeis e Ferramenta Utilizada
Kanban e Jira

## Gitflow – Como colaboramos no Debug Library

Adotamos o modelo de Gitflow para garantir uma organização eficiente e colaborativa no desenvolvimento.

## Fluxo de Branches

**main** – Contém a versão estável e pronta para produção.

**develop** – Branch de desenvolvimento contínuo. Todas as features são integradas aqui antes de ir para produção.

**feature/<nome>** – Para desenvolver novas funcionalidades.

**fix/<nome>** – Correções de bugs identificados.

**hotfix/<nome>** – Correções urgentes diretamente na produção.

**release/<versão>** – Preparação para uma nova versão de release.


## Exemplo prático:

1. Criar uma nova funcionalidade:

```git checkout develop```
```git pull```
```git checkout -b feature/cadastro-snippets```

Faça os commits normalmente e, ao finalizar:

```git push origin feature/cadastro-snippets```

Abra um Pull Request da sua branch para develop.

2. Corrigir um bug:

```git checkout develop```
```git checkout -b fix/snippets-carregamento```


3. Lançar uma nova versão: Após aprovação e merge de features na develop:

```git checkout -b release/v1.0.0```

Realize os testes finais e abra um PR para main.

## Regras de Contribuição

Sempre crie uma branch a partir de develop.

Commits devem ser claros e descritivos. Exemplo:

- **feat:** adiciona formulário de criação de snippet
- **fix:** corrige bug ao carregar biblioteca salva

Abra Pull Requests com descrições completas e solicite revisão.

Revise e teste sua funcionalidade antes de submeter.

## Rodando o Projeto

Em breve será disponibilizado um guia passo a passo com os comandos para rodar localmente o ambiente de desenvolvimento.
