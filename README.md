Algoritmo "PostoDeCombustivel"

//declaração das variáveis
Var
   tipoCombustivel: Caractere
   litros: Real
   precoLitro, precoTotal: Real
   desconto: Real



inicio

   Escreva("Digite o tipo de combustível (A-álcool, G-gasolina): ")
   Leia(tipoCombustivel)
   Escreva("Digite a quantidade de litros: ")
   Leia(litros)


   Se tipoCombustivel = "A" entao
      precoLitro <- 3.79
   fimse

   Se litros <= 25 entao
      desconto <- 0.02
   senao
      desconto <- 0.04
   fimse

   Se tipoCombustivel = "G" entao
      precoLitro <- 6.59
   fimse
   Se litros <= 25 entao
      desconto <- 0.03
   senao
      desconto <- 0.05
   fimse


   precoTotal <- (litros * precoLitro) - (litros * precoLitro * desconto)


   Escreva("O preço a ser pago é de R$", precoTotal)

FimAlgoritmo
