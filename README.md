# Méta-dépôt des travaux autour de la Base Adresse Nationale

Bonjour et encore merci de tester l’API BAN.

Le test de l’API BAN, qui durera jusqu’à mi avril, permettra d’améliorer la BAN et l’API. Votre rôle est de tester fonctionnellement l’API (prise en main, fonctionnalités, droits, synchronisation avec votre SI, documentation,…) mais aussi d’évaluer les données adresse sur vos départements (qualité, exhaustivité, homogénéité, liens entre objets, doublons, documentation…) puis nous faire des retours. 

Cette BAN test est en cours d’amélioration. Elle a été initialisée à partir de différents sources (INSEE, La Poste, IGN, FANTOIR, DGFIP/BANO). Le processus d’initialisation est décrit sur le github https://github.com/BaseAdresseNationale/donnees-initiales/tree/master/scripts 


Tout d’abord, il faut que validiez la charte d’expérimentation par mail (api-ban@ign.fr), qui fait office de CGU pendant la phase d’expérimentation. Elle se trouve https://github.com/BaseAdresseNationale/charte-experimentation/blob/master/CHARTE.md

Par vos inforations de connexion, vous pourrez créer des token dans l’API, qu’il vous faudra redemander selon la procédure décrite dans https://github.com/BaseAdresseNationale/ban/wiki/Documentation-utilisateur-de-l'API-de-gestion. Cette documentation est plus générale puisqu’elle décrit toute l’API et notamment comment accéder aux différentes ressources. Quant aux ressources accessibles, elles sont décrites dans https://github.com/BaseAdresseNationale/ban/wiki/Ressources-de-l'API-de-gestion. 
Vos droits sont classiques et consistent en la lecture et l’écriture de 3 classes principales du modèle : les Group (qui sont en général les voies et les lieux-dits), les Housenumber (les adresses) et les Position.

Enfin, pour des questions et des retours à  l’équipe technique BAN, vous utiliserez au choix :
- le forum https://gitter.im/BaseAdresseNationale/api-gestion 
- ou la liste de diffusion api-ban@ign.fr 

De notre côté, nous communiquerons vers les béta-testeurs en utilisant les mêmes médias.

