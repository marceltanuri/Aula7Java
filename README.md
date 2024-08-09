# Exercicio de Programação: Calcula Aprovação do Aluno

## Descrição

Implemente uma função `calculaAprovacao` em Java que receba três notas de um aluno, calcule a média ponderada dessas notas e determine se o aluno foi aprovado ou reprovado. A função deve retornar uma string indicando o resultado.

### Regras de Negócio

- A função deve receber três notas e seus respectivos pesos (`nota1`, `nota2`, `nota3`, `peso1`, `peso2`, `peso3`) como valores `double`.
- A média ponderada deve ser calculada da seguinte forma: Multiplicar cada nota pelo seu respectivo peso e somar todos os resultados. Depois, essa soma é dividida pela soma dos pesos.


- Se a média ponderada for maior ou igual a 7.0, o aluno é considerado **aprovado**.
- Se a média ponderada for menor que 7.0, o aluno é considerado **reprovado**.

### Retorno

- Se o aluno for aprovado, a função deve retornar a string: `Aluno aprovado com a nota X`, onde `X` é a média ponderada.
- Se o aluno for reprovado, a função deve retornar a string: `Aluno reprovado com a nota Y`, onde `Y` é a média ponderada.

## Exemplo de Entrada e Saída

### Exemplo 1

```java 
"input": {
                "nota1": 7.0,
                "nota2": 8.0,
                "nota3": 9.0,
                "peso1": 2.0,
                "peso2": 3.0,
                "peso3": 5.0
            },
            "expected": "Aluno aprovado com a nota 8.3"
```


### Exemplo 2


```java
"input": {
                "nota1": 5.0,
                "nota2": 6.0,
                "nota3": 7.0,
                "peso1": 2.0,
                "peso2": 3.0,
                "peso3": 4.0
            },
            "expected": "Aluno reprovado com a nota 6.1"
```

## Tarefa
Implemente a função calculaAprovacao de forma que todos os casos de teste sejam aprovados.

```java
public class Solution {
    public static String calculaAprovacao(double nota1, double nota2, double nota3, double peso1, double peso2, double peso3) {
        // Calcule a média ponderada e retorne a String adequada.
        return "";
    }
}
```


