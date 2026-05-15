#  Modifications/apprentissages

## Modifier le titre des alertes

[Lien vers la documentation au sujet des callouts et des alertes](https://support.typora.io/What's-New-1.8/)

[Explication de comment faire un CSS Custom.](https://support.typora.io/Add-Custom-CSS/)



J'ai fait : modifier le nom d'affichage des alertes. Elles conservent leur façon habituelle de faire l'«appel» dans Typora, mais un fichier custom *everforest-light.user.css* apporte la possibilité de modifier l'affichage avec une commande de style : 

```
.md-alert-text-warning .md-alert-text-container:after {
  content: "Avertissement";
}
```

où «warning» est le nom officiel de l'alerte (utile pour l'appeler) et «Avertissement» devient ce qui est affiché lors de la production du document.





Voici le résultat.

> [!NOTE]
>
> pas modifié

> [!TIP]
>
> fait partie du css custom nommé *everforest-light.user.css*

> [!CAUTION]
>
> fait partie du css custom nommé *everforest-light.user.css*

> [!IMPORTANT]
>
> pas modifié

> [!WARNING]
>
> fait partie du css custom nommé *everforest-light.user.css*



## Page break

Insérer

```
<div style="page-break-after: always;"></div>
```

Permet de forcer un saut de page

Je ne sais pas ce que ça fait une fois dans la page web, par exemple.



test (je place cette ligne qui deviendra invisible après)

<div style="page-break-after: always;"></div>

2e page?



oui en pdf, NON en html (voir image)

<img src="/Users/luctremblay/Library/Application Support/typora-user-images/image-20251221215548205.png" alt="image-20251221215548205" style="zoom:50%;" />



Sinon, un test avec triple étoile sur la ligne sous celle-ci

***

ne change rien en pdf

## Section 1.4 - La fonction rationnelle

## sous-titre 1

| $ f(x) = {1}\over x $<br/><br/><br/><br/>blabla<br/> | ![image-20251221103304181](/Users/luctremblay/Library/Application Support/typora-user-images/image-20251221103304181.png) |
| :--------------------------------------------------: | ------------------------------------------------------------ |
|                                                      |                                                              |
|                                                      |                                                              |

> [!NOTE] 
>
> asdfsdf

Sdf



> [!TIP] 
>
> Conseil




