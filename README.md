# Reto 3, flujogramas y pseudocodigos 

Para este reto se socilicta realizar el flujograma y pseudocodigo para dos casos, el primero es determinar si un numero es primo  y el segundo caso es poder calcular la raiz cuadrada de un valor entregado.

1.para el primer caso desarrolle primero el flujograma para determinar si un numero es primo o no:
![mermaid-diagram-2023-09-15-235216](https://github.com/AndresBustamant/Repo-3/assets/141858005/9b73b77b-ee38-4580-bd42-5f1c50370918)
posteriormente plantee el pseudocodigo basado en el flujograma anterior:

```pseudocode
  instrucciones
n:int 
n = int(input("Ingrese un numero entero: "))
inicio
I=(2, n-1)
  def division(n/I)
  para los I <= n-1 hacer
    dividir n/I donde I=2 
      si modulo de division en algun caso = 0
       print(el numero no es primo)
    sino
       print(el numero es primo
       I:I+1
  fin para
fin
```
2.posteriormente desarrolle un segundo flujograma para poder calcular una raiz cuadrada a partir del metodo babilonico basado en nociones de aproximacion:
![mermaid-diagram-2023-09-16-011741](https://github.com/AndresBustamant/Repo-3/assets/141858005/2725efcd-20bf-42c4-b546-595c8cb5f141)
ya para finalizar a partir de este flujograma se pantea un pseudocodico consecuente a las instrucciones dadas:

```pseudocode
  instrucciones
n = int 
n = int(input("Ingrese un numero entero: "))
inicio
n = int #definir n como el valor dentro de la raiz
  def x (x=n^2) #se define la variable x como el cuadrado del numero n
  def formularaiz(x,y)
    resultado = n= n+x^2/2x
    return resultado
print("la raiz del numero es " + str(n)+ " aproximadamente")
fin
```
