### Test des commandes git reflog et git reset

![capture du terminal](/img/screenshot.png)

**Objectifs** : s'habituer à travailler avec git, en solo même sans pusher.

Au tout début, je croyais qu'il fallait faire un commit *uniquement* s'il fallait  pusher sur un repo.
Mais c'était avant :smile:
Aujourd'hui,  sur mon ordi, je peux revenir à une version antérieure de mon taf grâce à l'historique des actions obtenu par la commande ```git reflog```

Je n'ai qu'à choisir l'état vers lequel je souhaite revenir en tapant dans mon terminal :
  ```git reset --soft HEAD@{x}``` (modifs conservées ) ou ```git reset --hard HEAD@{y}``` (modifs NON conservées)
  
  Et mes fichiers rajeunissent ! 
  
  J'ai capté l'utilité *d'immortaliser* l'instant où mon code fonctionne bien :thumbsup: 
Car si  je rajoute des choses qui ne marchent pas du tout par la suite (ce qui m'arrive très souvent ),   je peux choisir sereinement de revenir à un état antérieur, sans prendre le risque de supprimer les bonnes lignes de code - surtout en fin de journée :tired_face: .
C'est **git** qui se chargera de me faire revenir pile où je veux.

Et je push, seulement si nécessaire : c'est plus écolo :deciduous_tree:  :wink:

[**=> résultat**](https://dianatecher.github.io/github-training/)
