# ban
Méta-dépôt des travaux autour de la Base Adresse Nationale

Bonjour et merci de vous être portés volontaires pour tester l’API BAN !

Nous sommes entrés dans une phase de test de l’API, qui durera jusqu’à mi octobre, dans le but d’améliorer la BAN et l’API. Votre rôle est de tester fonctionnellement l’API (prise en main, fonctionnalités, droits, synchronisation avec votre SI, documentation,…) mais aussi d’évaluer les données adresse sur vos départements (qualité, exhaustivité, homogénéité, liens entre objets, doublons, documentation…) puis nous faire des retours. Vos retours seront priorisés pour faire évoluer les outils de l’API BAN. Actuellement, voici les départements dans la BAN https://github.com/BaseAdresseNationale/donnees-initiales/blob/master/departements.csv, choisis en priorité selon vos zones d’influence. Cette BAN test est un premier essai de BAN et est en cours d’amélioration (cf tickets ouverts sur le github), ce qui se confirmera grâce à vos retours. Elle a été initialisée à partir de différents sources (INSEE, La Poste, IGN, FANTOIR, DGFIP/BANO). Le processus d’initialisation est décrit sur le github https://github.com/BaseAdresseNationale/donnees-initiales/tree/master/scripts 


Tout d’abord, il faut que validiez la charte d’expérimentation par mail (api-ban@ign.fr), qui fait office de CGU pendant la phase d’expérimentation. Elle se trouve https://github.com/BaseAdresseNationale/charte-experimentation/blob/finalisation-xp/CHARTE.md

Puis, d’un point de vue pratique, nous allons vous donner individuellement par mail vos informations de connexion dans un second mail, consistant en 2 données : un client_id et un client-secret. Ces 2 données vous permettront de créer des token dans l’API, qu’il vous faudra demander tous les jours, selon la procédure décrite dans https://github.com/BaseAdresseNationale/api-gestion/wiki/Documentation-utilisateur-de-l'API-de-gestion. Cette documentation est aussi plus générale puisqu’elle décrit l’API, notamment comment utiliser le token et comment accéder aux différentes ressources. Quant aux ressources accessibles, elles sont décrites dans https://github.com/BaseAdresseNationale/api-gestion/wiki/Ressources-de-l'API-de-gestion. 
Vos droits sont classiques et consistent en la lecture et l’écriture de 3 classes principales du modèle : les Group (qui sont en général les voies et les lieux-dits), les Housenumber (les adresses) et les Position.

Enfin, la communication pendant cette période de test est primordiale. En cas de questions pour l’équipe technique BAN, vous utiliserez au choix :
- le forum https://gitter.im/BaseAdresseNationale/api-gestion où on vous répondra directement si nécessaire
- ou la liste de diffusion api-ban@ign.fr 
En cas de retours, vous pouvez également utiliser les tickets github de la BAN : s’ils concernent la base de données initiale https://github.com/BaseAdresseNationale/donnees-initiales/issues et s’ils concernent l’API https://github.com/BaseAdresseNationale/api-gestion .

De notre côté, nous communiquerons vers les béta-testeurs
-	une liste de retours des tests identifiés au fil de l’eau sur les tickets github, de la base de données initiale ou de l’API
-	des évolutions techniques de l’API ou l’ajout de départements de tests par mail et sur le forum

