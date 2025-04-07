# TD 7 : complexité - o, O, θ, ω, Ω

## Exercice 7.1

Trier les suites ci-dessous par ordre de domination au voisinage de +∞.

- $a_n = 0.001n^2 - 100000n$
- $b_n = 2^{n/2}$  
- $c_n = \log(n^2 + 1)$  
- $d_n = n^2$  
- $e_n = n^2 (\log(3n) + 5)$  
- $f_n = 3000n + 28$  
- $g_n = 2^{n+1}$  
- $h_n = 3^n - 2^n$  


## Exercice 7.2

A et B sont deux algorithmes qui répondent au même problème. La complexité de A est proportionnelle à n2 et celle de B est proportionnelle à n log n. On implémente A et B sur un même ordinateur. L'exécution du programme correspondant à A dure 1 seconde avec n=100, celle du programme correspondant à B dure 10s avec n=100. 

1. L'application prévoit n=1000. Quel algorithme faut-il choisir a priori ? 

2. Même question si n=10000.


## Exercice 7.3

On dispose d'un ordinateur X et d'un ordinateur Y 100 fois plus rapide.

1. On  dispose d'un algorithme de complexité proportionnelle à $n^2$. L'ordinateur X peut le traiter avec une taille d'entrée $n_0$ en 1 minute. Quelle taille d'entrée l'ordinateur Y peut-il traiter dans la même durée ?

2. Même question si la complexité est proportionnelle à 2n.
