1. **Installer l'application**

    **Description :** Décrit le processus d'installation de l'application sur différents médias.

    **Acteurs :** L'utilisateur, le serveur de mise à disposition de l'application.

    **Précondition :** Le téléchargement de l'application doit être possible depuis le média (ordinateur ou smartphone) de l'utilisateur.

    **Étapes :**

    - L'utilisateur ouvre son navigateur ou le marché de son système d'exploitation.
    - L'utilisateur saisit le nom de l'application.
    - La page de sélection affiche la description de l'application et ses informations légales, notamment celles correspondant aux partages des œuvres et à leurs droits d'auteurs.
    - L'utilisateur sélectionne l'application et l'installe.

    **Scénario Alternatif :**
    - L'utilisateur utilise le market store de son système d'exploitation plutôt que le navigateur.

    **Données :**
    - Informations de l'application (nom, description, droits d'auteur).
    
    **État Final :** L'application est installée avec succès sur le dispositif de l'utilisateur.

2. **Devenir Membre**

    **Description :** Un anonyme devient membre de l'application.

    **Acteurs :** Un utilisateur anonyme, FranceConnect, les différents mandataires de FranceConnect.

    **Prérequis :** Le scénario « Installer l'application » a été exécuté sans erreur.

    **Étapes :**

    - L'utilisateur anonyme lance l'application.
    - L'application détecte que c'est son premier lancement sur le média.
    - L'application affiche une page d'information.
    - L'application propose à l'utilisateur de se connecter via FranceConnect.
    - L'application propose de créer un compte ne pouvant déposer ou louer des œuvres.
    - L'utilisateur choisit de se connecter via FranceConnect.

    **Scénario Alternatif :**
    - L'utilisateur choisit de créer un nouvel identifiant.

    **Données :**
    - Informations d'identification (nom, prénom, date de naissance).

    **État Final :** L'utilisateur est connecté avec succès et peut accéder aux fonctionnalités de l'application.

3. **Naviguer dans l'application en tant qu'utilisateur connecté**

    **Description :** L'utilisateur connecté explore les différentes fonctionnalités de l'application après s'être identifié avec succès.

    **Acteurs :** Utilisateur connecté, Serveur de l'application.

    **Précondition :** L'utilisateur est connecté à l'application.

    **Étapes :**

    - L'utilisateur ouvre l'application.
    - L'application affiche le tableau de bord de l'utilisateur connecté.
    - L'utilisateur explore les différentes sections de l'application (par exemple, la bibliothèque, les paramètres).
    - L'utilisateur effectue une action, comme la recherche d'une œuvre spécifique.
    - L'application affiche les résultats de la recherche.
    - L'utilisateur sélectionne une œuvre et explore les options associées (lecture, informations supplémentaires, etc.).

    **Scénario Alternatif :**
    - L'utilisateur explore d'autres fonctionnalités avant de rechercher une œuvre.

    **Données :**
    - Préférences de navigation de l'utilisateur.

    **État Final :** L'utilisateur a navigué avec succès dans l'application et peut accéder aux fonctionnalités de son choix.

4. **Déposer une œuvre dans la bibliothèque publique**

    **Description :** L'utilisateur souhaite contribuer en déposant une œuvre dans la bibliothèque publique de l'application.

    **Acteurs :** Utilisateur connecté, Serveur de l'application.

    **Précondition :** L'utilisateur est connecté et a une œuvre à déposer.

    **Étapes :**

    - L'utilisateur accède à la section de dépôt d'œuvres.
    - L'application affiche les instructions et les critères pour le dépôt.
    - L'utilisateur sélectionne l'œuvre à déposer.
    - L'application demande des informations supplémentaires sur l'œuvre (titre, description, etc.).
    - L'utilisateur fournit les informations requises.
    - L'application télécharge l'œuvre sur le serveur.

    **Scénario Alternatif :**
    - L'utilisateur choisit de ne pas fournir certaines informations supplémentaires facultatives.

    **Données :**
    - Informations sur l'œuvre déposée.

    **État Final :** L'œuvre est déposée avec succès dans la bibliothèque publique de l'application.

5. **Gérer les droits d'auteur sur une œuvre déposée**

    **Description :** L'utilisateur souhaite mettre à jour les droits d'auteur sur une œuvre qu'il a déposée précédemment.

    **Acteurs :** Utilisateur connecté, Serveur de l'application.

    **Précondition :** L'utilisateur a déjà déposé une œuvre.

    **Étapes :**

    - L'utilisateur accède à la section de gestion des droits d'auteur.
    - L'application affiche la liste des œuvres déposées par l'utilisateur.
    - L'utilisateur sélectionne l'œuvre dont il souhaite mettre à jour les droits.
    - L'application affiche les informations actuelles sur les droits d'auteur.
    - L'utilisateur modifie les informations sur les droits d'auteur.
    - L'application enregistre les modifications sur le serveur.

    **Scénario Alternatif :**
    - L'utilisateur souhaite ajouter une licence spécifique aux droits d'auteur.

    **Données :**
    - Informations sur les droits d'auteur mis à jour.

    **État Final :** Les droits d'auteur de l'œuvre sont mis à jour avec succès sur le serveur de l'application.

6. **Louer une œuvre protégée par des droits d'auteur**

    **Description :** L'utilisateur souhaite louer une œuvre spécifique qui est protégée par des droits d'auteur.

    **Acteurs :** Utilisateur connecté, Serveur de l'application, Propriétaire des droits d'auteur.

    **Précondition :** L'utilisateur est connecté et a accès à des œuvres protégées par des droits.

    **Étapes :**

    - L'utilisateur recherche une œuvre spécifique.
    - L'application affiche les détails de l'œuvre, y compris les conditions de location.
    - L'utilisateur sélectionne l'option de location.
    - L'application demande confirmation de la location.
    - L'utilisateur confirme la location.
    - L'application communique avec le serveur pour vérifier les droits et effectuer la transaction.

    **Scénario Alternatif :**
    - L'utilisateur souhaite consulter les conditions de location avant de rechercher une œuvre spécifique.

    **Données :**
    - Informations sur la location de l'œuvre.

    **État Final :** L'utilisateur a loué avec succès une œuvre protégée par des droits d'auteur.

7. **Modifier les préférences de compte**

    **Description :** L'utilisateur ajuste les paramètres et préférences de son compte au sein de l'application.

    **Acteurs :** Utilisateur connecté, Serveur de l'application.

    **Précondition :** L'utilisateur est connecté à son compte.

    **Étapes :**

    - L'utilisateur accède à la section des paramètres de son compte.
    - L'application affiche les différentes options de personnalisation (langue, notifications, etc.).
    - L'utilisateur modifie ses préférences selon ses besoins.
    - L'application enregistre les modifications sur le serveur.

    **Scénario Alternatif :**
    - L'utilisateur choisit de ne pas effectuer de modifications après avoir accédé à la section des paramètres.

    **Données :**
    - Nouvelles préférences de compte.

    **État Final :** Les préférences du compte utilisateur sont mises à jour avec succès sur le serveur de l'application.

8. **Information Supplémentaire Facultative lors du Dépôt:**

    **Description :** L'utilisateur dépose une œuvre dans la bibliothèque publique, mais décide de ne pas fournir certaines informations supplémentaires facultatives.

    **Acteurs :** Utilisateur connecté, Serveur de l'application.

    **Précondition :** L'utilisateur est connecté et a une œuvre à déposer.

    **Étapes :**

    - L'utilisateur accède à la section de dépôt d'œuvres.
    - L'application affiche les instructions et les critères pour le dépôt.
    - L'utilisateur sélectionne l'œuvre à déposer.
    - L'application demande des informations supplémentaires sur l'œuvre (titre, description, etc.).
    - L'utilisateur choisit de ne pas fournir certaines informations facultatives.
    - L'application accepte le dépôt avec les informations obligatoires uniquement.
    - L'œuvre est téléchargée sur le serveur avec les informations disponibles.

    **Scénario Alternatif :**
    - L'utilisateur décide de fournir toutes les informations facultatives.

    **Données :**
    - Informations sur l'œuvre déposée.

    **État Final :** L'œuvre est déposée avec succès dans la bibliothèque publique de l'application.

9. **Ajout d'une Licence Spécifique lors de la Gestion des Droits d'Auteur:**

    **Description :** L'utilisateur souhaite ajouter une licence spécifique aux droits d'auteur de son œuvre déposée.

    **Acteurs :** Utilisateur connecté, Serveur de l'application.

    **Précondition :** L'utilisateur a déjà déposé une œuvre.

    **Étapes :**

    - L'utilisateur accède à la section de gestion des droits d'auteur.
    - L'application affiche la liste des œuvres déposées par l'utilisateur.
    - L'utilisateur sélectionne l'œuvre dont il souhaite mettre à jour les droits.
    - L'application affiche les informations actuelles sur les droits d'auteur.
    - L'utilisateur choisit d'ajouter une licence spécifique aux droits d'auteur.
    - L'application guide l'utilisateur pour sélectionner le type de licence et fournir les détails associés.
    - L'utilisateur enregistre les modifications.
    - L'application met à jour les informations sur les droits d'auteur avec la nouvelle licence sur le serveur.

    **Scénario Alternatif :**
    - L'utilisateur choisit de ne pas ajouter de licence spécifique.

    **Données :**
    - Informations sur les droits d'auteur mis à jour.

    **État Final :** Les droits d'auteur de l'œuvre sont mis à jour avec succès sur le serveur de l'application.

10. **Consulter les Conditions de Location avant de Rechercher une Œuvre Spécifique:**

    **Description :** L'utilisateur souhaite consulter les conditions de location avant de rechercher une œuvre spécifique à louer.

    **Acteurs :** Utilisateur connecté, Serveur de l'application, Propriétaire des droits d'auteur.

    **Précondition :** L'utilisateur est connecté et a accès à des œuvres protégées par des droits.

    **Étapes :**

    - L'utilisateur accède à la section de location d'œuvres.
    - L'application affiche les conditions générales de location.
    - L'utilisateur prend connaissance des conditions avant de commencer la recherche d'une œuvre.

    **Scénario Alternatif :**
    - L'utilisateur choisit de rechercher une œuvre avant de consulter les conditions de location.

    **Données :**
    - Informations sur la location de l'œuvre.

    **État Final :** L'utilisateur a pris connaissance avec succès des conditions de location et peut maintenant rechercher une œuvre en toute connaissance de cause.

11. **Pas de Modification des Préférences de Compte:**

    **Description :** L'utilisateur accède à la section des paramètres de son compte mais choisit de ne pas effectuer de modifications.

    **Acteurs :** Utilisateur connecté, Serveur de l'application.

    **Précondition :** L'utilisateur est connecté à son compte.

    **Étapes :**

    - L'utilisateur accède à la section des paramètres de son compte.
    - L'application affiche les différentes options de personnalisation (langue, notifications, etc.).
    - L'utilisateur choisit de ne pas effectuer de modifications.
    - L'application ne fait aucune mise à jour.

    **Scénario Alternatif :**
    - L'utilisateur choisit de modifier certaines préférences après avoir accédé à la section des paramètres.

    **Données :**
    - Préférences de compte inchangées.

    **État Final :** Aucune modification n'a été apportée aux préférences du compte utilisateur, et l'application conserve les préférences existantes. 
