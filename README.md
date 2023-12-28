Ce projet est realisé par Nidhal Alouini Groupe F , de l'ecole nationale des sciences de l'informatique
Ce programme est une application de gestion de comptes bancaires utilisant une liste chaînée de structures CompteNode. Voici un résumé de ses fonctionnalités :
Structures et Fonctions
Struct. CompteNode :
Représente un compte bancaire avec un numéro, le nom du client, le solde et un lien vers le prochain compte.
Fonction creerCompte :
Crée un nouveau compte en demandant le numéro, le nom du client et le solde initial.
Fonction afficherDetailsCompte :
Affiche les détails d'un compte en fonction de son numéro.
Fonction mettreAJourInfosCompte :
Met à jour le nom du client et le solde d'un compte spécifique.
Fonction supprimerCompte :
Supprime un compte spécifique.
Fonction afficherListeClients :
Affiche la liste de tous les clients enregistrés.
Fonction effectuerDepot et effectuerRetrait :
Effectue un dépôt ou un retrait sur un compte spécifique.
Fonction calculerInterets :
Calcule les intérêts pour un compte d'épargne en fonction d'un taux donné.
description du programme Principal :
Le programme fonctionne à l'aide d'un menu interactif offrant les actions suivantes :
-Créer un nouveau compte
-Afficher les détails d'un compte
-Mettre à jour les informations d'un compte
-Supprimer un compte
-Afficher la liste des clients
-Gestion des transactions bancaires (dépôt, retrait)
-Calcul des intérêts pour les comptes d'épargne
-Quitter
Stockage des Données :
Les informations des comptes sont sauvegardées dans un fichier texte (comptes.txt) pour assurer leur persistance entre les sessions.
