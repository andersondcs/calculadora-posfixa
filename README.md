# Calculadora Posfixa


## Objetivo
- Projetar testes uniários para uma terceira equipe implementar

## Problema
- Receber uma string contendo uma expressão matemática em [notação polonesa](https://pt.wikipedia.org/wiki/Nota%C3%A7%C3%A3o_polonesa) e retornar o valor de resultado da expressão.

- Exemplos
"3 2 5 + *" => 21

- [Calculadora online](https://epxx.co/ctb/hp12c.html)


## Atividades
- segunda-feira 25-09
   1. forkar este repositório
   1. atualizar README.md com
      - equipe (lembrar de colocar link para o github dos membros)
      - tecnologia usada
      - plano de teste (definir se vai usar top-down ou bottom-up)
      - como executar teste
   1. apresentar em sala o plano de teste
- quinta-feira 28-09
   1. sortear repositório e equipe
   1. forkar repositório
   1. desenvolver solução para os testes
   1. apresentar plano de teste e solução
   
## Resolução
- parte 1
   Equipe: Anderson e Kaynara (https://github.com/andersondcs/calculadora-posfixa)
   Tecnologia: Python
   Plano de teste:
   | Entrada  | Condição | Classes Válidas | Classes Inválidas |
   | ------------- | ------------- | ------------- | ------------- |
   | expressao | Expressão é do tipo string | tipo(expressao) == string | tipo(expressao) != string |
   || String da expressão de tamanho impar | len(expressao) % 2 == 1 | len(expressao) % 2 == 0 |
   |||||
   |||||
