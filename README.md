
                  Rapport du proje
Aoudia katiana 
Alili lina 
groupe 1 


# application superette
Introduction
Ce projet vise à concevoir une application permettant de gérer les opérations courantes d’une supérette. L’application prend en charge la gestion des produits, des achats, des ventes, des fournisseurs, des contrats et des contacts. Toutes ces informations sont stockées dans une base de données relationnelle et permettent une analyse simplifiée.

Progrès Réalisés
Connexion à la Base de Données
Après avoir rencontré et résolu des difficultés liées au mot de passe, nous avons pu établir une connexion stable avec la base de données pédagogique utilisée pour le projet.
Définition de la Classe Produit
La structure de la classe Produit a été définie avec les attributs essentiels. Ces derniers incluent des champs tels que numUnique, idAchat, nom, description, prixVente et catégorie. Chacun a été spécifié avec son type de données et sa signification dans le contexte de l’application.
Création de la Table Produit
Une table associée à la classe Produit a été créée dans la base de données. Sa structure a été validée pour garantir qu’elle répond aux exigences de l’application.
Insertion de Données
Pour insérer des données dans la table Produit, deux approches ont été explorées : l’utilisation directe de commandes SQL dans le terminal et l’utilisation de l’outil BufferedReader pour capturer les données saisies par l’utilisateur.
Certaines difficultés ont été rencontrées, notamment des erreurs liées à la compatibilité des types de données et à la gestion des formats lors de l’insertion via BufferedReader.
Prochaines Étapes
Nous prévoyons de résoudre les problèmes liés à l’insertion des données pour rendre le processus plus fluide et fiable.

Langages et Technologies Utilisés
L’application a été développée en Java pour la logique, tandis que PostgreSQL a été utilisé pour la gestion de la base de données avec l’aide de l’API JDBC.
Résumé des Fonctionnalités
L’application propose un menu principal permettant d’accéder aux différentes sections, à savoir les produits, fournisseurs, achats, ventes, contrats, contacts et résultats. Pour chaque section, plusieurs actions sont disponibles, telles que l’ajout ou la suppression d’éléments, la modification d’informations et l’affichage des données existantes.
Certaines fonctionnalités spécifiques aux achats incluent la validation ou le report des commandes, ainsi que le calcul des prix moyens. L’application prend également en charge des commandes interactives permettant d’afficher des lots proches de leur date de péremption ou de modifier des quantités.
Difficultés Rencontrées

Description Fonctionnelle par Onglet
Onglet 1 : Produit
Cet onglet permet de visualiser la liste complète des produits enregistrés dans la base de données. Il offre également la possibilité d’ajouter un nouveau produit ou de modifier les informations d’un produit existant. Les descriptions détaillées et la catégorie du produit s’affichent dans une fenêtre modale au clic sur un élément.
Onglet 2 : Fournisseur
Dans cet onglet, il est possible de gérer les informations des fournisseurs, telles que le nom de la société, le numéro SIRET, l’adresse et l’e-mail principal. Les produits associés à chaque fournisseur sont automatiquement affichés en fonction des contrats en cours.
Onglet 3 : Achat
Cet onglet permet de gérer les achats auprès des fournisseurs. Les utilisateurs peuvent ajouter un achat, modifier la quantité pour respecter les termes du contrat ou reporter une commande à une date ultérieure. Les achats de la journée sont automatiquement validés à minuit. L’onglet inclut également des fonctionnalités pour calculer le prix moyen d’un produit ou afficher les lots proches de leur date de péremption.
Onglet 4 : Vente
L’ajout d’une vente se fait en sélectionnant un produit et une quantité. Les ventes réalisées pour la journée sont également affichées dans cet onglet pour une meilleure visibilité.
Onglet 5 : Contrats
Les contrats entre la supérette et ses fournisseurs peuvent être consultés ou modifiés dans cet onglet. Les utilisateurs peuvent, par exemple, ajuster la date de validité d’un contrat pour s’adapter à de nouveaux termes convenus avec le fournisseur.
Onglet 6 : Contacts
Cet onglet permet de gérer les contacts associés à chaque fournisseur, avec des champs pour le nom, le prénom, la fonction, l’e-mail et le numéro de téléphone.
Onglet 7 : Résultats
Les résultats affichent un résumé des indicateurs clés liés aux ventes. Ces indicateurs incluent le total des ventes réalisées pour la journée et le mois, les bénéfices générés sur ces périodes, ainsi qu’un classement des dix meilleures ventes. Ce classement est établi à la fois en fonction des quantités vendues et des bénéfices obtenus.
Difficultés Rencontrées
Le choix dynamique d’un fournisseur parmi plusieurs options disponibles pour chaque produit n’a pas pu être implémenté dans la version actuelle. Par ailleurs, bien que nous ayons une interface utilisateur fonctionnelle et claire, nous n’avons pas pu développer une interface graphique en raison de notre manque de formation dans ce domaine.
Conclusion
Malgré certaines limitations, l’application atteint ses objectifs principaux en permettant une gestion centralisée et efficace des opérations d’une supérette. Avec des améliorations futures, notamment pour l’interface graphique et certaines fonctionnalités avancées, elle pourra répondre encore mieux aux besoins des utilisateurs.

