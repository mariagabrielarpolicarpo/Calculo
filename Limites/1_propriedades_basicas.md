# Propriedades básicas do Limite

### 1) O limite de uma constante é sempre a mesma constante 

- lim (x-> a) c  = c 

      Ex: lim (x->54) 8  = 8 
   
### 2) Quando a função é multiplicada por uma constante, podemos colocá-la em evidência

- lim (x-> a) [c.f(x)] = c.lim (x-> a) f(x)

      Ex: lim (x-> 1) (2x² + 4x - 2) = lim (x->1) 2.(x² + 2x - 1) = 2.lim (x-> 1) (x² + 2x - 1)

### 3) O limite da soma/diferença de duas funções f(x) e g(x) é igual ao limite de f(x) +- o limite de g(x) 

- **lim (x->a)** [f(x)+- g(x)] = **lim (x->a)** f(x) +- lim (x->a) g(x) 

      Ex: lim (x->1) (x-3) + (x+5)/(x-9) =

          lim(x->1) (x-3) + lim (x->1) (x+5)/(x-9) 

### 4) O limite do produto de duas funções f(x) e g(x) é igual ao limite de f(x) multiplicado pelo limite de g(x)

- **lim(x->a)** [f(x).g(x)] = **lim(x->a)** f(x).**lim(x->a)** g(x)

      Ex: lim(x->1) [(x-3)(x+5)]/(x-9) = 

          lim(x->1) (x-3). lim(x->1)(x+5)/(x-9)

### 5) O limite do quociente de duas funções f(x) e g(x) é igual ao limite de f(x) dividido pelo limite de g(x)
Obs: o denominador deve ser diferente de 0

- **lim(x->a)** f(x)/g(x) = **lim(x->a)** f(x) / **lim(x->a)** g(x) 

      Ex: lim(x->1) [sen (x) / x-9] = 
          lim(x->1) sen (x) / lim(x->1) x-9

### 6) Apenas para f contínua:

- **lim(x->a)** f(g(x)) = f(**lim(x->a)** g(x))

Esta propriedade pode ser utilizada em: 

#### Raízes: 

      lim(x->a) √x³ = 
      √[lim(x->a) x³] = 
      √a³

#### Exponenciais: 

      lim(x->a) e^4x = 
      e^[lim(x->a)4x] = 
      e^4a

#### Funções trigonométricas: 

      lim(x->a) sen(x2) = 
      sen[lim(x->a) x²] = 
      sen a²

#### Funções logarítmicas: 

      lim(x->a) ln(x³) = 
      ln[lim(x->a)x³] = 
      ln(a³)
