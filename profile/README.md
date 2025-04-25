## Debug Library 🪲

Debug Library é uma aplicação fullstack desenvolvida com foco em produtividade, organização e colaboração para desenvolvedores(as). A plataforma permite cadastrar, fazer login e adicionar livros na lista personalizada com base em suas avaliações.

## Tecnologias Utilizadas

### Frontend

- **Vite** – Build tool ultra rápido.
- **React** – Biblioteca JavaScript para interfaces modernas.
- **Typescript** - Superset de JavaScript tipado.
- **TailwindCSS** – Framework utilitário de CSS.

### Backend

A definir

## Gitflow – Como colaboramos no Debug Library

Adotamos o modelo de Gitflow para garantir uma organização eficiente e colaborativa no desenvolvimento.

## Fluxo de Branches

- **main** – Contém a versão estável e pronta para produção.

- **develop** – Branch de desenvolvimento contínuo. Todas as features são integradas aqui antes de ir para produção.

- **feature/<nome>** – Para desenvolver novas funcionalidades.

- **fix/<nome>** – Correções de bugs identificados.

- **hotfix/<nome>** – Correções urgentes diretamente na produção.

- **release/<versão>** – Preparação para uma nova versão de release.

> ⚠️ **Importante:**  
> Não se esqueça de criar a branch `develop` localmente em sua máquina para poder seguir com o fluxo do Gitflow:

```git checkout -b develop origin/develop```

## Exemplo prático:

1. Criar uma nova funcionalidade:

- ```git checkout develop```
- ```git pull```
- ```git checkout -b feature/cadastro-snippets```

Faça os commits normalmente e, ao finalizar:

```git push origin feature/cadastro-snippets```

Abra um Pull Request da sua branch para develop.

2. Corrigir um bug:

- ```git checkout develop```
- ```git checkout -b fix/snippets-carregamento```

3. Lançar uma nova versão: Após aprovação e merge de features na develop:

- ```git checkout -b release/v1.0.0```

Realize os testes finais e abra um PR para main.

## Regras de Contribuição

Sempre crie uma branch a partir de develop.

Commits devem ser claros e descritivos. Exemplo:

- **feat:** adiciona formulário de criação de snippet
- **fix:** corrige bug ao carregar biblioteca salva

Abra Pull Requests com descrições completas e solicite revisão.

Revise e teste sua funcionalidade antes de submeter.

## Rodando o Projeto
Siga os passos abaixo para clonar e rodar o projeto localmente:

1. Clone o repositório
   
- ```git clone https://github.com/seu-usuario/debug-library-frontend.git```

3. Acesse a pasta do projeto
   
- ```cd debug-library```

4. Instale as dependências
   
- ```npm install```

6. Inicie o servidor de desenvolvimento
   
- ```npm run dev```

8. Acesse no navegador

Abra o navegador e vá até:
- ```http://localhost:5173```

O Vite, por padrão, utiliza a porta 5173. Se estiver diferente, o terminal mostrará a porta correta após rodar ```npm run dev```

## 👥 Integrantes

- **Alice Lavínia**  
  ![GitHub](https://img.shields.io/badge/GitHub-AliceLavinia-181717?style=flat-square&logo=github&logoColor=white&labelColor=gray)  
  Cargo: **Desenvolvedora Full-Stack & UI/UX Designer** 👩🏻‍💻🎨

- **Guilherme Gonzaga**  
  ![GitHub](https://img.shields.io/badge/GitHub-Balko596-181717?style=flat-square&logo=github&logoColor=white&labelColor=gray)  
  Cargo: **Desenvolvedor Full-Stack & UI/UX Designer** 👨🏻‍💻🎨

- **Gabriel Ávila**  
  ![GitHub](https://img.shields.io/badge/GitHub-gabriel--avila--27-181717?style=flat-square&logo=github&logoColor=white&labelColor=gray)  
  Cargo: **Desenvolvedor Full-Stack** 👨🏻‍💻

- **Ivanildo Marques**  
  Cargo: **UI/UX Designer** 🎨

- **Maria de Fátima**  
  ![GitHub](https://img.shields.io/badge/GitHub-alvesmariadefatima-181717?style=flat-square&logo=github&logoColor=white&labelColor=gray)  
  Cargo: **Tech Lead & Desenvolvedora Frontend** 👩🏻‍💻
