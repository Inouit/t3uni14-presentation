<!-- .slide: data-breadcrumb="typo3,skinDummy : la base" -->
#Extension
##*skinDummy*
<table class="reveal">
    <tr valign="middle">
        <td width="50%" style="vertical-align: middle"><img src="img/screen1.png" class="fragment shrink"  data-fragment-index="1" width="405" alt=""/></td>
        <td width="50%" style="vertical-align: middle"><img src="img/screen2.png" class="fragment grow"  data-fragment-index="1" width="311" alt=""/></td>
    </tr> 
</table>


note:
Typo3 est installé ! Premier constat : en lieu et place des pages d'erreurs que nous avons tous pris l'habitude de voir, j'ai un site pré-configuré. Détaillons ce que le script de duplication a installé.<br />
Une première extension : **skinDummy**. Si elle n'apporte pas de réelle évolution, elle sert de base à tout ce qui va suivre. Cette extension est un **modèle** que d'autres plugins viendront **surcharger**.<br /> 
Elle contient principalement des éléments par défaut (**relation backend_layout** / **gabarit frontend**, un **menu pré-construit**, les **requêtes de récupération de contenus de colonnes**, ...)<br />
Elle contient également une configuration basique du backend (pour l'**éditeur wysiwyg** par exemple). Et c'est tout ! Cette extension représente ce que vous aurez de commun à tous vos sites.<br />
**Pourquoi l'isoler du reste ?** Pour que vous n'ayez pas à nettoyer une installation trop complète. Comprenez que dans cette partie, comme dans toute la présentation, nous ne cherchons pas à avoir l'installation la plus complète possible, mais bien celle qui nous fera gagner un maximum de temps. Dans ce cas, comme souvent en développement, il est bien **plus facile d'ajouter** des fonctionnalités **que d'en supprimer proprement**. Ces choix pour skinDummy sont ceux qui correspondent à nos besoins. A vous de l'adapter à **vos besoins**.