## Imagens, Não Diferenças
- Snapshots

![snapshots](snapshots.png)
- Offline
  - Exemplo: está dentro do avião
- Geralmente adiciona-se dados, porém você pode perder os arquivos que não estão dentro dessa imagem.

## Três Estados
- Committed
  - Arquivos estão armazenados de forma segura no banco de dados
- Staged
  - Arquivos que foram alterados estão marcados para o estado de committed
- Modified
  - Arquivos alterados, porém não foram adicionados ao banco de dados

![stages](areas.png) 

- OBS.: o .git armazena metadados e o banco de dados do projeto.

### Fluxo Básico
1. Você modifica arquivos no seu diretório de trabalho.
2. Você prepara os arquivos, adicionando imagens deles à sua área de preparo.
3. Você compromete, o que leva os arquivos como eles são na área de preparo e armazena essa imagens de forma permanente para o diretório do Git. 

### Arquivo .gitignore
É um arquivo de blacklist, ou seja, qualquer nome de arquivo, extensão, algo do tipo que tiver no .gitignore, o git irá ignorar e não realizará as snapshots.

### Arquivo .gitkeep/.keep
O git não guarda informações de diretórios vazios, porém para guardar-los é necessário adicionar o .gitkeep dentro do diretório e o diretório estará salvo em uma snapshot.

- Vantagens: Guardar no banco de dados uma estrutura de diretórios antes de fazer qualquer alteração de código.