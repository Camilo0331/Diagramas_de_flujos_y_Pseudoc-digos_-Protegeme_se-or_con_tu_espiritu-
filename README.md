# Diagramas_de_flujos_y_Pseudoc-digos_-Protegeme_se-or_con_tu_espiritu-
Espero que sea de su agrado y entiendan lo que quise representar
# Pseudocódigo y diagrama de flujo para hallar números primos
## Pseudocódigo
Aquí plantee el pseudocódigo para n=20
```
[variables]
n: int =20
i: int
inicio
 i : =2
 si modulo (i, desde 1 hasta i) == 0
   mientras (i solo sea divisible por 1 y por i) entonces
          escribir ("i es número primo")
   sino
           escribir ("i no es número primo")
           i=i+1
           mientras (i < n)
        Fin mientras
 fin
```
## Diagrama de flujo
Utilice la pagina mermaid
este es el código que utilice, lo pueden copiar y pegar en mermaid
```
flowchart TD
   A(Inicio) --> B[Lista de 2 hasta 20] 
  B --> C[i=2]
  C --> D[Dividir i entre cada número desde 1 hasta i]
  D --> E{ Solo al dividir por 1 y por i el residuo es cero?}
  E -->|sí| F[i es número primo]
  E -->|no| G[i no es número primo]
  F --> H[i=i+1]
  G --> H[i=i+1]
  H --> I{i es menor 20?}
  I -->|sí| D
  I -->|no| J(Fin)
```
![mermaid-diagram-2023-02-26-215617](https://user-images.githubusercontent.com/124615019/221462517-33428a9e-e266-4bdb-940d-c40dd8325835.png)
# Pseudocódigo y diagrama de flujo para hallar raíces
## Pseudocódigo
El pseudocódigo lo plantee de la forma para hallar el resultado de las raíces hasta n, sí tiene mas de 3 decimales solo dejar hasta el tercero para que sea un proceso finito.
```
[variables]
n : int
i : int
x : int
y : float
 inicio 
    i := 0 
 sí modulo (√i) == x entonces  
        escribir("x")
     sino da x y da (√i) == y entonces    
        escribir (y) hasta tercer decimal    
  i:= i+1  
      mientras (i menor o igual a n)
   Fin mientras
fin
```
## Diagrama de flujo
Adjunto el código para que puedan copiar y pegar en mermaid
```
flowchart TD
   A(Inicio) --> B[Lista de números del 0 hasta n] 
   B --> C[i=0]
   C --> D[Sacar raiz cuadrada de i]
   D --> E{La raiz cuadrada de i tiene más de tres decimales?}
   E -->|sí| F[Tomar hasta el tercer decimal de la raiz de i]
   E -->|no| G[Dejar la raiz de i completa]
   F --> H[i=i+1]
   G --> H[i=i+1]
   H --> I{i menor o igual n?}
   I -->|sí| D 
   I -->|no| J(Fin)
```
![mermaid-diagram-2023-02-26-220924](https://user-images.githubusercontent.com/124615019/221464004-e88f8368-82c6-4c20-b3ed-d254864f1e70.png)
### ¡Gracias, espero que haya sido de utilidad para ustedes!
