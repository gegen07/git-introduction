## Imagens, Não Diferenças
- Snapshots

![snapshots](snapshots.png)
- Offline
  - Exempplo: está dentro do avião
- Geralmente adiciona-se dados, porém você pode perder os arquivos que não estão dentro dessa imagem.

## Três Estados
- Committed
  - Arquivos estão armazedos de forma segura no banco de dados
- Modified
 - Arquivos alterados, porém não foram adicionados ao banco de dados
- Staged
  - Arquivos que foram alterados estão marcados para o estado de committed

![stages](areas.png) 

- OBS.: o .git armazena metadados e o banco de dados do projeto.

### Fluxo Básico
1. Você modifica arquivos no seu diretório de trabalho.
2. Você prepara os arquivos, adicionando imagens deles à sua área de preparo.
3. Você compromete, o que leva os arquivos como eles são na área de preparo e armazena essa imagens de forma permanente para o diretório do Git. 