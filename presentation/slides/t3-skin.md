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
  We've just talk about theme, skin is your theme extension. In this plugin, you will store your templates, assets, typoscript configuration, hooks, ... If skinDummy never change, skin will evolve a lot during the project. However, it could contain some default configuration but once again, nothing that unnecessary<br />
  Watch out: this plugin must be independant. In the future, if you have to build another skin, you should be able to remove the old one without residual code that will trouble the new one.