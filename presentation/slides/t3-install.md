<!-- .slide: data-breadcrumb="Installation VS Duplication" -->
# Première étape :

<table class="reveal">
	<thead>
		<tr>
			<th width="48%"><img src="img/ico_install.png" width="50" alt=""/> Installation</th>
			<th width="4%" class="vs">VS</th>
			<th width="48%"><img src="img/ico_clone.png" width="50" alt=""/> Script de duplication</th>
		</tr>
	</thead>
	<tbody>
		<tr>
			<td><ul class="fragment fade-in">
				<li>3 étapes simples</li>
				<li>Installation d'un package</li>
	</ul></td>
			<td>
			<td><ul class="fragment fade-in">
				<li>2 questions (nom d'utilisateur, nom de projet)</li>
				<li>Configuration des extensions systèmatiques</li>
				<li>Configuration Typoscript de base (menus, logo, favicon, ...)</li>
				<li>Déploiement sur plusieurs postes</li>
				<li>Configuration serveur, versionning, fichiers locaux, ...</li>
			</ul></td>
		</tr>
	</tbody>
</table> 

note:
Dois-je installer un typo, où dois-je en dupliquer un ?<br />
Depuis quelques années, nous avons vu fleurir des sites pré-construit, des *installation package*, des *twitter bootstrap*, ... <br />
A nos yeux, ce sont d'**excellents outils pour une présentation**, mais ils sont **peu utilisables** au moment de commencer un site. Pourquoi ? <br /> 
Parce qu'ils font **beaucoup trop de choses** ! Quand j'installe un site, ce qui me préoccupe **en premier** ne devrait pas être de **supprimer des pages**, d'**assainir une feuille de style**. Je n'ai pas non plus envie de configurer un virtual host, de dupliquer mon site sur l'ensemble des serveurs de développement et de test.<br />
Non ! Ce que j'ai envie de faire c'est de commencer le **travail de création** pour lequel j'apporte une **vraie valeur ajoutée**.<br />
Inouit aurait pu choisir de faire un **Inouit Package**, mais comme je viens de le dire, nos besoins vont bien **au-delà du framework**. Aussi nous  sommes nous tournés vers un **script de duplication**. Quelles différences celà fait ?