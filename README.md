# Documentação Python

## Funções embutidas

- `len(prt)` -> "prt" pode ser uma string ou uma lista, a função len irá retornar seu comprimento/tamanho.

## String

### Métodos
- `str.upper()` -> Deixa tudo maiúsculo.
- `str.lower()` -> Deixa tudo minúsculo.
- `str.capitalize()` -> Primeira letra maiúscula.
- `str.lstrip()` -> elimina espaços ao lado esquerdo.
- `str.rstrip()` -> elimina espaços ao lado direito.
- `str.strip()` -> elimina espaços de ambos os lados.

## Lista

### Observações

1. Passando um número negativo, irá retornar elementos a partir do último index.
2. Passando `[indexInicial:indexFinal]` irá pegar o intervalo desses elementos (ambos estarão inclusos).

### Métodos

- `lista.count(prt)` -> "prt" é o valor a ser achado, verifica o parâmetro e retorna quantas vezes aparece na lista.
- `lista.clear()` -> Limpa a lista.
- `lista.index(prt)` -> "prt" é o valor a ser achado, verifica o parâmetro e retorna o index se existir na lista.
- `lista.append(prt)` -> "prt" é o valor a ser adicionado, verifica o parâmetro e adiciona ao final da lista.
  
