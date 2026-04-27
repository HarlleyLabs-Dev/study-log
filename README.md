Copia esse texto todo de uma vez:

\# Study Log

O que aprendo todo dia.

\---

\## 2026-04-25

\- Criei minha conta no GitHub
\- Aprendi o que e repositorio, README e commit
\- Entendi por que o GitHub e importante para conseguir trabalho

\---

\## 2026-04-26 \- Calculadora Pessoal

Primeiro programa completo que fiz sozinho.

\### Codigo

\`\`\`portugol
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
\`\`\`

\### O que aprendi
\- cadeia guarda texto, inteiro guarda numero sem virgula
\- leia() pega o que o usuario digita e guarda na variavel
\- variaveis declaradas fora da funcao funcionam dentro dela
\- virgula dentro do escreva() mistura texto com numero sem erro
\- Soma recebe o resultado de N1 \+ N2 igual na matematica

\### Hoje eu consegui
\- Fazer meu primeiro programa completo sozinho

\---

\## 2026-04-27 \- Operadores Relacionais e Logicos

\### O que aprendi
\- Operadores relacionais: comparam dois valores e retornam verdadeiro ou falso
\- Operadores logicos:
  \- E: os dois precisam ser verdadeiros
  \- OU: basta um ser verdadeiro
  \- NAO: inverte o resultado
\- Diferenca entre = e ==:
  \- = guarda valor na variavel
  \- == compara dois valores

\### Codigo do dia

\`\`\`portugol
programa {
  inteiro A, B, C

  funcao inicio() {
    A <\- 2
    B <\- 3
    C <\- 5
    escreva((A == B) ou (C > A))
  }
}
\`\`\`

\### Hoje eu consegui
\- Entender que (A==B) ou (C>A) da verdadeiro porque C>A e verdadeiro
\- Descobrir que faltava == no lugar de = para comparar valores
