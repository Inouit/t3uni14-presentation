(19:00)
ensuite, je vais ajouter un champ étiquette.
- Pour ceux qui ne verraient pas la vidéo et qui n'écouteraient que l'audio, on voit un script en ligne de commandes qui nous permet de construire tous les champs de notre contenu flexible un par un. On choisit le type de champ : input, textarea, ... C'est comme remplir un formulaire. On construit le contenu flexible avec un guide étape par étape qui créé automatiquement toute la configuration.
- Tout à fait. On voit qu'il a créé la configuration backend, la configuration frontend, la localisation en deux langues. Le contenu flexible est automatiquement ajouté à la liste des contenus de typo3. Comme on lui a demandé, des fichiers CSS et JS sont inclus. Bien évidemment les scripts sont vides, ne vous attendez pas à voir un diagramme en donut tout de suite mais tous les éléments sont déjà présent.
- C'est un kickstarter en fait. Comme si on créer une extension automatiquement pour notre contenu.
- Un des points intéressants, et c'est pour ça que nous mettons nos FCE dans skinFlex, c'est que l'on peut exporter chacun d'entre eux puisqu'ils sont totalement indépendants du site, et les importer ailleurs. Si nous ne les stoquons pas dans skin, c'est parce que ces éléments sont indépendants. 
Clément va nous montrer ce que ça donne à travers une démo.
- Vous le verrez par la suite mais l'intégralité des scripts est disponible sur github et pour ce générateur, nous avons ajouté la possibilité de créer des liens vers des pages ou url externes et de faire des listes déroulantes de plusieurs choix. Vous pourrez donc créer une liste de choix couleur verte, couleur orange, etc. et le flexform sera l'intégrera automatiquement. Ce n'est pas encore disponible. C'est en cours. Il n'y a plus qu'à valider le code de notre stagiaire (JuJulien). Il y aura aussi bientôt une fonction d'export automatique qui construira un zip de tous les fichiers.
- Est-ce qu'on peut ajouter une zone de contenus libres qui permettrait d'ajouter n'importe qu'elle type de contenu à l'intérieur.
- En fait, ce besoin correspond d'avantage à l'autre versant de gridelement qui est du colonnage. Nous l'avons pour Bonduelle, mais le générateur ne le fait pas.
- Tu as dis le nom.
- Ah ! Pardon... en même temps, quand c'est bon...
Le générateur ne le permet pas actuellement car il s'agit de deux parties bien distinctes de la configuration, mais ça serait tout à fait envisageable.
- Qu'est-ce qui est créé au juste quand on utilise Yeoman ?
- Nous allons voir ça dans le backend de Typo.
- Au passage, on voit le système de colonnage mis en place. Ce dernier est créé avec gridelement et installé de base dans le dummy qu'on a dupliqué plus tôt.

Ce que vous voyez actuellement, c'est la distribution que nous allons mettre à votre disposition. D'ailleurs si vous souhaitez vous logguer, nous avons simplement mis admin/password
- Nous allons ajouter un nouveau type de flexible content. L'icône a même déjà la tête d'un diagramme en donut. Bien évidemment, nous avons un peu triché là dessus. Nous créons un nouveau chart doughnut et nous allons remplire les champs créés plus tôt : le titre...
- Clément aime bien doubler les majuscules.
- Il aime également mettre des titres pourris à ses formulaires, merci Clément. Ensuite, on crée une boucle de chiffre avec l'étiquette, la valeur, la couleur. Puis on ajoute un autre chiffre (étiquette, valeur, couleur). Cette méthode vous permet réellement de faire des contenus flexibles complexes.
Le générateur ne le fais pas automatiquement mais le champ de couleur devrait être un sélecteur de couleur. Vous pouvez donc avoir la main sur le design que le client pourra modifier ou non.
- Ce qu'il faut bien comprendre c'est que seul gridelements est utilisé. Le générateur créé un flexform, du typoscript, feuilles de styles, du JS. Il n'y a aucune dépendance vis à vis de nous. Le générateur se contente de créer les fichiers et faire la liaison entre frontend et backend.
- Clément remplit le flexform. C'est du IRRE ? On peut en créer autant qu'on veut ?
- En fait c'est le système de section des flexforms.
- On crée donc autant de champs qu'on le souhaite. Un titre, une valeur, une couleur. On sauvegarde.
- Mon apache est particulièrement lent.
- Si on rafraîchit la page, c'est très moche...
- Mais les données y sont et il ne manque qu'une template.
- Exactement, il ne manque que le JS, le CSS et modifier le typoscript légèrement puisqu'actuellement il se contente d'afficher les valeurs qui ont été saisies en back. Clément a préconfiguré le rendu final.
- Ici, vous voyez ce que le générateur a préconfiguré.
- Le générateur crée automatiquement les objets typoscripts qui affichent le texte brut et on a plus qu'à wrapper avec du HTML ?
- C'est exactement ça.
- Ça ne vous embête pas d'être payés à rien faire ?
- Encore une fois, notre temps de travail est rempli par la partie intéressante de notre travail.
- Bien sûr. En tout cas, c'est admirable. C'est très intéressant. Même un intégrateur typo3 ferait ça rapidement.
- Vous pouvez donner le générateur à vos designeurs. Tant qu'il s'agit d'afficher simplement des données en front, il saura se débrouiller seul. 
- Vous pouvez voir l'appel au CSS, même si ce dernier reste vide et l'appel au script qui va générer l'affichage du graphique et son initialisation, mais ce n'est pas très intéressant à présenter ici.
- Oui, le but n'est pas de faire une conférence sur le développement frontend.
- Si on rafraîchit le frontend, c'est sensé fonctionné. Du moins, nous l'espérons pour toi Clément.
- FAUX.
- Les caches de typo vous présente l'effet Bonaldi de toutes les conférences.
- Et voilà. Vous pouvez voir en plus, nos libellés.
- C'est un bel exemple de FCE puisque le rendu est très visuel mais ça peut être utilisé pour beaucoup d'autres choses.
- Le premier besoin que l'on a eu, déjà à l'époque de wecce_contentelements, était un slideshow. On peut en faire de très très complet avec même des pages contenues dans un slideshow et le faire slider alors que le client n'a quasiment rien à faire.
- On peut aussi imaginer une fiche de présentation des élus pour une collectivité avec photo, description, biographie.
- Bien sûr, mais il faut faire attention puisqu'un FCE ne remplace pas une extension. Si on doit pouvoir effectuer des requêtes sur les entrées en base de données, il faut toujours faire une extension. Nous sommes d'accord avec la team de gridelements à propos de ce genre de situation sur les flexforms, mais s'il n'y a pas besoin de faire de requêtes sur les données, il faut en profiter.
- Comme pour n'importe quel flexform, ce qui est stocké en BDD est au format XML.
- Xavier a une question.
- Un internaute demande sur les différents outils frontend que vous avez présenté, à quoi correspond le petit oiseau ?
- Bower 
(26:51)