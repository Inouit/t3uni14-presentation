<!-- .slide: data-breadcrumb="typo3,skin : the theme" -->
#Extension
##*skin*
<table class="reveal">
  <tr valign="middle">
    <td width="50%" style="vertical-align: middle"><img src="img/screen2.png" class="fragment shrink"  data-fragment-index="1" width="405" alt=""/></td>
    <td width="50%" style="vertical-align: middle"><img src="img/screen3.png" class="fragment grow"  data-fragment-index="1" width="311" alt=""/></td>
  </tr>
</table>

note:
  Nous parlions de thème, voici l'extension qui s'en occupe : skin. C'est dans cette extension que vous placerez vos templates HTML, CSS, JS, la configuration typoscript liée à l'intégration, la configuration définitive des extensions, ... Si skinDummy est inamovible, skin va évoluer au fur et à mesure du projet. De base elle contient déjà un peu de configuration, amenée à changer, mais surtout rien de superflu. <br />
  Pensez aussi à en faire un plugin totalement autonome. Si vous êtes amenés à refondre le site, vous devriez être en mesure de désinstaller skin et en créer un nouveau sans qu'aucun résidu ne vienne perturber le remaniement.
