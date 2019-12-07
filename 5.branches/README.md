## Git branches

1. Estou trabalhando numa nova feature para o projeto.
2. Crio o projeto git, mas não acabei de testar a feature, posso ainda achar bugs, ou seja, não posso enviar para a produção.
3. Chega uma mensagem do cliente e fala que achou um bug crítico

E agora? Crio um novo commit? É a melhor alternativa?

1. Crio uma nova branch, uma ramificação, de onde eu parei e conserto o bug, depois de consertado, dá um merge na branch da nova feature.

Porém a master tem modificações sem estar no estágio de staged, podendo gerar conflito, o Git não te deixará fazer isso.

- Fast forward

## Git Merge

- Conflito

## Git Stashing e Celaning
- Imagina que você está trabalhando em uma branch e quer passar para outra feature. No entanto, você não quer dar commit em um trabalho não acabado.

- Usa uma pilha para salvar arquivos modified e não os adiciona ao repository