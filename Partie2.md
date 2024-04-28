# Deuxième partie

1) Étudier la libération de chaleur d'une ville:
Effet d'îlot de chaleur urbain : Les villes ont tendance à être plus chaudes que les zones environnantes en raison de l'accumulation de chaleur générée par les activités humaines, les bâtiments en béton et en asphalte qui absorbent et retiennent la chaleur, et la diminution de la végétation. Comprendre la libération de chaleur dans différentes zones urbaines permet de quantifier et de modéliser l'effet d'îlot de chaleur urbain.

Prédiction des températures locales : En tenant compte de la libération de chaleur dans différents secteurs d'une ville, les modèles météorologiques peuvent mieux prédire les températures locales. Cela est particulièrement important pour les services météorologiques qui fournissent des prévisions météorologiques précises pour les habitants des zones urbaines.

 Îlot de chaleur urbain, [Wikipedia](https://fr.wikipedia.org/wiki/%C3%8Elot_de_chaleur_urbain)

 ![image](https://raw.githubusercontent.com/are-dynamic-2024-g6/environnements/master/images/Capture%20d%E2%80%99e%CC%81cran%202024-04-28%20a%CC%80%2018.19.23.png)
 
Le coefficient de réflexion. Ce terme désigne la proportion de lumière ou de chaleur réfléchie par une surface par rapport à celle qui est absorbée. Alors que le coefficient d'absorption mesure la capacité d'une surface à absorber la lumière ou la chaleur incidente, le coefficient de réflexion indique la proportion de cette énergie qui est renvoyée ou réfléchie.

Les mesures des coefficients d'absorption et de réflexion pour les zones vertes (forêts) et les zones urbaines peuvent varier en fonction de plusieurs facteurs, tels que la végétation, les matériaux de construction, la géométrie urbaine, etc. D'aprés https://www.nrel.gov/docs/fy17osti/66763.pdf, voici des valeurs typiques pour ces coefficients :

Zones Vertes (Forêts) : Coefficient de Réflexion : En conséquence, le coefficient de réflexion serait plus bas, par exemple autour de 0,1 à 0,2, indiquant que seule une petite fraction de l'énergie incidente est réfléchie par la végétation.
Zones Industrielle : Coefficient de Réflexion : le coefficient de réflexion serait plus élevé que dans les zones industrielles, par exemple autour de 0,4 à 0,8, indiquant une plus grande proportion d'énergie réfléchie par les surfaces industrielle.


2) Définir la température initiale, le coefficient de réflexion et la quantité de chaleur libérée pour chaque zone.


3)Définir la fonction qui calcule le changement de température en fonction de la formule
D'aprés notre recherche on a utiliisé la formule pour trouver la temperature de chaque case:

temperature=ti−cr∗qlch

Temperature-initial= Ti

Quantité de libération de chaleur == Qlch

Coefficient-de-réflexion== Cr

pour une case:
![image](https://raw.githubusercontent.com/are-dynamic-2024-g6/environnements/master/images/Capture%20d%E2%80%99e%CC%81cran%202024-04-28%20a%CC%80%2022.26.11.png)

4)En fonction des températures reçues, nous créons un nouveau plan où nous présentons la baisse de température attendue dans la ville.

![image](https://raw.githubusercontent.com/are-dynamic-2024-g6/environnements/master/images/Capture%20d%E2%80%99e%CC%81cran%202024-04-28%20a%CC%80%2018.27.50.png)


5) Trouver les coordonnées de case avec la température la plus basse dans le tableau des températures.

![image](https://raw.githubusercontent.com/are-dynamic-2024-g6/environnements/master/images/Capture%20d%E2%80%99e%CC%81cran%202024-04-28%20a%CC%80%2018.28.25.png)

6) Présenter le changement de température pour une case/ zone qui présente la plus grande baisse de température au cours de la journée.

![image](https://raw.githubusercontent.com/are-dynamic-2024-g6/environnements/master/images/Capture%20d%E2%80%99e%CC%81cran%202024-04-28%20a%CC%80%2018.29.02.png)


