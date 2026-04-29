# CTF - Bancarrota 💰🔐

¡Bienvenidos a **CTF-Bancarrota**! 🎉  
Un reto donde la criptografía no es tan segura como parece… y donde un pequeño fallo puede llevar a una **quiebra total del sistema**.

Prepárate para enfrentarte a un desafío avanzado de **RSA**, fugas de información y ataques matemáticos que pondrán a prueba tu conocimiento en criptografía moderna. 😈



## ¿De qué trata CTF-Bancarrota? 🤔

En este reto, una entidad bancaria ha implementado un sistema de cifrado RSA para proteger información crítica… pero algo ha salido mal.

Se ha filtrado **parte de uno de los primos privados** utilizados en la generación de la clave.

Tu misión será responder a la gran pregunta:

> **¿Puede romperse RSA si conocemos solo una parte de uno de sus factores?**

Spoiler: sí… si sabes cómo hacerlo. 💀



## 🧠 Conceptos clave del reto

Durante el desafío tendrás que aplicar:

- 🔐 Criptografía RSA
- 🧩 Fuga parcial de claves
- 📐 Matemática modular
- ⚡ Ataque de Coppersmith (small roots)
- 🧠 Pensamiento analítico

Este no es un reto de fuerza bruta… es un reto de **inteligencia**.



## ¿Por dónde empiezo? 🛠️

1. **Descarga el reto:**

   📥 [Descargar Bancarrota](https://labs.thehackerslabs.com/machine/193)



2. **Analiza los datos:**

El reto incluye un archivo `output.txt` con parámetros como:

- `n`
- `e`
- `c`
- `p_msb`
- `unknown_bits`

Si sabes lo que significan… ya estás dentro del juego.



3. **Encuentra la vulnerabilidad:**

No estás ante un RSA normal.

Aquí hay una **filtración parcial de un primo**.  
Eso cambia completamente las reglas.



4. **Rompe el sistema:**

Si logras reconstruir el primo:

- Factorizas `n`
- Calculas la clave privada
- Descifras el mensaje

Y provocas la **bancarrota total** 💥



## 🧩 Pistas y solución

Si te quedas atascado, puedes consultar la solución completa:

📖 [Writeup Bancarrota](https://beafn28.gitbook.io/beafn28/mis-ctfs/bancarrota)



## 🚀 ¿Estás listo?

Este reto no es trivial.  
Requiere entender cómo funciona RSA **más allá de lo básico**.

Pero si lo resuelves, habrás aprendido una de las vulnerabilidades más interesantes en criptografía aplicada.



## 💀 Mensaje final

> En criptografía, no hace falta romper todo el sistema…  
> solo encontrar la pequeña grieta que lo destruye por completo.



Buena suerte, hacker.  
Y recuerda…

**los bancos también pueden quebrar.** 🏦💥
