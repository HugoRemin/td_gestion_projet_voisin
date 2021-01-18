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

1.18 https://github.com/HugoRemin/td_gestion_projet_voisin

