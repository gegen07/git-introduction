## Git Commands

### Criar, Modificar, salvar
- git init
- git add *.c
- git commit -m "commit inicial"
  - git commit -a -m "commit inicial"

### Copiar Repositorio
- git clone <https://github.com/libgit2/libgit2> <home_nome_diretorio>

### Verificar status de arquivos
- git status

### Verificar o que foi mudado
- git diff

### Ver o que já foi mudado
- git log
- git log --pretty

## Refazendo
- git commit --amend
- git reset HEAD <file> (staged <-> working directory)