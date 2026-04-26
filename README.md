# Study Log

O que aprendo todo dia.

---

## 2026-04-25

- Criei minha conta no GitHub
- Aprendi o que é repositório, README e commit
- Entendi por que o GitHub é importante para conseguir trabalho
 
## 2026-04-26 — Calculadora Pessoal

Primeiro programa completo que fiz sozinho.
Aprendi: variáveis, entrada de dados, soma e saída formatada.

### Código

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
    escreva("A soma de ", N1, "+", N2, "=", Soma)
  }
}

### O que aprendi

- cadeia guarda texto, inteiro guarda número sem vírgula
- leia() pega o que o usuário digita e guarda na variável
- variáveis declaradas fora da função funcionam dentro dela
- vírgula dentro do escreva() mistura texto com número sem erro
- Soma recebe o resultado de N1 + N2 igual na matemática
