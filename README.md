Gestion des Services et Employés avec JSF, XAMPP et NetBeans Ce projet est une application web Java basée sur JSF qui permet la gestion des services et des employés d'une entreprise. Il utilise XAMPP comme serveur local pour la base de données MySQL et NetBeans comme environnement de développement intégré.

Introduction à JavaServer Faces (JSF) JavaServer Faces (JSF) est un framework Java destiné au développement d'applications web. Il simplifie la création d'interfaces utilisateur web en permettant la construction de composants d'interface utilisateur réutilisables. JSF suit le modèle de conception MVC (Modèle-Vue-Contrôleur), favorisant ainsi la séparation des préoccupations au sein des applications web.

📌Principales Caractéristiques de JSF :

Composants Réutilisables : JSF propose une bibliothèque de composants d'interface utilisateur (UI) préconçus tels que boutons, champs de texte, tableaux, etc. Ces composants peuvent être réutilisés facilement à travers l'application, permettant un développement plus rapide et une maintenance simplifiée .

Modèle-Vue-Contrôleur (MVC) : JSF suit le modèle MVC, encourageant la séparation claire entre le modèle (logique métier), la vue (interface utilisateur) et le contrôleur (logique de gestion des événements). Cela améliore la maintenabilité et la modularité des applications.

Gestion Automatique des États : JSF gère automatiquement l'état des composants entre les requêtes HTTP, éliminant ainsi la nécessité pour les développeurs de gérer manuellement les états des composants. Cela simplifie le développement et améliore la productivité.

Intégration Transparente avec d'Autres Technologies Java : JSF s'intègre facilement avec d'autres technologies Java telles que Java EE (Enterprise Edition), les servlets, les JSP (JavaServer Pages) et les bean CDI (Context and Dependency Injection).

Gestion des Événements et de la Navigation : JSF offre une gestion robuste des événements, permettant aux développeurs de gérer les interactions utilisateur de manière efficace. La navigation entre les pages est également gérée de manière déclarative, simplifiant la configuration.

Support Internationalization (i18n) : JSF facilite la prise en charge de l'internationalisation en permettant aux développeurs de créer des applications multilingues de manière transparente.

Utilisation de JSF dans le Développement Web : Création de Pages JSF : Les pages JSF sont généralement définies en utilisant des fichiers XHTML, avec des balises spécifiques pour les composants JSF.

Configuration du Contrôleur : Les contrôleurs, gérant les événements et la logique métier, sont généralement gérés par des beans gérés.

Définition des Composants UI : Les composants d'interface utilisateur sont placés sur les pages XHTML et liens aux beans gérés. Ces composants sont automatiquement gérés par le cycle de vie de JSF.

Gestion des Événements : Les événements utilisateur déclenchent des actions définies dans les beans gérés, permettant une réaction appropriée côté serveur.

Navigation entre les Pages : La navigation entre les pages est souvent définie dans un fichier de configuration, simplifiant ainsi la gestion des flux de l'application.

En résumé, JSF fournit une structure solide pour le développement d'applications web Java, en mettant l'accent sur la réutilisation des composants, la gestion des états, la séparation des préoccupations et une intégration harmonieuse avec d'autres technologies Java. Son approche déclarative et son cycle de vie bien défini facilitent le développement d'applications web robustes et évolutives.

Configuration requise XAMPP : Télécharger XAMPP NetBeans : Télécharger NetBeans

Configuration de la base de données Installez XAMPP sur votre machine. Lancez XAMPP et démarrez les services Apache et MySQL. Accédez à phpMyAdmin ( http://localhost/phpmyadmin/ ) et créez une nouvelle base de données nommée gestion_employes. Importez le fichier Database.sql situé dans le répertoire Database pour créer les tables nécessaires.

Configuration du projet dans NetBeans Ouvrez NetBeans et importez le projet. Assurez-vous que le serveur GlassFish est configuré dans NetBeans. Modifiez le fichier persistence.xml dans le répertoire src/META-INF pour correspondre à vos paramètres de base de données. xml Copier le code jdbc/gestion_employes

Exécution de l'application Déployez l'application sur le serveur GlassFish depuis NetBeans. Accédez à l'application à l'adresse http://localhost:8080/NomDuProjet/ .

Fonctionnalités Gestion des Services : Ajout, suppression et modification des services ✅AJOUTER ❌SUPPRESSION MODIFICATION

![WhatsApp Image 2023-11-26 à 01 03 31_a7d70291](https://github.com/KasbiMohammed/jsf4/assets/147922729/49369ac3-08a6-4d87-9c86-b6063c7d1549)
![kasbi ajouter1](https://github.com/KasbiMohammed/jsf4/assets/147922729/ce5cb9bf-a4a6-4d8a-9e37-ac2e2190d355)
![supprimer ](https://github.com/KasbiMohammed/jsf4/assets/147922729/8d818126-8617-4bf5-a943-e0a72c848438)
![modifier](https://github.com/KasbiMohammed/jsf4/assets/147922729/42fa3a3d-15de-4c7e-9d13-911bcbe00753)

![WhatsApp Image 2023-11-26 à 01 16 06_7aad126a](https://github.com/KasbiMohammed/jsf4/assets/147922729/ba159f0a-b6cc-4907-88bc-f84c7bcf17e3)
![WhatsApp Image 2023-11-26 à 01 12 24_4ac01687](https://github.com/KasbiMohammed/jsf4/assets/147922729/27362cf7-6b2f-46d5-acf6-fab26fd3bcbb)
![WhatsApp Image 2023-11-26 à 01 16 07_098a3bf4](https://github.com/KasbiMohammed/jsf4/assets/147922729/b4a0a1dc-a441-4839-b74d-4256bb0bc337)
![WhatsApp Image 2023-11-26 à 01 16 06_15b5c567](https://github.com/KasbiMohammed/jsf4/assets/147922729/95cef6f2-141a-4a9c-8da5-e44cdb0255c7)


![WhatsApp Image 2023-11-26 à 01 16 07_f5493b55](https://github.com/KasbiMohammed/jsf4/assets/147922729/cee1cd10-680d-4e87-b9b7-544567a2e0f0)


![WhatsApp Image 2023-11-26 à 01 16 06_15b5c567](https://github.com/KasbiMohammed/jsf4/assets/147922729/8ebd0889-fcad-4929-9835-a688ea532560)
![WhatsApp Image 2023-11-26 à 01 16 07_c4217cd8](https://github.com/KasbiMohammed/jsf4/assets/147922729/ad4ee2be-7507-4fdf-81c6-6c27580f269a)

https://github.com/KasbiMohammed/jsf4
