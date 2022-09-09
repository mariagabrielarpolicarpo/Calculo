# Indeterminações ∞ - ∞

Exemplo de como calcular uma indeterminação do tipo ∞ - ∞ 

      lim(x->4) 1/(x-4) - 1/(x²-5x+4) =
                1/0  -  1/0  =
                ∞ - ∞
                
      Vamos realizar algumas manipulações: 
      
      lim(x->4) 1/(x-4) - 1/(x²-5x+4) =
                1/(x-4) - 1/(x-4)(x-1) = (fatorou o denominador) 
                [1.(x-1) - 1]/(x-4)(x-1) = (igualou os denominadores, multiplicando a numerador da primeira fração por (x-1))
                x-2/(x-4)(x-1) = 
      [lim(x->4) 1/x-4].[lim(x->4) (x-2)/(x-1)] = (propriedade do produto de limites) 
      (4-2)/(4-1).[lim(x->4) 1/(x-4)] = (substituiu o 4 no segundo limite e colocou em evidência) 
      
      Depois das manipulações, a equação final foi: 
      2/3.lim(x->4) 1/(x-4) 
      
      Agora é aplicar o conceito de limites laterais para tentar chegar a um resultado determinado: 
      
      2/3.lim(x->4+) 1/(x-4) = 
                     1/4-4 = 
                     +∞
                     
      2/3.lim(x->4-) 1/(x-4) = 
                     1/4-4 = 
                     -∞
                     
      Como os limites laterais são diferentes, o limite não existe. 
      
