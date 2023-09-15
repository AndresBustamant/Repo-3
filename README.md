# Repo-3

flowchart TD
   A[inicio] --> B(definir n)
   B -->C(crear una lista I de 2 a n-1)
   D -->E(dividir n/ I hasta I= n-1)
   C -->D( I=2)
   E -->F(I= I+1)
   F -->D
   F -->G{el modulo de N/I dion cero alguna vez}
   G -->H(si)
   G -->I(no)
   H -->J(no es un mumero primo)
   I -->K(es un numero primo)
