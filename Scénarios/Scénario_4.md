# Déposer une œuvre dans la bibliothèque publique

  **Description :** L'utilisateur souhaite contribuer en déposant une œuvre dans la bibliothèque publique de l'application.

  **Acteurs :** Utilisateur connecté, Interface de Dépôt, Système de Gestion de la Bibliothèque, Base de Données, Système de Validation.

  **Précondition :** L'utilisateur est connecté et a une œuvre à déposer.

  **Étapes :**

  - L'utilisateur connecté navigue vers la section de dépôt d'œuvres dans l'application.
  - L'interface de dépôt affiche les instructions et les critères pour le dépôt d'œuvres.
  - L'utilisateur sélectionne l'œuvre qu'il souhaite déposer.
  - L'application demande des informations supplémentaires sur l'œuvre (titre, description, etc.).
  - L'utilisateur remplit les champs requis et facultatifs selon ses préférences.
  - L'œuvre et les informations associées sont téléchargées sur le serveur de l'application et traitées par le système de gestion de la bibliothèque.
  - L'utilisateur reçoit une confirmation que son œuvre a été déposée avec succès.

   **Scénario Alternatif :** Omission d'Informations Facultatives
   - L'utilisateur, après avoir sélectionné l'œuvre à déposer, choisit de ne pas fournir certaines informations supplémentaires facultatives demandées par l'application.
   - Le système de gestion de la bibliothèque traite les informations manquantes et accepte le dépôt de l'œuvre.
   - L'utilisateur reçoit une confirmation que l'œuvre a été déposée, même avec des informations manquantes.

  **Données :**
   - Informations sur l'œuvre déposée.

  **État Final :** L'œuvre est déposée avec succès dans la bibliothèque publique de l'application.
