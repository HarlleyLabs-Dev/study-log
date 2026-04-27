# Study Log

O que aprendo todo dia.

---

## 2026-04-25

- Criei minha conta no GitHub
- Aprendi o que Ã© repositÃ³rio, README e commit
- Entendi por que o GitHub Ã© importante para conseguir trabalho

---

## 2026-04-26 â€” Calculadora Pessoal

Primeiro programa completo que fiz sozinho.

### CÃ³digo

```portugol
programa {
  cadeia Nome
  inteiro Soma, N1, N2

  funcao inicio() {
    escreva("Digite seu nome:")
    leia(Nome)
    escreva("Seja bem vindo(a) ", Nome, ", a sua calculadora pessoal!\n")
    escreva("Digite um numero: ")
    leia(N1)
    escreva("Digite outro numero: ")
    leia(N2)
    Soma = N1 + N2
    escreva("A soma de ", N1, "+", N2, " = ", Soma)
  }
}
```

### O que aprendi
- cadeia guarda texto, inteiro guarda nÃºmero sem vÃ­rgula
- leia() pega o que o usuÃ¡rio digita e guarda na variÃ¡vel
- variÃ¡veis declaradas fora da funÃ§Ã£o funcionam dentro dela
- vÃ­rgula dentro do escreva() mistura texto com nÃºmero sem erro
- Soma recebe o resultado de N1 + N2 igual na matemÃ¡tica

### Hoje eu consegui
- Fazer meu primeiro programa completo sozinho

---

## 2026-04-27 â€” Operadores Relacionais e LÃ³gicos

### O que aprendi
- Operadores relacionais: comparam dois valores e retornam verdadeiro ou falso
- Operadores lÃ³gicos:
  - E: os dois precisam ser verdadeiros
  - OU: basta um ser verdadeiro
  - NAO: inverte o resultado
- DiferenÃ§a entre = e ==:
  - = guarda valor na variÃ¡vel
  - == compara dois valores

### CÃ³digo do dia

```portugol
programa {
  inteiro A, B, C

  funcao inicio() {
    A <- 2
    B <- 3
    C <- 5
    escreva((A == B) ou (C > A))
  }
}
```

### Hoje eu consegui
- Entender que (A==B) ou (C>A) dÃ¡ verdadeiro porque C>A Ã© verdadeiro
- Descobrir que faltava == no lugar de = para comparar valores
