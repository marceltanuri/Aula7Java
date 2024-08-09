# Exercicio de Programação: Calcula Aprovação do Aluno

## Descrição

Implemente uma função `calculaAprovacao` em Java que receba três notas de um aluno, calcule a média ponderada dessas notas e determine se o aluno foi aprovado ou reprovado. A função deve retornar uma string indicando o resultado.

### Regras de Negócio

- A função deve receber três notas (`nota1`, `nota2`, `nota3`) como valores `double`.
- As notas possuem pesos diferentes: `nota1` tem peso 2, `nota2` tem peso 3, e `nota3` tem peso 5.
- A média ponderada deve ser calculada da seguinte forma:

  \[
  \text{Média Ponderada} = \frac{\text{nota1} \times 2 + \text{nota2} \times 3 + \text{nota3} \times 5}{10}
  \]

- Se a média ponderada for maior ou igual a 7.0, o aluno é considerado **aprovado**.
- Se a média ponderada for menor que 7.0, o aluno é considerado **reprovado**.

### Retorno

- Se o aluno for aprovado, a função deve retornar a string: `Aluno aprovado com a nota X`, onde `X` é a média ponderada.
- Se o aluno for reprovado, a função deve retornar a string: `Aluno reprovado com a nota Y`, onde `Y` é a média ponderada.

## Exemplo de Entrada e Saída

### Exemplo 1

**Entrada:**
```java
calculaAprovacao(7.0, 8.0, 9.0);
```

**Saída:**
```
"Aluno aprovado com a nota 8.0"
```

### Exemplo 2

**Entrada:**
```java
calculaAprovacao(5.0, 6.0, 7.0);
```

**Saída:**
```
"Aluno reprovado com a nota 6.2"
```
### Exemplo 3

**Entrada:**
```java
calculaAprovacao(10.0, 10.0, 10.0);
```

**Saída:**
```
"Aluno aprovado com a nota 10.0"
```

## Tarefa
Implemente a função calculaAprovacao de forma que todos os casos de teste sejam aprovados.

```java
public class Solution {
    public static String calculaAprovacao(double nota1, double nota2, double nota3) {
        // Calcule a média ponderada e retorne a String adequada.
        return "";
    }
}
```


