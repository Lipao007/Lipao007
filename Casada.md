Algoritmo "semnome"
// Disciplina  :  [Linguagem e Lógica de Programação]
// Professor   : Antonio Carlos Nicolodi
// Descrição   : Aqui você descreve o que o programa faz! (função)
// Autor(a)    : Nome do(a) aluno(a)
// Data atual  : 30/03/2023
Var

   estadoCivil,sexo,nome:caractere
   duracao:inteiro


Inicio

   escreval("Qual seu nome?")
   leia(nome)
   escreval("Qual seu sexo? coloque (F)para FEMENINO e (M) para MASCULINO")
   leia(sexo)
   escreval("Qual seu estado civil: CASADA(O) , SOLTERIA(O)")
   leia(estadoCivil)


   se (estadoCivil = "casada") e (sexo = "femenino")entao

      escreval ("desde que ano estao juntos em ano?")
      leia(duracao)
      escreval (nome , ",você é do sexo: " , sexo , " e seu estado civil é de: " ,estadoCivil , " você é casa desde o ano de:" , duracao)
   senao
      escreval (nome , ",você é do sexo: " , sexo , " e seu estado civil é de: " ,estadoCivil)

   fimse



Fimalgoritmo