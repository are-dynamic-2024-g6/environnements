# Première partie: Etude du modèle initiale

Pour modéliser l'évolution de la température dans une ville, nous allons commencer par créer un modèle simplifié d'une ville . Nous allons définir des paramètres simples pour calculer la température à chaque position de la ville. Les formules et les paramètres seront basés sur les principes de base de la diffusion thermique, du bilan radiatif et de l'effet d'îlot de chaleur urbain.

1) Initialisation de la ville à étudier
![image](https://raw.githubusercontent.com/are-dynamic-2024-g6/environnements/master/images/Capture%20d%E2%80%99e%CC%81cran%202024-04-27%20a%CC%80%2014.42.29.png)
Les cases en verts représente les zones vertes et les cases grises les zones industriellle.

2) Définir la fonction generate_heat_amount_per_hour qui représente la variation de l'ensoleillement tout au long d'une journée.

La courbe sinusoïdale est générée à l'aide de la formule :

la variation de l′ensoleillement = amplitude × sin (π/12×(heure-heure de point))+ compense quantité de chaleur

amplitude : Cela représente l'amplitude de la courbe sinus, contrôlant la plage de variation de l'ensoleillement. sin ⁡

sin : C'est la fonction sinus, qui renvoie le sinus de l'angle fourni.

𝜋/12 : Ce terme ajuste la période de la fonction sinus pour correspondre à une journée de 24 heures. Comme la période de la fonction sinus est 2𝜋, diviser par 12 la comprime pour qu'elle s'adapte dans 24 heures.

(heure−heure_pic): Ce terme ajuste la phase de la courbe sinus pour déterminer quand le pic se produit.

décalage: Cela ajoute un décalage à la courbe sinus pour s'assurer que l'ensoleillement minimale est supérieure à zéro.


![image](https://raw.githubusercontent.com/are-dynamic-2024-g6/environnements/master/images/Capture%20d%E2%80%99e%CC%81cran%202024-04-27%20a%CC%80%2014.45.43.png)

3) En fonction des températures reçues, nous créons un nouveau plan dans lequel nous présentons l'augmentation attendue de la température dans la ville à l'aide de la formule suivant.
Ti = température initial
Abs = coefficient d'absorption
Ve = variation de l'ensoleillement 
Temperature = Ti + Abs *  Ve

![image](https://raw.githubusercontent.com/are-dynamic-2024-g6/environnements/master/images/Capture%20d%E2%80%99e%CC%81cran%202024-04-27%20a%CC%80%2014.51.34.png)

4)À partir des données obtenues, nous trouvons la zone avec la température la plus élevée.
![image](https://raw.githubusercontent.com/are-dynamic-2024-g6/environnements/master/images/Capture%20d%E2%80%99e%CC%81cran%202024-04-27%20a%CC%80%2015.04.19.png)

5)Tracer l'évolution de la température pour un lieu précis (coordonnées).
![image](https://raw.githubusercontent.com/are-dynamic-2024-g6/environnements/master/images/Capture%20d%E2%80%99e%CC%81cran%202024-04-27%20a%CC%80%2015.03.55.png)

Ce modèle a montré une augmentation générale de la température dans la ville, avec des valeurs plus élevées près du centre de la ville en raison de l'effet d'îlot de chaleur urbain.

Or l'intégration de la végétation a eu un effet significatif sur la réduction de la température dans la ville. La végétation a aidé à absorber une partie du rayonnement solaire, réduisant ainsi le bilan radiatif positif et la température globale dans la ville. De plus, la végétation a également amélioré l'efficacité de la convection et de la circulation de l'air, contribuant à une meilleure régulation thermique.
