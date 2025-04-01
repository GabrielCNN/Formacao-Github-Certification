# Introdução aos Conceitos de Git e GitHub

Este documento registra meu aprendizado sobre Git e GitHub, fornecido como um guia para quem está começando a utilizar essas ferramentas essenciais no desenvolvimento de software.

## O que aprendi até aqui

Até o momento, aprendi conceitos fundamentais sobre GitHub, incluindo:

✅ A importância do GitHub para o desenvolvimento colaborativo.

✅ Como clonar repositórios do GitHub para minha máquina local.

✅ Crie chaves SSH e tokens de acesso para aumentar a segurança.

✅ Inicie um repositório local e conecte-se ao GitHub.

Além disso, já estou utilizando vários comandos para gerenciar repositórios e versionamento de código.


<details>
<summary>Nova Branch</summary>

:computer: [(git branch versao_01) Criar uma nova branch para alterar os arquivos, depois realiza um Merge com a branch padr"ao (main)]
:computer: (git checkout nome_da_branch) Para entrar na branch criada
:computer: (git checkout merge nome_da_branch) Quando selecionar a branch main, rodar o comando merge para incluir alteração realizada

</details>

## Principais comandos do Git

### Configuração Inicial



| Comando   |  Descrição                           |
| :---------- |  :---------------------------------- |
| `git config --list` | Exiba as configurações atuais do usuário no Git. |
| `git config --global user.name "Seu Nome"` | Definir o nome do usuário globalmente. |
| `git config --global user.email "seu@email.com"` | Definir o e-mail do usuário globalmente. |
| `ssh-keygen` | Gere uma chave SSH para autenticação sem precisar digitar usuário e senha em cada commit. |
| `Configuração de autenticação de dois fatores (2FA) ` | Habilita mais segurança na conta do GitHub. |

### Manipulação de Repositórios

| Comando   |  Descrição                           |
| :---------- |  :---------------------------------- |
| `git init` | Inicializa um novo repositório Git localmente. |
| `git clone <URL do repositório>` | Clona um repositório remoto para uma máquina local. |
| `git remote set-url origin <URL>` | Configure ou altere a URL do repositório remoto. |

### Trabalhando com Arquivos e Commits

| Comando   |  Descrição                           |
| :---------- |  :---------------------------------- |
| `git add .` | Adicionadas todas as alterações para serem comprometidas. |
| `git commit -m "Mensagem do commit"` | Salvar as alterações com uma mensagem descritiva. |
| `git status` | Exibe o status das modificações no repositório. |
| `git tag -a v1.1 -m` | Controle de versão do arquivo no qual estou trabalhando. |

### Enviando modificações para o GitHub

| Comando   |  Descrição                           |
| :---------- |  :---------------------------------- |
| `git push origin main` | Envie as alterações para o repositório remoto na branch main. |
| `Merge` | Realiza o Merge da Branch secundária para Branch Main |
| `Fork` | Contribuir com projetos de terceiros, sem alterar o respositório origem |

### Navegação no Terminal

| Comando   |  Descrição                           |
| :---------- |  :---------------------------------- |
| `cd <nome_da_pasta>` | Acessa uma pasta específica no terminal. |