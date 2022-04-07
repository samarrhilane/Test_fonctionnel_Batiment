# Scénario d'intégration agile
1. Rédiger les User Stories & critères d'acceptance 
2. Planifier les Itérations (quoi / quand) 
3. Ecrire code + tests unitaires & fonctionnels 
4. Archiver les implémentations 
5. Exécuter et tester automatiquement 
6. Signaler et corriger les anomalies et suivrel'avancement 
7. Assurer la reproductibilité
► développement parallèle

# Test_fonctionnel_Batiment

Pour effectuer les tests fonctionnels, le package Cucumber est necessaire. Cucumber est un outil qui lit les spécifications exécutables écrites en texte brut et confirme que le logiciel fait ce que ces spécifications disent. Les spécifications se composent de plusieurs exemples ou scénarios.

![cucumber](https://user-images.githubusercontent.com/29365707/162333846-2051c2c4-5f7d-46fd-acbd-75447151926d.png)

## 1. Création d’un projet Maven :
Pour cela, il vous faut :
- Ouvrir Éclipse puis créer un nouveau projet Maven.
- créer les dépendances.
![dependecy](https://user-images.githubusercontent.com/29365707/162334418-28ab4e69-4807-4c9f-b03b-af2cb8690284.png)
## 2. Création du projet :
- Dans le répertoire src/main/java, stocker le code source des classes.
- Dans le répertoire src/test/java, stocker les classes de tests JUNIT
- Dans le répertoire src/test/ressources, stocker les fichiers .features.
## 3. Définition du feature
Nous définissons le feature qui contiendra tous les scénarios liés à la classe. Chaque situation réelle sera représentée par un scénario.
![feature](https://user-images.githubusercontent.com/29365707/162334458-dca1fd23-2f4d-470c-8ae6-60b132ba1321.PNG)

## 4.Le code de test implémentant le scénario
![stepdef](https://user-images.githubusercontent.com/29365707/162335489-1d4689d8-0720-40cd-a7dc-4abce8d18e4d.PNG)

- La fonction (le nombre détages (.+) et le nombre de fenetres (.+) dun batiment) : 
Permet de saisir le nombre de fenetre et d'etages d'un batiment
- La fonction (lutilisateur demande le calcul du nombre total de fenêtres):
Permet de calculer le nombre total de fenetres quand l'utilisateur passe la demande
- La fonction (e (.+) doit etre retourné):
Retourne le nombre calculer après la demande

## 5. Execution est resultat du test
![runner](https://user-images.githubusercontent.com/29365707/162334484-719c1b65-a6e0-4f5f-a713-2bdefc7e2d6a.PNG)

==> test réalisé !!
