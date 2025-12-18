# PGCD-a-b-c-
Le PGCD  de 3 nombres : 

Il existe plusieurs méthodes pour calculer le PGCD de 3 nombres mais la plus simple et la plus efficace est :
La méthode d’Euclide ; c’est la plus rapide, la plus pratique, et elle fonctionne même pour des grands nombres.
Le principe est comme suit :
•	On utilise la formule :
   PGCD (a,b,c,) =PGCD (PGCD(a,b),c)
Et on calcule chaque PGCD avec l’algorithme d’Euclide :
   PGCD(x,y) =   PGCD(y , x mod y)
Exemple :
PGCD(48, 18, 30) :
	D’abord PGCD(48, 18) :
48=18×2+12
→ PGCD(48,18) = PGCD(18,12)
18=12×1+6
→ PGCD(18,12) = PGCD(12,6)
12=6×2+0
 Le PGCD (48 ,18)=6
	Maintenant PGCD(6, 30) :

30=6 ×5+0
Le PGCD(6, 30) = 6
Donc : 
Le résultat final est :
        PGCD(48,18,30)=6
