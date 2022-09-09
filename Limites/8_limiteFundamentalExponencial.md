# Limite Fundamental Exponencial 

$$ lim(u->+-∞) (1+\frac{1}{u})^u = e $$

Se pegarmos $\frac{1}{u}$ e substituíssem por h, u tenderia a infinito e h tenderia a zero. 

$$ lim(h->+0) (1+h)^\frac{1}{h} = e $$

No limite a seguir, se substituísemos, cairíamos numa indeterminação $1^∞$

$$ lim(x->+∞) (1+\frac{2}{x})^{4x} $$ 

$\frac{1}{u}$ corresponde a $\frac{2}{x}$, então fazendo a substituição $\frac{1}{u} = \frac{2}{x}$ -> $x=2u$ e $4x->4(2u)->8u$

Da mesma forma, os valores que tendem também devem ser modificados, u tende a $\frac{x}{2}$

$u->\frac{x}{2} = \frac{+∞}{2}$ então $u->+∞$

$$ lim(u->+∞) (1+\frac{1}{u})^{8u} = $$ 

$$ lim(u->+∞) ({(1+\frac{1}{u})^u})^8 = $$ 

$$ ({lim(u->+∞) (1+\frac{1}{u})^u})^8 = e^8 $$ 


### Passo-a-passo:

1. Deixar a base no formato (1+f(x)) 

2. Chamar o f(x) de $\frac{1}{u}$
 
3. Aplicar a substituição tanto no expoente, quanto no valor da tendência.

4. Substituir pelo limite fundamental exponencial.
