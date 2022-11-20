# cr-dito
Algoritmo "crédito"
// Disciplina   : [Linguagem e Lógica de Programação]
// Professor   : Antonio Carlos Nicolodi 
// Descrição   : Aqui você descreve o que o programa faz! (função)
// Autor(a)    : Nome do(a) aluno(a)
// Data atual  : 19/11/2022
Var
// Seção de Declarações das variáveis 
cpf, login:inteiro
quantia: real
cont: inteiro
login1:vetor [0..9]
Inicio
// Seção de Comandos, procedimento, funções, operadores, etc... 

para cont de 0 ate 9 faca
escreva("digite seu login:")
leia (login)
se (login>=0) e (login<=9) entao
escreval ("bem vindo a sua puoança")
senao
escreval ("acesso negado")
 fimse
escreval ("digite a quantia que deseja depositar: R$")
leia (quantia)
 se (quantia>=1) entao
Fimalgoritmo
