<!-- .slide: data-breadcrumb="typo3,skin : le thème" -->
#Extension
##*skin*
<table class="reveal">
    <tr valign="middle">
        <td width="50%" style="vertical-align: middle"><img src="img/screen2.png" class="fragment shrink"  data-fragment-index="1" width="405" alt=""/></td>
        <td width="50%" style="vertical-align: middle"><img src="img/screen3.png" class="fragment grow"  data-fragment-index="1" width="311" alt=""/></td>
    </tr> 
</table>

note:
L'extension skin correspond au **thème de votre site**. Elle vient **puisez des éléments dans skinDummy**, en **surcharger** d'autre et représente ce qui sera au final le **coeur de votre projet**. Vous y déclarez vos **templates**, vos blocs de **configuration typoscript**, vos **assets**, la **surcharge des extensions**, ... L'intégralité de votre intervention sur le site est stocké ici.<br />
Si vous êtes amenés quelques années après la création du site, à le refondre entièrement, vous supprimez l'extension, en créez une nouvelle et vous n'aurez laissé aucune trace de votre premier passage.<br />
Notre choix est que skin contienne de base une **template** ainsi que les **feuilles de style** et **scripts** qui lui sont associés mais surtout, rien de superflu ! Si vous souhaitez utiliser bootstrap ou autre, vous êtes libres de le faire, et ça peut tout à fait s'inscrire dans cette démarche. Mais une fois de plus, pour nous, **le trop est l'ennemi du bien** et je vous enjoints à trouver le même équilibre pour simplifier vos débuts de projet.