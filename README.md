# HANDS-ON #01 | Git e GitHub no Visual Studio 2026

**Ponto de Conhecimento Tecnológico**

*Explorar · Experimentar · Aprender · Partilhar*

## Sobre o projeto

Este repositório contém um exercício prático de introdução ao controlo de versões com **Git e GitHub**, utilizando o **Visual Studio 2026**, **C#** e **.NET 10**.

O objetivo é demonstrar o ciclo de desenvolvimento desde a criação de um projeto local até à publicação e sincronização das alterações num repositório remoto.

## Tecnologias utilizadas

- Visual Studio 2026
- C# / .NET 10
- Git
- GitHub
- Developer PowerShell

## Conceitos abordados

| Conceito | Descrição |
|---|---|
| Repositório local | Espaço onde o Git gere o código e o histórico de versões |
| `.gitignore` | Define ficheiros e pastas não rastreados que devem ser ignorados |
| Working tree | Ficheiros de trabalho e respetivas alterações locais |
| Git Diff | Comparação entre versões de ficheiros |
| Staging area | Área de preparação das alterações para commit |
| Commit | Registo de uma versão no histórico local |
| Branch | Linha de desenvolvimento do projeto |
| Remote | Ligação a um repositório remoto |
| Push | Envio de commits locais para o remoto |

## Exercício prático

### 1. Criar o projeto

Criar uma aplicação **Console App (C#)** no Visual Studio 2026, com o nome `GitHubHandsOnDemo`, utilizando .NET 10.

### 2. Inicializar o Git

No Visual Studio, aceder a **Git → Create Git Repository** e inicializar um repositório local.

Verificar a existência do ficheiro `.gitignore` e das regras de exclusão de ficheiros temporários e resultados de compilação.

### 3. Modificar o código

Editar o ficheiro `Program.cs`, substituindo a mensagem inicial por uma apresentação do tutorial.

### 4. Analisar as alterações

Na janela **Git Changes**, utilizar a comparação de versões para identificar as linhas adicionadas, modificadas ou removidas.

### 5. Preparar e registar alterações

Adicionar `Program.cs` à *staging area* e criar um commit com a mensagem:

`feat: adicionar apresentação inicial do tutorial Git`

### 6. Associar o GitHub

Criar um repositório remoto vazio e associá-lo ao projeto local:

`git remote add origin https://github.com/FgAraujo-web/GitHubHandsOnDemo.git`

Confirmar a configuração:

`git remote -v`

### 7. Publicar a primeira versão

Verificar o estado do repositório:

`git status`

Publicar a branch local:

`git push -u origin master`

### 8. Evoluir o projeto

Adicionar novas instruções ao `Program.cs`, consultar o Git Diff e criar outro commit:

`feat: adicionar segunda versão da aplicação`

Sincronizar com o GitHub:

`git push`

## Fluxo de trabalho

**Alterar código → Git Diff → Stage → Commit → Push**

Este fluxo permite acompanhar a evolução do projeto, rever alterações antes de as registar e manter o repositório remoto atualizado.

## Executar o projeto

1. Clonar o repositório ou descarregar o código.
2. Abrir a solução no Visual Studio 2026.
3. Confirmar que o .NET 10 SDK está instalado.
4. Executar a aplicação com `Ctrl + F5`.

Em alternativa, na pasta do projeto, executar:

`dotnet run`

## Boas práticas

- Consultar o Git Diff antes de cada commit.
- Criar commits pequenos e com mensagens descritivas.
- Utilizar o `.gitignore` adequado à tecnologia.
- Evitar publicar credenciais, palavras-passe ou ficheiros sensíveis.
- Confirmar o estado do repositório com `git status`.
- Sincronizar regularmente o trabalho com o remoto.

## Repositório

[GitHubHandsOnDemo](https://github.com/FgAraujo-web/GitHubHandsOnDemo)

## Tutorial completo em PDF

O guia técnico inclui explicações passo a passo,
capturas reais do Visual Studio 2026 e os comandos
utilizados durante o exercício.

📘 [Consultar o tutorial completo em PDF](docs/HANDS_ON_01_Git_GitHub_Visual_Studio_2026.pdf)

---

**Ponto de Conhecimento Tecnológico | HANDS-ON**

*Explorar · Experimentar · Aprender · Partilhar*