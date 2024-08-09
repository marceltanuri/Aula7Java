# Exercicio de Programação: Calcula Aprovação do Aluno

## Descrição

Implemente uma função `calculaAprovacao` em Java que receba três notas de um aluno, os respectivos pesos dessas notas, calcule a média ponderada e classifique o aluno em uma das seis categorias abaixo. A função deve retornar uma string indicando a classificação e a média.

### Regras de Negócio

- A função deve receber três notas e seus respectivos pesos (`nota1`, `nota2`, `nota3`, `peso1`, `peso2`, `peso3`) como valores `double`.
- A média ponderada deve ser calculada da seguinte forma: Multiplicar cada nota pelo seu respectivo peso e somar todos os resultados. Depois, essa soma é dividida pela soma dos pesos.

### Classificações

- **Nota >= 9.0:** "Aluno excelente com a nota X"
- **8.0 <= Nota < 9.0:** "Aluno muito bom com a nota X"
- **7.0 <= Nota < 8.0:** "Aluno bom com a nota X"
- **6.0 <= Nota < 7.0:** "Aluno mediano com a nota X"
- **5.0 <= Nota < 6.0:** "Aluno em recuperação com a nota X"
- **Nota < 5.0:** "Aluno reprovado com a nota X"

### Retorno

- Se o aluno for aprovado, a função deve retornar a string: `Aluno aprovado com a nota X`, onde `X` é a média ponderada.
- Se o aluno for reprovado, a função deve retornar a string: `Aluno reprovado com a nota Y`, onde `Y` é a média ponderada.

## Exemplo de Entrada e Saída

### Exemplo 1

```java 
 "input": {
                "nota1": 9.0,
                "nota2": 9.5,
                "nota3": 10.0,
                "peso1": 2.0,
                "peso2": 3.0,
                "peso3": 5.0
            },
            "expected": "Aluno excelente com a nota 9.6"
```


### Exemplo 2


```java
"input": {
                "nota1": 7.0,
                "nota2": 8.0,
                "nota3": 7.5,
                "peso1": 2.0,
                "peso2": 3.0,
                "peso3": 5.0
            },
            "expected": "Aluno muito bom com a nota 7.7"
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


Para testar, coloque o conteúdo do arquivo tests.json nessa página: https://sandbox-playground.ada.tech/blackbox
