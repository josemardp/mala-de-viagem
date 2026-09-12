# Mala de Viagem

Calculadora de mala do Josemar. Você diz quantos dias, manhãs, tardes e noites vai
passar fora de casa, e a página monta a lista de roupa, remédio, documento e
higiene com a quantidade certa de cada item.

## Regras de roupa

- Camiseta de sair: 1 por noite, mais 1 pensando na saída do dia da volta
- Camiseta de ficar em casa: 1 por dia
- Cueca: 2 por dia, mais 1 de reserva
- Meia branca: 2 por dia
- Pijama: 1 a cada 2 dias
- Calça tectel, calça jeans, tênis, chinelo Havaianas e cinta: 1 de cada, fixo

A reserva de cueca e o +1 de camiseta de sair só entram se a viagem tiver pelo
menos 1 dia ou 1 noite (viagem em branco não gera item).

## Remédio

A lista de remédio **não fica no código**. Quem usa cadastra na própria página, no
bloco "Meus remédios", e a lista é guardada só no `localStorage` daquele navegador.

Isso é de propósito. Nome e dose de medicamento são dado de saúde: não entram em
arquivo versionado nem em site publicado. Como a lista vive no navegador, a
ferramenta funciona igual e o repositório pode ser público sem expor ninguém.

Consequências práticas:

- Cada navegador tem a própria lista. Trocar de aparelho pede cadastrar de novo.
- Limpar os dados do site apaga a lista.
- O grupo "Remédio" da mala só aparece depois que existe pelo menos um cadastro.

## Publicado em

https://josemardp.github.io/mala-de-viagem/

Site estático, sem build. Só abrir o `index.html` já funciona local também.
