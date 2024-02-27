# curso-python

Este é um exercício de correção de erros em um programa Python que calcula a média dos valores digitados pelo usuário.

## Erros Corrigidos

1. **Erro com a palavra-chave `False`:**
   - A palavra-chave `false` (com "f" minúsculo) foi substituída por `False` (com "F" maiúsculo) para representar corretamente o valor booleano falso em Python.

2. **Falta de retorno da média:**
   - Adicionou-se uma declaração de retorno na função `calcular_media` para retornar a média calculada para ser utilizada no programa principal.

3. **Ausência de uso de `len` e `sum` para calcular a média:**
   - Substituiu-se o loop `for` na função `calcular_media` pelo uso das funções embutidas `len` e `sum` para calcular o tamanho da lista e a soma de seus elementos, respectivamente.

4. **Falta de um bloco `else` para adicionar valores à lista:**
   - Adicionou-se um bloco `else` que adiciona os valores à lista `valores` sempre que um valor válido é digitado pelo usuário, garantindo que os valores sejam armazenados para calcular a média posteriormente.
