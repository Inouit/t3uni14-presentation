<!-- .slide: data-breadcrumb="typo3,skinFlex" -->
#Extension
##*skinFlex*
<table class="reveal">
  <tr valign="middle">
    <td width="50%" style="vertical-align: middle"><img src="img/screen3.png" class="fragment shrink"  data-fragment-index="1" width="405" alt=""/></td>
    <td width="50%" style="position: relative; vertical-align: middle"><img src="img/screen4.png" class="fragment grow"  data-fragment-index="1" width="311" alt=""/>
      <img src="img/screen5.png" class="fragment fade-in"  data-fragment-index="3" style="position: absolute; top: 0; bottom: 0; left: 0; right: 0;" width="405" alt=""/>
    </td>
  </tr>
</table>

note:
  Based on gridelements, this extension allow you to rearrange contents in columns... and a bit more. Our clients want to custom columns with border, background, margin, etc. It handles that too.<br />
  This plugin is a storage for flexible content elements too. In Typo3, you can make prebuilt content with advanced layout that will be very easy to fill by the integrator, without getting his hand dirty by complex combination of wysiwig editor's style. This kind of content are called Flexible Content Elements a.k.a. FCE. Using it or not is not the subject here. Our clients need it, maybe yours too. In that case, you have to store all of your FCE in an independant extension, not in skinDummy cause it's not common code; not in skin, cause all of these contents are independant from the theme... skinFlex can be a great storage folder for this case.