# Deployer une application sans code

4. `vercel -c`
5. `vercel init`
6. `vercel deploy`
7. `vercel ls`
8. `vercel log angular-41z1v8rb0.vercel.app`
10. 
11. `vercel env add plain Ma_Variable_de_Prod` 
12. `vercel env ls`
15. `vercel secret add Ma_Variable_Secrete 66`
16.  Production, Preview, Developpment 
17. Cela permet d'effectuer des tests en situation réelle, sans avoir à affecter le fonctionnement du service en production.
19. Un "pull request" est une demande de contribution à un projet (généralement open source), visant à l'améliorer.
  Vercel deploye automatiquement les changements apportés par la pull request.
20. les environnement "preview" et "production" sont actifs.L'environnement "production" était en mode "pending" pendant un moment, j'en déduis donc que notre pull request a été déployée cet environnement là .
21. L'environnement de production correspond à la branche master.
   Les pull requests permettent de comparerle code avant l'ajout d'une nouvelle fonctiannalité, afin de réduire les conflits.
   Un nouveau feature commence généralement sur une branche . Puis est mergé sur une branche 'dev', avant de merger sur la branche master après un pull request réussi.
20. Le serverless consite à confier notre application aux fournisseurs de services cloud (AWS, Azure, Google Cloud), afin qu'ils gèrent la mise à disposition des ressources nécéssaires au fonctionnement de notre application.
  Une app serverless facilite le travail d'un développeur car il n'a plus à s'occuper du serveur sur lequel son application sera déployée, et peut se focaliser sur le maintien de cette dernière. 


![Angular Logo](https://github.com/vercel/vercel/blob/master/packages/frameworks/logos/angular.svg)

# Angular Example using Vercel

This directory is a brief example of an [Angular](https://angular.io/) app that can be deployed with Vercel and zero configuration.

## Deploy Your Own

Deploy your own Angular project with Vercel.

[![Deploy with Vercel](https://vercel.com/button)](https://vercel.com/import/project?template=https://github.com/vercel/vercel/tree/master/examples/angular)

_Live Example: https://angular.now-examples.now.sh_

### How We Created This Example

To get started with Angular, you can use the [Angular CLI](https://cli.angular.io/) to initialize the project:

```shell
$ ng new
```
