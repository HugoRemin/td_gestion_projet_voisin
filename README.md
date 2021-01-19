# td_gestion_projet_voisin

1.4 `vercel -v`

1.5 `vercel init angular`

1.6 `cd angular` puis `vercel`

1.7 `vercel ls`

1.8 `vercel logs tdgestionvoisin-mbld223z0.vercel.app`

1.9 `vercel inspect tdgestionvoisin-mbld223z0.vercel.app`

inspect donne des information sur un deployement

1.10 Les variable d'environnement permettent d'injecter des valeurs qu'on ne veux pas placer directement dans le code source et de modifier son comportement en fonction de l'environnement dans lequel il fonctionne.

1.11 `vercel env add plain PASSWORD production`

1.12 `vercel env ls`

1.13 Les variable secrètes sont cryptés et doivent être utilisés pour les informations sensibles comme les mots de passe ou les jetons d'accès. Elle fournisssent également un moyen sécurisé de stocker et de partager des informations sensibles entre les déploiements.

1.15 `vercel secret add username hugo` puis ` vercel env add secret USERNAME production` en donnant le secret username après

1.16 Vercel met à dispostion 3 types : Production, Preview et Development. Plusieurs environnement permet de separer les variables en fonction de l'avancer du porjet. Parexemple un variable development sert pendant le developement et une fois le developement finis prends sa valeur definitive dans prodution. Par exemple un chemin de base de données qui change en fonciton de si on developpe ou si l'application est finie.

1.18 https://td-gestion-projet-voisin.vercel.app/

1.19 Une pull request permet de travailler à coté de la branche fonctionnelle et d'ensuite demander une fusion au gérant de la branche principale

![vercel_pull_request](https://user-images.githubusercontent.com/74649302/104926978-2331b900-59a1-11eb-881b-c0b029fb0602.PNG)

Vercel deploie automatiquement la pull request et c'est l'environement preview qui est activé.

1.20 Vercel deploie automatiquement la branche fusionée dans l'environnement production.

1.21
L'environemment de production correspond à la branche principale du git.

Utiliser des pull request permet de developper un paralelle sans se soucier des conflits avec la branche principale lors d'un push.

Un feature commence à petre developper en créant une nouvelle branche au git. Le vercel la passe en environnement development. Lorsque que la feature est finie un effectue une pull request qui fait passer à l'environemment preview. Et enfin la pull request est acceptée et la nouvelle branche fusionne avec la branche pirncipale ce qui passe la feature à l'environnement production.

1.22

Le serverless c'est quand un fournisseur de cloud fournit les ressources à la demande aux application. Malgrès son nom le serverless utilise des serveurs c'est que le devellopeur n'a pas à gerer les serveurs. Le premier interret est que celà facilite le passage d'une application en production. De plus le coût est généralement moins élévées que de créer ses propres serveurs.




