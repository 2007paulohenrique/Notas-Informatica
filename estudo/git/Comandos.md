# Comandos do Git

Abaixo estão listados os principais comandos do Git.

## Comandos Básicos

- **`git init`** - Inicializa um novo repositório Git no diretório atual.
  
- **`git clone <url>`** - Clona um repositório remoto para o diretório local.

- **`git add <arquivo>`** - Adiciona um arquivo ou conjunto de arquivos ao "staging area" (preparação para commit).
- **`git add .`** - Adiciona todos os arquivo alterados ao staging area.

- **`git commit -m "<mensagem>"`** - Cria um commit com as alterações no "staging area" e adiciona uma mensagem descritiva.

- **`git status`** - Mostra o status atual do repositório, incluindo arquivos modificados, adicionados e prontos para commit.

- **`git log`** - Exibe o histórico de commits no repositório.

- **`git diff`** - Mostra as diferenças entre o código modificado e o último commit ou entre branches.

## Gerenciamento de Branches

- **`git branch`** - Lista as branches existentes no repositório e indica a branch atual.

- **`git branch <nome-da-branch>`** - Cria uma nova branch.

- **`git checkout <nome-da-branch>`** - Muda para outra branch.

- **`git checkout -b <nome-da-branch>`** - Cria e muda para uma nova branch.

- **`git merge <nome-da-branch>`** - Mescla uma branch na branch atual.

## Sincronização com Repositórios Remotos

- **`git pull`** - Atualiza o repositório local com as alterações do repositório remoto.

- **`git push origin <branch>`** - Envia os commits da branch local para o repositório remoto.

- **`git remote add origin <url>`** - Define um repositório remoto (normalmente na primeira vez que um repositório local é conectado a um remoto).

- **`git fetch`** - Baixa alterações do repositório remoto, mas não as aplica automaticamente ao seu repositório local.