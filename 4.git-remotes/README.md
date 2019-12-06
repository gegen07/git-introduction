## Git Remotes
- Para habilitar a colaboração é necessário saber trabalhar com remotes.

- São versões de seu projeto que estão hospedados na internet ou rede.

- Colaborar se resume em push and pull em remotes.

## Remote Commands
- ```git remote``` 
- ```git remote -v```

## Adicionando Remotes
- ```git remote add origin https://github.com/schacon/ticgit.```

## Download de informações do remote
- ```git fetch origin```
  - Porém, o fetch não realiza o merge automaticamente, apenas faz o download para o repositório local.

- ```git pull <remote>```
  - Realiza o fetch e além disso realiza o merge.

- ```git push <remote> <branch>```
  - Realiza o upload das mudanças do estágio staged para a branch do remote.

## Renomear remotes
- ```git remote rename <remote> <newname>```

## Remover remotes
- ```git remote remove <remote>```
- ```git remote rm <remote>```
