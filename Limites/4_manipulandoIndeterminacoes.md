# Manipulando indeterminações

## Quociente de polinômios com x que tende a uma constante 

Deve-se manipular o numerador e o denominador para sair de indeterminações 

### Fatoração de polinômios 

#### Polinômios de 2° grau com Bháskara

      lim(x->2) (x-2)/x²-5x+6 =
                (x-2)/(x-3).(x-2) =
                1/(x-3) =
                1/2-3 = 
                -1
                
#### Produtos Notáveis

Os principais são: 
- x² - a² = (x-a)(x+2) 
- x³ -a³ = (x-a)(x²+ ax+b²)
- x³ + a³ = (x+a)(x²- ax +a²) 
- x² +- a² = (x² +- 2xb + b²) 

      Exemplo 1)
      
      lim(x->3) (√x - √3)/(x-3) = 
                x-3 = (√x)² - (√3)² (manipulação algébrica) 
                (√x)² - (√3)² = (√x - √3)(√x + √3) (utilizando a propriedade de produto notável) 
      lim(x->3) (√x - √3)/ (√x - √3)(√x + √3) = 
                1/ (√x + √3) = 
                1/(√3 + √3) = 
                1/2√3
                
      Exemplo 2) Conjugado
      
      Vou cair numa indeterminação 0/0 se substituir x por 4: lim(x->4) (√x - 2)/(x-4) 
      Sabe-se que: x-4 = (√x-2)(√x+2) 
      
      lim(x->4) (√x - 2).(√x+2)/(x-4).(√x+2) = (multipliquei o numerador e denominador por (√x + 2), a fim de que o numerador pudesse ser substituído por x-4) 
                (x - 4)/(x-4).(√x+2) = 
                1/(√x+2) = 
                1/4
                
#### Brioft-Ruffini

lim(x->3) (2x^4 - 3x³ - 17x - 30)/x-3 = 
          0/0
          
      3| 2  -3  0  -17  -30 
         2  3   9   10   0
         
      lim(x->3) (2x³ + 3x²+9x+10) =
                2.(3)³ + 3.(3)² + 9.(3) + 10 = 118 (substituindo por 3) 
      
      
### Módulo 

Observe esse exemplo com módulo no denominador: 

      lim(x->3) (x² - 7x + 12) / |x-3| 
                (x - 3)(x-4)/|x-3| (fatorei a equação de 2º grau)
                
     O módulo é dado por: 
     |x-3| = { -(x-3), x<3 
                (x-3), x>=3 } 
                
     Para resolver o problema do módulo, é necessário utilizar o conceito de limites laterais: 
     lim(x->3+) (x - 3)(x-4)/(x-3) = 
                (x-4) = 
                3-4= 
                -1 
    lim(x->3-) (x - 3)(x-4)/-(x-3) =      
               (x-4)/-1 = 
               1
               
   Como os limites laterais são diferentes, o limite não existe.
                
