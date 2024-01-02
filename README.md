# Digital Lib

**Création d'une bibliothèque numérique décentralisée pour le partage d'œuvres variées.**

## Description du projet

**L\'association *CultureDiffusion* souhaite réaliser une bibliothèque
numérique à gestion décentralisée.**

**Le principe est de permettre à chaque *membre* de *numériser* les
*œuvres* et aux *bibliothécaires* de les *proposer à l\'emprunt* selon
deux modalités :**

**- Toutes les *œuvres du domaine public* sont *accessibles gratuitement.***

**- Toutes les *œuvres sous droits* sont proposées en *location* pour une
période de *2 semaines*.**

Lorsqu\'une œuvre *passe dans le domaine public*, elle devient
*accessible gratuitement* et *est diffusée aux membres* *ayant accordé*
à *l\'application* *suffisamment d\'espace disque*.

Chaque *membre* de la *bibliothèque* peut *emprunter* ou *louer* une
*œuvre*.

Chaque *membre* peut *proposer* une œuvre et ainsi *enrichir* la
*bibliothèque*.

Chaque *œuvre* est constituée d\'un *fichier* contenant l\'œuvre et
d\'un fichier au *format json* contenant *les informations sur
l\'œuvre*.

L\'application bibliothèque possède un *index* des œuvres qui est *mis à
jour* à chaque *ajout* ou *suppression* d\'œuvre.

L\'application possède quatre *rubriques* proposées sous forme de
*répertoires*.

Un répertoire \"*fond\_commun*\" avec une partie des œuvres *libres de
droits* de *l\'association*.

Un répertoire \"*emprunts*\" avec les *œuvres* sous droit empruntées par
le *membre* qui sont *chiffrées* avec sa *clé*.

Un *répertoire \"séquestre\"* avec une partie des *œuvres* sous *droit*
gérée par *l\'association*, *tous les fichiers y sont chiffrés*,
*l\'index* n\'y est pas *accessible de façon directe*.

Un *répertoire \"à modérer\" *avec les *œuvres* que le *membre* a
*proposées*.

Lorsqu\'une *œuvre* est *proposée* par un membre, elle est *soumise à
modération*.

Les *bibliothécaires* *voient les œuvres soumises*, vérifient et
complètent les *données* telles que les *auteurs*, *éditeur*, *langue*,
*pays d\'origine*, *date de publication*, *droits*, *catégorie de
l\'œuvre*, *format du support*, puis ils décident du *statut de
l\'œuvre* et donc si elle est dans le domaine public ou non, ou si elle
est *rejetée*.

Selon le statut de l\'*œuvre modérée*, l\'application *range* dans la
bonne *rubrique* et *gère* les *droits d\'accès*.

Si l\'*œuvre* est dans le *domaine public* il peut y en avoir autant de
*copie* qu\'il y a de membre.

Si l\'*œuvre* est *protégée* alors il ne peut y avoir que *3 fois plus
de copies* que de *licence d\'exploitation*, et chaque œuvre est
*chiffrée* par une *clé différente* ayant une *date de validité*.

À la *fin de la validité d\'un emprunt*, l\'application bibliothèque
supprime automatiquement l\'œuvre du répertoire du membre.

Les œuvres sont classées selon les types et sous-types suivants :

Article

Livre : BD - Enfants - Romans - Livre technique - Education - Loisir - Culture - Sante - etc

Musique : Classique - Jazz/Funk/Soul - Pop - Metal - etc

Vidéos : SF - Histoire - Série - Documentaire - etc

Certaines œuvres appartiennent à plusieurs catégories en même temps.

## Glossaire

1. **Association :** Personne morale au sens de la loi 1901, regroupant des membres partageant des intérêts communs, telle que CultureDiffusion.

2. **CultureDiffusion :** Nom de l'application informatique développée par l'association pour la réalisation d'une bibliothèque numérique à gestion décentralisée.

3. **Bibliothèque numérique :** Application informatique fonctionnant métaphoriquement comme une bibliothèque/médiathèque physique, permettant la gestion décentralisée d'œuvres numérisées.

4. **Gestion décentralisée :** Mode de gestion où les administrateurs et les bibliothécaires accèdent à l'application depuis différents lieux et moments. Les œuvres sont stockées sur les terminaux des membres avec des protocoles de partage pair à pair et de contrôle de version.

5. **Membre :** Individu ayant un compte sur l'application CultureDiffusion, pouvant numériser, emprunter, louer, et proposer des œuvres.

6. **Numériser :** Processus de création d'une version numérique d'une œuvre, tel que le scan d'un livre.

7. **Œuvres :** Créations ou réalisations humaines ayant généralement un intérêt artistique, incluant des livres, articles, musiques, vidéos, etc.

8. **Bibliothécaires :** Membres de l'application responsables du classement des œuvres, de la vérification des informations, et de la modération.

9. **Proposer à l'emprunt :** Action des bibliothécaires permettant de rendre une œuvre disponible à l'emprunt.

10. **Œuvres du domaine public :** Créations dont les droits moraux permettent leur usage gratuit, généralement parce que l'auteur est décédé depuis plus de 70 ans.

11. **Fichier :** Conteneur numérique d'une œuvre, comprenant le contenu de l'œuvre.

12. **Format json :** Format de fichier utilisé pour stocker les informations structurées sur une œuvre.

13. **Informations sur une œuvre :** Données telles que les auteurs, éditeur, langue, pays d'origine, date de publication, droits, catégorie de l'œuvre, format du support, etc.

14. **Index :** Liste organisée des œuvres dans l'application, mise à jour à chaque ajout ou suppression d'œuvre.

15. **Index mis à jour :** Processus de modification de l'index suite à l'ajout ou la suppression d'une œuvre.

16. **Mise à jour de l'index :** Action de mettre à jour la liste des œuvres dans l'index.

17. **Ajout d'une œuvre :** Processus d'intégration d'une nouvelle œuvre dans l'application.

18. **Suppression d'une œuvre :** Processus de retrait d'une œuvre de l'application.

19. **Rubriques :** Catégories principales proposées sous forme de répertoires dans l'application.

20. **Répertoires :** Organisations de stockage des œuvres, tels que "fond_commun," "emprunts," "séquestre," et "à modérer."

21. **Fond_commun :** Répertoire contenant une partie des œuvres libres de droits de l'association.

22. **Fichier chiffré :** Œuvre sécurisée par un cryptage, empêchant un accès non autorisé.

23. **Clé :** Code permettant de déchiffrer une œuvre chiffrée.

24. **Répertoire "séquestre" :** Stockage sécurisé des œuvres sous droits gérées par l'association, avec fichiers chiffrés et un index non accessible directement.

25. **Fichiers chiffrés :** Œuvres protégées par un chiffrement pour empêcher l'accès non autorisé.

26. **Accessible de façon directe :** Caractéristique du répertoire "séquestre" où l'index n'est pas accessible directement.

27. **Répertoire "à modérer" :** Espace dédié aux œuvres soumises par les membres, en attente de modération.

28. **Soumise à modération :** Œuvre proposée par un membre, en attente d'approbation par les bibliothécaires.

29. **Voir les œuvres soumises :** Action des bibliothécaires permettant de visualiser les propositions d'œuvres.

30. **Données :** Informations complémentaires sur une œuvre, telles que les auteurs, éditeur, langue, etc.

31. **Auteurs :** Personnes ayant créé l'œuvre, pouvant être plusieurs.

32. **Éditeur :** Entité responsable de la publication de l'œuvre.

33. **Langue :** Langue dans laquelle l'œuvre a été créée ou traduite.

34. **Pays d'origine :** Pays associé à la création de l'œuvre.

35. **Date de publication :** Moment où l'œuvre a été rendue publique.

36. **Droits :** Ensemble des permissions et restrictions associées à une œuvre.

37. **Catégorie de l'œuvre :** Classification de l'œuvre par type, comme Livre, Musique, Vidéo, etc.

38. **Format du support :** Nature du support physique ou numérique de l'œuvre.

39. **Statut de l'œuvre :** Ensemble d'informations déterminant si une œuvre est dans le domaine public, protégée, ou rejetée.

40. **Fichier rejeté :** Fichier dont le partage a été refusé par les bibliothécaires après modération.

41. **Œuvre modérée :** Œuvre soumise à modération par les bibliothécaires.

42. **Range dans la bonne rubrique :** Processus d'organisation de l'œuvre dans la catégorie appropriée après modération.

43. **Gère les droits d'accès :** Attribution des droits d'accès en fonction du statut de l'œuvre après modération.

44. **Domaine public :** Statut indiquant que l'œuvre est libre de droits et peut être copiée par autant de membres que nécessaire.

45. **Copie :** Duplication d'une œuvre libre de droits autorisée sans restriction.

46. **Œuvre modérée :** Œuvre soumise à modération par les bibliothécaires.

47. **Range dans la bonne rubrique :** Processus d'organisation de l'œuvre dans la catégorie appropriée après modération.

48. **Gère les droits d'accès :** Attribution des droits d'accès en fonction du statut de l'œuvre après modération.

49. **Domaine public :** Statut indiquant que l'œuvre est libre de droits et peut être copiée par autant de membres que nécessaire.

50. **Copie :** Duplication d'une œuvre libre de droits autorisée sans restriction.

51. **Œuvre protégée :** Statut indiquant que l'œuvre est soumise à des droits, limitant le nombre de copies et nécessitant un chiffrement individuel.

52. **3 fois plus de copies :** Limite de trois duplications pour une œuvre protégée, en fonction du nombre de licences d'exploitation.

53. **Licence d'exploitation :** Autorisation légale d'utiliser une œuvre soumise à des droits, déterminant le nombre de copies autorisées.

54. **Date de validité :** Période pendant laquelle une œuvre protégée peut être utilisée, définie par une clé de chiffrement.

55. **À la fin de la validité d'un emprunt :** Processus de suppression automatique d'une œuvre du répertoire du membre à la fin de la période de location.

56. **Œuvres classées selon les types et sous-types :** Organisation des œuvres en catégories et sous-catégories spécifiques.

57. **Article :** Type d'œuvre comprenant des écrits courts et informatifs.

58. **Livre :** Catégorie d'œuvres comprenant divers sous-types tels que BD, Enfants, Romans, Livre technique, Éducation, Loisir, Culture, Santé, etc.

59. **BD :** Sous-type de Livre, regroupant les bandes dessinées.

60. **Enfants :** Sous-type de Livre, spécifique aux œuvres destinées à un jeune public.

61. **Romans :** Sous-type de Livre, englobant les œuvres de fiction narratives.

62. **Livre technique :** Sous-type de Livre, incluant des ouvrages spécialisés.

63. **Éducation :** Sous-type de Livre, comprenant des œuvres pédagogiques.

64. **Loisir :** Sous-type de Livre, regroupant des œuvres de divertissement.

65. **Culture :** Sous-type de Livre, englobant des œuvres liées à la culture générale.

66. **Santé :** Sous-type de Livre, incluant des ouvrages sur la santé.

67. **Musique :** Catégorie d'œuvres regroupant des sous-types tels que Classique, Jazz/Funk/Soul, Pop, Metal, etc.

68. **Classique :** Sous-type de Musique, englobant des œuvres musicales classiques.

69. **Jazz/Funk/Soul :** Sous-type de Musique, regroupant des œuvres de jazz, funk et soul.

70. **Pop :** Sous-type de Musique, incluant des œuvres musicales populaires.

71. **Metal :** Sous-type de Musique, spécifique aux œuvres musicales metal.

72. **Vidéos :** Catégorie d'œuvres incluant des sous-types tels que SF, Histoire, Série, Documentaire, etc.

73. **SF :** Sous-type de Vidéos, regroupant des œuvres de science-fiction.

74. **Histoire :** Sous-type de Vidéos, comprenant des œuvres historiques.

75. **Série :** Sous-type de Vidéos, englobant des séries télévisées.

76. **Documentaire :** Sous-type de Vidéos, spécifique aux œuvres documentaires.

77. **Certaines œuvres appartiennent à plusieurs catégories en même temps :** Possibilité pour une œuvre d'être classée dans plusieurs catégories ou sous-catégories en fonction de ses caractéristiques.

## Glossaire technique et concepts introduits par les scénarios :

78. **Anonyme :** Utilisateur non encore authentifié ou n'ayant pas de compte sur l'application CultureDiffusion.

79. **Téléchargement de l'application :** Processus d'obtention de l'application CultureDiffusion sur le terminal de l'utilisateur.

80. **Installation de l'application :** Processus d'implémentation et de configuration de l'application CultureDiffusion sur le terminal de l'utilisateur.

81. **Utilisateur :** Catégorie regroupant les rôles d'Anonyme, Membre, et Bibliothécaire utilisant l'application.

82. **Média :** Support permettant d'exécuter l'application de la bibliothèque décentralisée, tel qu'un smartphone, une tablette, ou un ordinateur.

83. **Membre authentifié :** Membre dont la connexion s'est faite avec FranceConnect, un système d'authentification français.

84. **Numéro de transaction :** Identification unique associée à chaque opération réalisée dans l'application CultureDiffusion.

85. **Fichier journal local :** Fichier contenant un historique de toutes les opérations effectuées par le membre, stocké localement.

86. **Filtre :** Mécanisme permettant de masquer des éléments indésirables dans une liste.

87. **Tri :** Processus d'ordonnancement des éléments d'une liste selon des critères spécifiques.

