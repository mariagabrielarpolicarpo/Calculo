# Quociente de funções com x tendendo ao infinito 

Nesse tipo de caso, o ideal é verificar o grau do numerador e denominador e evidenciar a variável

Se eu fizesse essa operação sem manipulação, teria ∞/∞ que é indeterminado:

$$ lim(x->∞) \frac{x^3+x+1}{x^2+1} = $$ 

Colocar o x³ e x² em evidência:

$$ lim(x->∞) \frac{x^3(1+\frac{1}{x^2} + \frac{1}{x^3})}{x^2(1+\frac{1}{x^2})} = $$

Com isso, todas as frações evidenciadas com x no denominador resultaram em 0: 

$$ \frac{x^3(1+0+0)}{x^2(1+0)} = $$

$$ \frac{x^3}{x^2} = $$ 

$$ x = ∞ $$


                
## Quando há raiz 

Nesse caso, deixar os termos de maior grau em evidência para tirar tudo que for possível de dentro da raiz. Quando o grau do numerador é maior, 
a função vai para +-∞, se for o mesmo grau resulta em uma constante e se o grau do denominador for maior, vai ser zero. 

$$ lim(x->-∞) \frac{x+1}{\sqrt{4x²+8x}} = $$

$$ lim(x->-∞) \frac{x(1+\frac{1}{x})}{\sqrt{x^2(4+ \frac{8}{x})}} = $$           
                 
$$ lim(x->-∞) \frac{x(1+\frac{1}{x})}{|x|\sqrt{4+ \frac{8}{x}}} = $$
                 
Como x tende a -∞, |x| = -x 
                 
$$ lim(x->-∞) \frac{x(1+\frac{1}{x})}{-x\sqrt{4+ \frac{8}{x}}} = $$

$$ lim(x->-∞) \frac{1+\frac{1}{x}}{-\sqrt{4+ \frac{8}{x}}} = $$

Substituí x por -∞:

$$ lim(x->-∞) \frac{1+0}{-\sqrt{4+0}} = \frac{1}{2}$$
                 
                 
## Quociente de funções exponenciais 

Nesse caso, deve-se colocar em evidência a maior base da função. 

$$ lim(x->∞) \frac{(3^x - 2^x)}{4^x + 5} =$$

$$ lim(x->∞) \frac{3^x[(\frac{3^x}{3^x}) - (\frac{2^x}{3^x})]}{4^x[(\frac{4^x}{4^x}) + (\frac{5}{4^x})]}= $$

$$ lim(x->∞) \frac{3^x[1 - (\frac{2}{3})^x]}  {4^x[ 1 + 5 (\frac{1}{4})^x]} = $$
    
$$ lim(x->∞) 
(\frac{3}{4})^x
\frac{[1 - (\frac{2}{3})^x]}  {[ 1 + 5 (\frac{1}{4})^x]} = $$

$$ (\frac{3}{4})^∞
\frac{[1 - (\frac{2}{3})^∞]}  {[ 1 + 5 (\frac{1}{4})^∞]} = $$
   
As exponenciais com base menor que 1 zeram:   
   
$$ 0
\frac{1-0}{1+5.(0)} = 0 $$
