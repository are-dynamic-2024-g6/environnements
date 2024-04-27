# Première partie: Etude du modèle initiale

Pour modéliser l'évolution de la température dans une ville, nous allons commencer par créer un modèle simplifié d'une ville . Nous allons définir des paramètres simples pour calculer la température à chaque position de la ville. Les formules et les paramètres seront basés sur les principes de base de la diffusion thermique, du bilan radiatif et de l'effet d'îlot de chaleur urbain.

1) Initialisation de la ville à étudier
![image](https://raw.githubusercontent.com/are-dynamic-2024-g6/environnements/master/images/Capture%20d%E2%80%99e%CC%81cran%202024-04-27%20a%CC%80%2014.42.29.png)
Les cases en verts représente les zones vertes et les cases grises les zones industriellle.

2) Définir la fonction generate_heat_amount_per_hour qui représente la variation de l'ensoleillement tout au long d'une journée.
![image](https://raw.githubusercontent.com/are-dynamic-2024-g6/environnements/master/images/Capture%20d%E2%80%99e%CC%81cran%202024-04-27%20a%CC%80%2014.45.43.png)

3) En fonction des températures reçues, nous créons un nouveau plan dans lequel nous présentons l'augmentation attendue de la température dans la ville.
![image](https://raw.githubusercontent.com/are-dynamic-2024-g6/environnements/master/images/Capture%20d%E2%80%99e%CC%81cran%202024-04-27%20a%CC%80%2014.51.34.png)

4)À partir des données obtenues, nous trouvons la zone avec la température la plus élevée.
![image](https://raw.githubusercontent.com/are-dynamic-2024-g6/environnements/master/images/Capture%20d%E2%80%99e%CC%81cran%202024-04-27%20a%CC%80%2015.04.19.png)

5)Tracer l'évolution de la température pour un lieu précis (coordonnées).
![image](https://raw.githubusercontent.com/are-dynamic-2024-g6/environnements/master/images/Capture%20d%E2%80%99e%CC%81cran%202024-04-27%20a%CC%80%2015.03.55.png)
