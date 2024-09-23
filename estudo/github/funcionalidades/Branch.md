# Branches

Uma Branch é uma ramificação no Git que permite que você trabalhe em diferentes linhas de desenvolvimento dentro do mesmo repositório. Branches são usadas para isolar novas funcionalidades, correções de bugs, ou qualquer outra mudança do código principal, sem afetar o estado do código em outras branches.

## Benefícios

- **Isolamento de Funcionalidades**: Permite trabalhar em uma nova funcionalidade sem interferir com o código principal.
- **Colaboração**: Facilita o trabalho colaborativo, pois cada desenvolvedor pode trabalhar em sua própria branch.
- **Controle de Versão**: Mantém um histórico organizado das mudanças, permitindo experimentar novas ideias sem comprometer a versão estável do projeto.
- **Revisão de Código**: Branches são essenciais para Pull Requests, que permitem a revisão do código antes de serem mescladas (merged) na branch principal.

## Tipos Comuns

1. **Main / Master**: A branch principal e estável do repositório, usada para releases de produção.
2. **Develop**: Usada para integrar funcionalidades antes de serem enviadas para a branch principal.
3. **Feature**: Criada para desenvolver novas funcionalidades ou melhorias específicas.
4. **Bugfix**: Usada para corrigir bugs ou problemas no código.
5. **Hotfix**: Criada para corrigir rapidamente problemas críticos na produção.

## Comandos Básicos no Git

1. Para criar uma nova branch:
`git branch nome-da-branch`

2. Mudar para a branch criada:
`git checkout nome-da-branch`

3. Criar e mudar automaticamente para uma branch:
`git checkout -b nome-da-branch`

4. Listar branches do repositório:
`git branch`

5. Renomear branch atual:
`git branch -m novo-nome-da-branch`

6. Deletar branch localmente:
`git branch -d nome-da-branch`

A manipulação de branches também pode ser feita manualmente no GitHub de forma intuitiva.

## Boas Práticas
- Use nomes que indiquem o propósito, como feature/login-system ou bugfix/fix-navbar.
- Mantenha Branches Pequenas e Focadas, pois pequenas mudanças são mais fáceis de revisar e mesclar.
- Sincronize sua branch com a principal regularmente para evitar conflitos complexos.
- Sempre revise o código e faça testes completos antes de mesclar uma branch na main.   
