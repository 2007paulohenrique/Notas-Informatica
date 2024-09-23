# Controle de Versão

Controle de versão é um sistema que registra as alterações feitas em arquivos ao longo do tempo, permitindo que você retorne a versões anteriores quando necessário. É uma prática fundamental no desenvolvimento de software, mas também pode ser aplicada a qualquer tipo de arquivo digital.

## Importância do Controle de Versão

1. **Histórico de Alterações**: Permite acompanhar as modificações feitas no código, facilitando a identificação de quando e onde um problema surgiu.
2. **Colaboração**: Permite que múltiplos desenvolvedores trabalhem em um projeto simultaneamente sem interferir no trabalho dos outros.
3. **Recuperação de Dados**: Facilita a recuperação de versões anteriores em caso de erro ou perda de dados.
4. **Branching e Merging**: Permite experimentar novas funcionalidades em branches separadas e mesclar essas alterações ao projeto principal quando estiverem prontas.
5. **Documentação**: Cada commit pode incluir mensagens descritivas, documentando a razão das mudanças.

## Conceitos

1. **Repositório (Repo)**: É um local onde todos os arquivos do projeto e seu histórico de versões são armazenados. Pode ser local (no seu computador) ou remoto (na nuvem, como no GitHub).
2. **Commit**: Uma marcação do estado atual do projeto em um determinado momento. Cada commit deve ter uma mensagem descritiva que explique as alterações realizadas.
3. **Branch**: Uma linha de desenvolvimento paralela que permite trabalhar em novas funcionalidades sem afetar o código principal (geralmente na branch main ou master).
4. **Merge**: O ato de unir alterações de uma branch a outra. Isso é feito quando uma funcionalidade foi completada e testada.
5. **Pull Request (PR)**: Uma solicitação para mesclar alterações de uma branch em outra, frequentemente usada em ambientes colaborativos. O PR permite revisões e comentários antes da fusão.
6. **Clone**: Uma cópia local de um repositório remoto. Você pode clonar um repositório para trabalhar em seu próprio ambiente.
7. **Fork**: Uma cópia de um repositório que permite que você faça alterações sem afetar o repositório original. Comumente usado em projetos open-source.
8. **Push**: Envia suas alterações locais para o repositório remoto.
9. **Pull**: Baixa as alterações do repositório remoto para seu repositório local.
10. **Staging Area (Área de Preparação)**: Uma área intermediária onde você pode preparar alterações para um commit. Permite selecionar quais alterações incluir no próximo commit.

## Fluxo de Trabalho

1. **Clonar o Repositório**: Baixar o repositório remoto para o seu computador com o comando `git clone url_repo_remoto`.
2. **Criar uma Branch**: Para desenvolver uma nova funcionalidade ou corrigir um bug. Use o comando `git branch nome-da-nova-branch` para criar uma branch. Para mudar para a branch criada, use `git checkout nome-da-nova-branch`, ou digite o comando `git checkout -b nome-da-nova-branch` para criar uma branch e mudar para ela automaticamente.
3. **Fazer Alterações**: Modificar os arquivos conforme necessário.
4. **Adicionar ao Staging Area**: Preparar as alterações para commit usando o comando git add. Use `git add .` para adicionar todas as alterações ao commit ou `git add nome-do-arquivo` para adicionar as alterações feitas em um arquivo específico.
5. **Fazer um Commit**: Registrar suas alterações com uma mensagem descritiva usando o comando `git commit -m "mensagem"`.
6. **Fazer Push**: Enviar suas alterações para o repositório remoto usando `git push origin nova-branch`.
7. **Criar um Pull Request**: Solicitar a revisão e mesclagem das suas alterações na branch principal.
8. **Fazer Merge**: Integrar suas alterações após a revisão.