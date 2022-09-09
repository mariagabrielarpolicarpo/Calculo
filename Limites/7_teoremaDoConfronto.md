# Teorema do Confronto 

Como fazer para calcular o limite de h(x)? 

$f(x)<= h(x) <= g(x)$ 

Como h(x) está limitada entre as duas funções, posso aplicar limite nas 3: 

$lim(x->a) f(x)$  <=  $lim(x->a) h(x)$  <=  $lim(x->a) g(x)$

Se $$lim(x->a) f(x) = lim(x->a) g(x) = K$$ então necessariamente $$lim(x->a) h(x) = K$$ pois h(x) está limitado entre as duas funções.

Sendo assim: 

$$ lim(x->+∞) \frac{sen(x)}{x} $$

Sabe-se que o seno é limitado -1 <= sen(x) <= 1

Se multiplicarmos todos os lados por $\frac{1}{x}$ :

$$ \frac{1}{x} <= \frac{sen(x)}{x}  <= \frac{1}{x} $$

Aplicar limites em todas as partes: 

$$ lim(x->+∞) \frac{1}{x} <= lim(x->+∞) \frac{sen(x)}{x} <= lim(x->+∞) \frac{1}{x}$$

$$ 0 <= lim(x->+∞) \frac{sen(x)}{x} <= 0 $$

Sendo assim: 

$$lim(x->+∞) \frac{sen(x)}{x} = 0 $$

## Sem trigonométricas

Se f(x) é limitada entre 4 <= f(x) <= 6, então

$$ lim(x->+∞) \frac{4}{x} <= lim(x->+∞) \frac{f(x)}{x} <= lim(x->+∞) \frac{6}{x}$$

$$ 0 <= lim(x->+∞) \frac{f(x)}{x} <= 0 $$

Logo 

$$ lim(x->+∞) \frac{f(x)}{x} = 0 $$
