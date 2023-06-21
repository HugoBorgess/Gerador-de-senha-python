# Gerador de Senhas

Este é um script simples em Python que gera senhas aleatórias com base em diferentes conjuntos de caracteres. O tamanho da senha, bem como a composição dos caracteres, podem ser personalizados de acordo com as necessidades.

## Requisitos

- Python 3.x

## Utilização

1. Execute o script em um ambiente Python.
2. Será solicitado que você insira o tamanho da senha desejada.
3. O script irá gerar uma senha aleatória com base nos critérios estabelecidos.
4. A senha será exibida na saída do terminal.

## Personalização

O script permite a personalização da composição dos caracteres da senha. Os conjuntos de caracteres utilizados são:

- Letras do alfabeto: `abcdefghijklmnopqrstuvwxyz`
- Números: `0123456789`
- Caracteres especiais: `@#$%&*`

Você pode ajustar o tamanho de cada conjunto de caracteres modificando as variáveis `alpha_len`, `num_len` e `special_len`. Além disso, você pode adicionar ou remover caracteres desses conjuntos para atender às suas preferências.

## Exemplo

Aqui está um exemplo de utilização do script:

```python
Qual o tamanho da senha? 12
Yz4#na7P%w9$
```

Neste exemplo, foi solicitada uma senha com tamanho 12. A senha gerada foi `Yz4#na7P%w9$`.

## Aviso

Este script tem fins educacionais e de demonstração. Ao utilizar senhas, é importante considerar as melhores práticas de segurança, como utilizar senhas complexas, não compartilhar senhas com outras pessoas e atualizá-las periodicamente.
