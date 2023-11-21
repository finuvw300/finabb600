- 👋 Hi, I’m @finxyz300
- 👀 I’m interested in ...
- 🌱 I’m currently learning ...
- 💞️ I’m looking to collaborate on ...
- 📫 How to reach me ...

<!---
finabb600/finabb600 is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->

###         Reto #0: EL FAMOSO "FIZZ BUZZ"          ###
     
/*
 * Escribe un programa que muestre por consola (con un print) los
 * números de 1 a 100 (ambos incluidos y con un salto de línea entre
 * cada impresión), sustituyendo los siguientes:
 * - Múltiplos de 3 por la palabra "fizz".
 * - Múltiplos de 5 por la palabra "buzz".
 * - Múltiplos de 3 y de 5 a la vez por la palabra "fizzbuzz".
 */
 
def fizzbuzz():
    
    for index in range(1, 101):
        
        if index % 3 == 0 and index % 5 == 0:
            print("fizzbuzz")
            
        elif index % 3 == 0:
            print("fizz")
            
        elif index % 5 == 0:
            print("buzz")
            
        else:
            print(index)
            
fizzbuzz()

https://retosdeprogramacion.com/semanales2023
