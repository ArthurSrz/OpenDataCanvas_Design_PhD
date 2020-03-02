---
auteur: Arthur Sarazin
number_sections: TRUE
output:
  pdf_document: 
    latex_engine: xelatex
  html_document: default
---

## 1.2 Le rôle et la place des plateformes de services dans les smart city

 Résumé | 
------------ | 
Lorem ipsum | 


#### Définition d'une plateforme de services selon Pitt et al. (2017) : un lieu virtuel au croisement entre les systèmes cyber-physiques et socio-techniques.

Un système cyber-physique intègre des objets informatiques (ex : caméras, capteurs)  et des artefacts matériels (ex : ordinateurs, serveurs) dans le but de capter, d’analyser et d’exploiter des données sur un espace physique (ex : une ville). Parmi les nombreux exemples de tels systèmes, décrivons le système de localisation du Syndicat Mixte de Transports en Commun (SMTC) de la ville de Grenoble. Chaque bus et tram de la ville possède des capteurs qui permettent de les géolocaliser. Ces données sont collectées par des serveurs appartenant à la métropole grenobloise qui, grâce à elles, peut organiser et gérer les transports communs de la ville en temps réel. 

Un système socio-technique se définit comme le point de rencontre entre d’un côté des individus, organisations, institutions, communautés et sociétés, et de l’autre, des machines et technologies. L’Open lab La Péniche à Grenoble constitue un système socio-technique à part entière dans la mesure où il rassemble les parties prenantes de l’Open data au sein de lieux physiques et virtuels et met à disposition des machines et technologies permettant de créer des services issus des données. 

#### La place centrale de la plateforme de services dans la smart city : regard de la service-dominant logic (Lusch et Nambisan, 2015) 

La service-dominant logic est un cadre conceptuel selon lequel la smart city est constituée de 3 éléments (Lusch et Nambisan, 2015)  : 

- un écosystème de services défini comme un système relativement autonome et autorégulé composé d'acteurs sociaux et économiques faiblement liés, reliés par des logiques institutionnelles partagées et une création de valeur mutuelle via l'échange de services. 
- une plateforme de services définie comme une structure modulaire composée d’éléments tangibles et intangibles qui facilite l'interaction des acteurs et des ressources.
- la co-création de valeur qui se comprend comme les processus et activités qui sous-tendent l'intégration des ressources et intègrent différents rôles d'acteur dans l'écosystème de services.

Prenant appui sur ces éléments, nous pouvons définir la smart-city comme un écosystème de services qui se construit autour d’une plateforme de services dans le but de co-créer de la valeur. Au coeur de cette définition se trouve le concept de plateforme de services. 

Au croisement entre l’écosystème et la co-création de valeur, la plateforme de service permet dans un premier temps de centraliser les nombreuses ressources détenues par chaque membre de l’écosystème ou,  pour reprendre les termes les termes de Lusch et Nambisan (2015, p. 157), de “maximiser leur densité”.  Dans un deuxième temps, la plateforme facilite la dynamisation des échanges de ressources entre les membres de l’écosystème de la Smart City. Autrement dit, elle augmente la liquidité des ressources.  Enfin, forte d’une densité importante de ressources liquides, la plateforme constitue le lieu d’élection pour développer des mécanismes de co-création de services entre les membres de l’écosystème. 

Etant donné la place centrale qu’occupe la plateforme dans la co-création de services, nous étudierons dans les parties suivantes, les dimensions des plateformes de services ayant une influence sur la co-création de services. 

#### Le rôle clé des plateformes de services dans la smart city : un vecteur d’innovation ouverte de services

La capacité d’une plateforme de services à générer de l’innovation de services dépend de 3 caractéristiques : son architecture, la capacité d’évolution de l’architecture et sa license d’utilisation. 

L’architecture d’une plateforme se définit comme le schéma conceptuel décrivant les composants stables et homogènes de la plateforme, les modules hétérogènes qui gravitent autour de ces composants, et les règles de design qui régissent l’articulation entre ces deux éléments (Tiwana et al., 2010). L’architecture d’une plateforme possède des fonctions primaires qui constituent le coeur de la valeur d’une plateforme ainsi que des fonctions secondaires (dites “ilités”) dont la valeur varie en fonction du cycle de vie de la plateforme : durabilité, maintenabilité, flexibilité, etc.  

Pour qu’une plateforme se maintienne et se développe, elle doit intégrer des modules de plus en plus hétérogènes sans pour autant détériorer les composants stables qui permettent les agencements entre ces derniers. Cette dialectique constitue à la fois le moteur du développement des plateformes et la principale problématique pour les architectes des plateformes qu’ils résolvent grâce à un certain nombre de règles de design.  

Une des caractéristiques critiques d’une plateforme réside dans sa license d’utilisation (Pitt et al., 2017). On distingue principalement les plateformes sous licence propriétaire, détenues par un seul acteur dont l’accès est conditionné par le paiement d’une redevance ou par le consentement à voir ses données personnelles utilisées et les plateformes sous license ouverte, dont l’accès est gratuit et dont le code source peut être modifié par toutes les personnes y voyant un intérêt. Le choix d’une license propriétaire ou ouverte est crucial dans la mesure où il influence la manière dont les parties prenantes échangent des ressources. Plus précisément, une plateforme sous license propriétaire amène à une asymétrie dans la distribution des ressources qui peut inhiber l’action collective issue des échanges entre les membres de l’écosystème et donc la co-création de service. A l’inverse, une plateforme sous license ouverte facilite la distribution de ressources, démocratise son utilisation au profit de mécanismes de co-création de services plus participatifs. 

#### Les mécanismes de gouvernance génériques des plateformes de services 

Les mécanismes de gouvernance d’une plateforme correspondent aux processus mis en place pour administrer les opérations des deux côtés de la plateforme et maintenir son écosystème (Tiwana et al., 2010). En effet, comme l’indique le schéma ci-dessous tiré d’Eisenmann et al. (2008), une plateforme se positionne comme un intermédiaire entre deux types d’utilisateurs : les fournisseurs de modules hétérogènes d’un côté (offre) et de l’autre les bénéficiaires de ces modules (demande). 

![Schéma de gouvernance générique d'une plateforme](http://opendatatales.com/wp-content/uploads/2020/03/Screen-Shot-2020-02-29-at-23.59.54.png)
##### Figure 4 : éléments de l’écosystème d’une plateforme selon Eisenmann et al. (2008)

Le design de mécanismes de gouvernance permet à l’opérateur de la plateforme de stimuler l’adaptabilité et la résilience de l’écosystème en incorporant la connaissance qu’il possède des interdépendances et de la co-évolution entre les deux types d’utilisateurs. (Allen and Varga, 2006 ; Benbya and McKelvey, 2006 ; Tanriverdi et al., 2010)

A terme, le design de ces mécanismes tend vers un équilibre permettant de garder suffisamment de contrôle sur le développement de l’écosystème pour assurer l’intégrité de la plateforme tout en laissant des zones de liberté aux acteurs et utilisateurs. Ceci afin qu’ils puissent innover au travers de la création de nouveaux modules hétérogènes venant s’incorporer à la plateforme. 
	
Tiwana et al. (2010) identifie trois approches théoriques distinctes pour expliquer la gouvernance des plateformes : la gouvernance par le partage de l’autorité et des responsabilités (approche centrée autour de la répartition du pouvoir de décision), la gouvernance par l’alignement des intentions (approche centrée autour des démarches de contrôle) et la gouvernance par le partage de l’intérêt (approche centrée autour de la propriété de la plateforme). 

Selon l’approche de la gouvernance par le partage de l’autorité et des responsabilités, la gouvernance des plateformes doit répondre à trois questions et par les réponses apportées diviser l’autorité et la responsabilité entre les propriétaires de la plateforme et les développeurs de modules : 
- quelle est la finalité de chaque sous-ensemble de la plateforme ? 
- comment ce sous-ensemble devrait-il faire ce qu’il fait ? 
- qui contrôle les interfaces internes (i.e, les éléments qui définissent les frontières des modules) de l’écosystème ? 

Selon l’approche de la gouvernance par l’alignement des intentions, la gouvernance d’une plateforme vise à mettre en place des mécanismes formels et informels visant à encourager des comportements souhaitables chez les développeurs de modules. Le contrôle formel peut prendre deux formes : 
Le contrôle de résultat par lequel le propriétaire de la plateforme précise les critères d’évaluation des modules développés 
Le contrôle du process par lequel le propriétaire de la plateforme flèche des méthodes et procédures aux développeurs de module. 

Enfin, selon l’approche de la gouvernance par le partage des intérêts, la gouvernance de la plaforme revient à distribuer les droits de la propriété de la plateforme et d’établir dans quelle mesure la propriété est partagée entre plusieurs acteurs (Eisenmann et al., 2006)

#### Les mécanismes de gouvernance de plateformes spécifiques aux smart city

Selon Lusch et Nambisan (2015), Il existe 3 types de parties prenantes investies dans les plateformes de services : les architectes, les acteurs et les bénéficiaires.

![Parties prenantes des plateformes smart city](http://opendatatales.com/wp-content/uploads/2020/03/Screen-Shot-2020-03-01-at-00.08.31.png)
##### Figure 5 : typologie des parties prenantes impliquées dans les mécanismes de gouvernance de la plateforme de services des Smart city.

Selon Lusch et Nambisan (2015), Il existe 3 types de parties prenantes investies dans les plateformes de services : les architectes, les acteurs et les bénéficiaires.

Les architectes créent l’architecture de participation qui clarifie la façon dont la co-création de valeur se déroule et la façon dont cette valeur est répartie entre les acteurs. Autrement dit, ils mettent en place une road map stratégique, soit une direction à suivre par tous les acteurs impliqués dans l’écosystème de services. Aussi créent-ils les mécanismes de gouvernance permettant de piloter le fonctionnement et l’évolution de l’écosystème de services vers les objectifs fixés par la road map stratégique. 

Les acteurs ont, de leur côté, les moyens techniques et les compétences pour exploiter les ressources présentes sur la plateforme dans le but de co-créer des services. Ils peuvent occuper trois rôles : idéateur, designer et intermédiaire. Les idéateurs apportent des connaissances sur l’écosystème, ses besoins et les offres de services existantes. Les designers créent des services à partir de nouvelles configurations de ressources. Enfin, les intermédiaires créent des synergies entre les différentes parties de l’écosystème. Ces acteurs constituent les premiers utilisateurs des mécanismes de gouvernance et participent à leur construction dans le cas des plateformes ouvertes.

Enfin, les bénéficiaires font l’expérience de la valeur créée par les services selon 4 types d’expériences : l’expérience pragmatique, l’expérience socialisante, l’expérience d’usage et l’expérience hédonique (Nambisan & Nambisan, 2008). Cette valeur se matérialise finalement pour les bénéficiaires par une amélioration de leur qualité de vie.  

#### Origines du manque d'implication des villes dans la réutilisation des données ouvertes et émergence de politiques de réutilisation

 Résumé | 
------------ | 
Dans cette partie, il sera question tout d’abord de pointer du doigt le postulat implicite à l’origine du du manque d’implication des villes dans la réutilisation de leurs données ouvertes avant de reprendre les catégories de politiques de réutilisation instaurées par Courmont (2016). Nous visons ici à développer plus en profondeur l’idée évoquée dans la partie précédente selon laquelle les acteurs publics rencontrent de nombreuses difficultés pour faciliter la réutilisation des données en open data, quand ils ne laissent pas complètement cet aspect hors de leur agenda | 

**Manque d'implication des villes dans la réutilisation des données ouvertes**
A l’origine du mouvement de l’open data on retrouve l’idée selon laquelle une fois les données mises en open data, elles seraient réutilisées et transformées en innovation, avec à la clé de la création de valeur économique (Chignard, 2013). On trouve ce postulat pour la première fois dans un rapport de la commission européenne de 2006, intitulé Measuring European Public Sector Information Resources (Dekkers et al., 2006) et qui estime que l’open data et les informations publiques pourraient créer un marché estimé à 40 milliards d’euros par an. 

Nous décrirons ici la logique construite par la commission européenne pour venir supporter cette estimation (figure ci-dessous).

![Logigramme](http://opendatatales.com/wp-content/uploads/2020/03/Document-de-travail-Revue-de-littérature-Mars-2019.png)
##### Figure 6. logigramme établissant le lien entre l’offre de données, la demande de données et les résultats économiques de l’open data (Dekkers et al., 2006)

En premier lieu, la commission européenne identifie trois rôles que les organisations impliquées dans l’open data peuvent jouer : 

1. Fournisseur public de données : tout organismes public ou organisme régit par le droit public qui fournit des données à un marché. 
2. Réutilisateur de données : les organismes (hors secteur public) qui fournissent de l’information au marché. 
3. Utilisateur : toute personne ou organisation utilisant les informations fournies par les réutilisateurs. 

Puis, elle articule les relations entre ces rôles en suivant une logique constituée de 5 conditions cadres, et de 2 types d’impact économiques. Les premières correspondent à des principes généraux s’appliquant à l’offre de données et d’informations tandis que les seconds ont traits aux conséquences économiques de l’application des principes généraux (description ci-dessous) 

<table>
	<tr>
            <td rowspan= "5">Conditions cadres</td>
            <td>1.Si les données ne sont pas disponibles pour les réutilisateurs alors il n’y aura pas de marché  </td>
	</tr>
	<tr>
	     <td>2. Si les données disponibles ne sont pas accessibles, alors il ne peut y avoir de réutilisations </td>
	</tr>
	<tr>
	     <td>3. Si les conditions de réutilisation des données ne sont pas transparentes, alors l’accessibilité perd tout son sens et il ne pourra y avoir de marché lié à la réutilisation des données </td>
	</tr>
	<tr>
	     <td>4. Les producteurs de données sont responsables et doivent rendre des comptes vis à vis des 3 premiers points</td>
	</tr>
	<tr>
	     <td>5. Les 4 premiers points doivent être respectés et ce, quelque soit le réutilisateur </td>
	</tr>
	<tr>
            <td rowspan= "5">Impacts économiques</td>
            <td>6. L’égalité et l’équité face aux données/informations publiques stimulera la demande actuelle de données et d’informations </td>
	</tr>
	<tr>
	     <td>7. Cette demande se traduira éventuellement par des résultats économiques directs (plus de chiffre d’affaire pour les réutilisateurs) et indirecteurs (plus d’activités commerciales basées sur la réutilisation des informations publiques)  </td>
	</tr>

</table>

En substance, la commission européenne estime que si les producteurs de données ouvertes font en sorte que ces données soient disponibles (point 1), accessibles (point 2), transparentes (point 3), que les fournisseurs de données s’engagent à rendre des comptes (point 4) et à fournir un accès égal et équitable à tous (point 5 et point 6), alors les données seront d’avantage réutilisées. Autrement dit, la commission européenne suggère que les acteurs publics verront leurs données réutilisées naturellement si elles respectent ces 5 critères. 

Ce raisonnement, que je rangerai ici parmi les fondations intellectuelles de l’open data, peut participer à expliquer l’avènement du mythe d’un développement économique causé, presque naturellement, par l’ouverture des données publiques. Aussi permet-il de comprendre la posture historique des politiques open data, qui allouent peu de moyens aux pratiques qui pourraient accroitre durablement la réutilisation des données ouvertes. Enfin, l’intérêt tardif de la communauté scientifique et le faible nombre d’études s’intéressant à la réutilisation peut être perçu comme une autre conséquence de ce raisonnement fondateur. Et Courmont (2016, p.242) de résumer : “l’accent est d’avantage mis sur l’accès aux données que sur les usages qui en sont faits” 

**L'émergence de politiques de réutilisation**
Pour pallier à ce manque de matériau scientifique, Courmont (2016) a réalisé une quinzaine d’études de cas de réutilisations de données mises à disposition par le Grand Lyon. A partir d’elles, il a pu établir 3 catégories de politiques de réutilisation. Rappellons ici qu’il conçoit une politique de données en se basant sur les travaux de Bruno Latour et qu’il définit comme : “l’ensemble des opérations de compositions de collectifs autour des données”. Cette conception a l’avantage de ne pas restreindre les politiques de données aux politiques telles que conçues par les sciences politiques : “Ces politiques de données peuvent s’inscrire dans ce qui relève d’un champ politique, mais elles ne s’y restreignent pas. Il existe autant de politiques qu’il y a d’étapes dans les transformations de données” (Courmont, 2016, p.31)

Suivant cette conception, il distingue 3 catégories de politique de données en suivant 3 étapes de transformation de la donnée : la consolidation, l’homogénéisation et l’articulation. 

1. Les politiques de consolidation

Ces politiques sont mises en place pour contrer le risque de deliquescence des données une fois qu’elles ont été extraites de leur univers institutionnel d’origine. Comme une plante qui une fois déracinée dépérit, la donnée perd de son potentiel de réutilisation une fois extraite de son contexte de production. 
Les politiques de consolidation visent à renforcer “la capacité de la donnée à resister à des circonstances et pratiques inattendues” (Courmont, 2016, p.247), et ce en ajoutant des éléments qui vont faciliter le passage de la donnée d’un contexte à un autre. Parmi les mesures liée à ce type de politique, nous pouvons prendre l’exemple du renseignement des métadonnées. Celles-ci donnent des indications textuelles sur ce que contient le jeu de données, la période et l’objet couvert. Avec ces informations, un réutilisateur peut facilement estimer la valeur de l’usage de ce jeu de données dans son contexte et univers social. 

2. Les politiques d'homogénéisation

Ces politiques sont mises en place lorsque les acteurs souhaitent utiliser les données dans une dimension plus large que celle pour laquelle elles ont été produites. Dans le cadre des villes, il peut s’agir de passer de l’échelle communale à l’échelle métropolitaine. L’avantage de cette homogénéisation est de pouvoir trouver des conventions communes s’appliquant à des données hétérogènes permettant de les intégrer pour pouvoir ensuite développer des services à un échelon spatial ou institutionnel supérieur. 
Ces politiques d’homogénéisation sont souvent mises en place par des acteurs hors de la sphère publique. Nous pouvons citer OpenStreetMap qui récupère et homogénéise les données géographiques ouvertes pour proposer un Wikipédia de la géographie à l’échelle mondiale.

3. Les politiques d'articulation

Ce type de politique consiste à mettre en relation des données qui ne sont pas du même type en trouver un dénominateur commun. Ces politiques sont mises en place quand les données produites rentrent dans la catégorie des big data, entendu au sens où la quantité générée est extrêmement importante avec des types de données extrêmement divers. En effet, pour pouvoir utiliser ces immenses quantités de données hétérogènes, il faut être capable de les relier entre elles.
Cette politique a notamment été mise en place par la Centrale de mobilité du Grand Lyon, pour “articuler les données de l’ensemble des modes de transport de l’agglomération lyonnaise pour produire une représentation métropolitaine de la mobilité (Courmont, 2016, p.294)



#### Les 3 générations de plateformes Open Data

- PhD Working Book (4) - p. 101-102 - Faible performance des plateformes de deuxième génération  
- PhD Working Book (1) - Plateformes de deuxième génération - Alewopoulos et al. (2014) - p.34
- PhD Working Book (8) - p.47 - Plateformes de collaboration (Hogan, 2017)
- PhD Working Book (9) - p.364 - Application du concept de plateforme auto-poietique


#### Innovation de services 

- PhD Working Book (7) - p.55-57/60-63 - Premier mindmap sur la littérature "classique" sur l'innovation de services
- PhD Working Book (2) - p.20-24 - Perspectives sur l'innovation de services
- Conclusion sur le centrage autour du schéma d'assemblage de Kuk et Davies (2011) + petits mains de l'open data et études STS (Denis) + PhD Working Book (2) - p.24-26 - Différentes descritpions des interactions en jeu dans l'innovation de services + PhD Working Book (3)- p.16-19 précisions feedback & collaboration 
- PhD Working Book (7) - p.154-159 - Centrer innovation de services autour de la relation de service (Denis et Pontille, Travalleurs de l'écrit, matières de l'information)
- PhD Working Book (8) - p.1-4 Couture (2012) - Suite sur la définition et la nature de l'OD Work
- PhD Working Book (8) - p.16 - Première mention de la Cognitive Work Analysis pour modéliser l'OD Work
- PhD Working Book (7) - Référence à Boutet (2001) avec exemple d'une relation de service et de la place des données 
- PhD Working Book (3) - p.58-66 - La réutilisation ou l'autre nom de l'innovation
- PhD Working Book (5) - p.57-58 - Démonstration de la différence entre l'utilisation et la réutilisation
- PhD Working Book (5) - p.116 et 119 -  Jetzek et al.(2014) OGD data-driven innovation mechanisms - Autre modèle d'innovation
- PhD Working Book (5) - p.137-141 - Carrara et al. (2015) - Valeurs créées par l'open data (cf data-driven innovation mechanisms)


Conclusion et transition | 
------------ | 
Dans cette partie, | 

#### Page 6

Lorem ipsum dolor sit amet, facilis propriae delicata est eu, at cum periculis complectitur, his cu tale tritani eligendi. In pri affert fabellas, qui eu congue oblique. Pri cu unum solet consul, ius ex soleat debitis. Aliquam graecis pertinax usu et, ad clita nostrud eam. Et vix facete sanctus, omnis scaevola ea cum. Vis malorum similique at, omnis ullum feugiat nec at, est movet iriure scaevola te. Et audire fastidii molestiae duo.

Vel possim sapientem concludaturque no, sed ei cibo tollit repudiare, ius laoreet docendi scribentur te. Has id erroribus contentiones. Nulla oportere quo et, wisi tation mentitum ne mel. Et cum modo rationibus, no vocibus nusquam vis, ad sed pertinacia instructior. Aperiam principes vix ut.

Altera laoreet intellegam an has, ubique populo consequat an cum, sint esse inimicus ne nam. Mel et vocibus nominavi phaedrum. Pro utroque ponderum pericula at, pri et facilisis eloquentiam. Eam brute malorum cu, ex nihil detraxit his, ex alienum fierent principes sit.

Vituperata ullamcorper at sit. Eam ut consul contentiones, pri an timeam erroribus. No fugit nihil atomorum per, vim adhuc atomorum ei. Te autem velit honestatis per, iisque aliquid tacimates et cum.

Ius sanctus facilisi vituperata ei, eius ipsum consul ne vel. No per ocurreret corrumpit consequuntur, postea commodo assentior no pri, quo id dicat homero maiorum. Cu dicam tation usu. No quo forensibus disputando, feugiat perpetua vituperata qui cu.

Ridens moderatius mel ut. Sed quot probo temporibus ei, quo tale adhuc doctus ne. Ne nam probo dicit. In pro equidem iracundia, nisl error ludus te nam, an vim brute delenit. Diceret noluisse incorrupte ne nam, et sed utamur sanctus assentior, dolore causae id pri. Copiosae consequat ius id, elitr gloriatur ius ad. Te choro molestiae qui.

Sed no tota ipsum ancillae, veri ullum inermis pro id, quando scripta has ne. Pro electram complectitur ei. Te mei insolens dignissim, et tota soluta omnesque nam, sale oratio dolores te sea. Ignota postulant usu an. Oblique voluptua mei cu, est instructior necessitatibus cu. Everti mollis quo ea, oporteat deterruisset eu vel.


#### Page 7 

Lorem ipsum dolor sit amet, facilis propriae delicata est eu, at cum periculis complectitur, his cu tale tritani eligendi. In pri affert fabellas, qui eu congue oblique. Pri cu unum solet consul, ius ex soleat debitis. Aliquam graecis pertinax usu et, ad clita nostrud eam. Et vix facete sanctus, omnis scaevola ea cum. Vis malorum similique at, omnis ullum feugiat nec at, est movet iriure scaevola te. Et audire fastidii molestiae duo.

Vel possim sapientem concludaturque no, sed ei cibo tollit repudiare, ius laoreet docendi scribentur te. Has id erroribus contentiones. Nulla oportere quo et, wisi tation mentitum ne mel. Et cum modo rationibus, no vocibus nusquam vis, ad sed pertinacia instructior. Aperiam principes vix ut.

Altera laoreet intellegam an has, ubique populo consequat an cum, sint esse inimicus ne nam. Mel et vocibus nominavi phaedrum. Pro utroque ponderum pericula at, pri et facilisis eloquentiam. Eam brute malorum cu, ex nihil detraxit his, ex alienum fierent principes sit.

Vituperata ullamcorper at sit. Eam ut consul contentiones, pri an timeam erroribus. No fugit nihil atomorum per, vim adhuc atomorum ei. Te autem velit honestatis per, iisque aliquid tacimates et cum.

Ius sanctus facilisi vituperata ei, eius ipsum consul ne vel. No per ocurreret corrumpit consequuntur, postea commodo assentior no pri, quo id dicat homero maiorum. Cu dicam tation usu. No quo forensibus disputando, feugiat perpetua vituperata qui cu.

Ridens moderatius mel ut. Sed quot probo temporibus ei, quo tale adhuc doctus ne. Ne nam probo dicit. In pro equidem iracundia, nisl error ludus te nam, an vim brute delenit. Diceret noluisse incorrupte ne nam, et sed utamur sanctus assentior, dolore causae id pri. Copiosae consequat ius id, elitr gloriatur ius ad. Te choro molestiae qui.

Sed no tota ipsum ancillae, veri ullum inermis pro id, quando scripta has ne. Pro electram complectitur ei. Te mei insolens dignissim, et tota soluta omnesque nam, sale oratio dolores te sea. Ignota postulant usu an. Oblique voluptua mei cu, est instructior necessitatibus cu. Everti mollis quo ea, oporteat deterruisset eu vel.

#### Page 8 

Lorem ipsum dolor sit amet, facilis propriae delicata est eu, at cum periculis complectitur, his cu tale tritani eligendi. In pri affert fabellas, qui eu congue oblique. Pri cu unum solet consul, ius ex soleat debitis. Aliquam graecis pertinax usu et, ad clita nostrud eam. Et vix facete sanctus, omnis scaevola ea cum. Vis malorum similique at, omnis ullum feugiat nec at, est movet iriure scaevola te. Et audire fastidii molestiae duo.

Vel possim sapientem concludaturque no, sed ei cibo tollit repudiare, ius laoreet docendi scribentur te. Has id erroribus contentiones. Nulla oportere quo et, wisi tation mentitum ne mel. Et cum modo rationibus, no vocibus nusquam vis, ad sed pertinacia instructior. Aperiam principes vix ut.

Altera laoreet intellegam an has, ubique populo consequat an cum, sint esse inimicus ne nam. Mel et vocibus nominavi phaedrum. Pro utroque ponderum pericula at, pri et facilisis eloquentiam. Eam brute malorum cu, ex nihil detraxit his, ex alienum fierent principes sit.

Vituperata ullamcorper at sit. Eam ut consul contentiones, pri an timeam erroribus. No fugit nihil atomorum per, vim adhuc atomorum ei. Te autem velit honestatis per, iisque aliquid tacimates et cum.

Ius sanctus facilisi vituperata ei, eius ipsum consul ne vel. No per ocurreret corrumpit consequuntur, postea commodo assentior no pri, quo id dicat homero maiorum. Cu dicam tation usu. No quo forensibus disputando, feugiat perpetua vituperata qui cu.

Ridens moderatius mel ut. Sed quot probo temporibus ei, quo tale adhuc doctus ne. Ne nam probo dicit. In pro equidem iracundia, nisl error ludus te nam, an vim brute delenit. Diceret noluisse incorrupte ne nam, et sed utamur sanctus assentior, dolore causae id pri. Copiosae consequat ius id, elitr gloriatur ius ad. Te choro molestiae qui.

Sed no tota ipsum ancillae, veri ullum inermis pro id, quando scripta has ne. Pro electram complectitur ei. Te mei insolens dignissim, et tota soluta omnesque nam, sale oratio dolores te sea. Ignota postulant usu an. Oblique voluptua mei cu, est instructior necessitatibus cu. Everti mollis quo ea, oporteat deterruisset eu vel.

#### Page 9 

Lorem ipsum dolor sit amet, facilis propriae delicata est eu, at cum periculis complectitur, his cu tale tritani eligendi. In pri affert fabellas, qui eu congue oblique. Pri cu unum solet consul, ius ex soleat debitis. Aliquam graecis pertinax usu et, ad clita nostrud eam. Et vix facete sanctus, omnis scaevola ea cum. Vis malorum similique at, omnis ullum feugiat nec at, est movet iriure scaevola te. Et audire fastidii molestiae duo.

Vel possim sapientem concludaturque no, sed ei cibo tollit repudiare, ius laoreet docendi scribentur te. Has id erroribus contentiones. Nulla oportere quo et, wisi tation mentitum ne mel. Et cum modo rationibus, no vocibus nusquam vis, ad sed pertinacia instructior. Aperiam principes vix ut.

Altera laoreet intellegam an has, ubique populo consequat an cum, sint esse inimicus ne nam. Mel et vocibus nominavi phaedrum. Pro utroque ponderum pericula at, pri et facilisis eloquentiam. Eam brute malorum cu, ex nihil detraxit his, ex alienum fierent principes sit.

Vituperata ullamcorper at sit. Eam ut consul contentiones, pri an timeam erroribus. No fugit nihil atomorum per, vim adhuc atomorum ei. Te autem velit honestatis per, iisque aliquid tacimates et cum.

Ius sanctus facilisi vituperata ei, eius ipsum consul ne vel. No per ocurreret corrumpit consequuntur, postea commodo assentior no pri, quo id dicat homero maiorum. Cu dicam tation usu. No quo forensibus disputando, feugiat perpetua vituperata qui cu.

Ridens moderatius mel ut. Sed quot probo temporibus ei, quo tale adhuc doctus ne. Ne nam probo dicit. In pro equidem iracundia, nisl error ludus te nam, an vim brute delenit. Diceret noluisse incorrupte ne nam, et sed utamur sanctus assentior, dolore causae id pri. Copiosae consequat ius id, elitr gloriatur ius ad. Te choro molestiae qui.

Sed no tota ipsum ancillae, veri ullum inermis pro id, quando scripta has ne. Pro electram complectitur ei. Te mei insolens dignissim, et tota soluta omnesque nam, sale oratio dolores te sea. Ignota postulant usu an. Oblique voluptua mei cu, est instructior necessitatibus cu. Everti mollis quo ea, oporteat deterruisset eu vel.


#### Page 10 

Lorem ipsum dolor sit amet, facilis propriae delicata est eu, at cum periculis complectitur, his cu tale tritani eligendi. In pri affert fabellas, qui eu congue oblique. Pri cu unum solet consul, ius ex soleat debitis. Aliquam graecis pertinax usu et, ad clita nostrud eam. Et vix facete sanctus, omnis scaevola ea cum. Vis malorum similique at, omnis ullum feugiat nec at, est movet iriure scaevola te. Et audire fastidii molestiae duo.

Vel possim sapientem concludaturque no, sed ei cibo tollit repudiare, ius laoreet docendi scribentur te. Has id erroribus contentiones. Nulla oportere quo et, wisi tation mentitum ne mel. Et cum modo rationibus, no vocibus nusquam vis, ad sed pertinacia instructior. Aperiam principes vix ut.

Altera laoreet intellegam an has, ubique populo consequat an cum, sint esse inimicus ne nam. Mel et vocibus nominavi phaedrum. Pro utroque ponderum pericula at, pri et facilisis eloquentiam. Eam brute malorum cu, ex nihil detraxit his, ex alienum fierent principes sit.

Vituperata ullamcorper at sit. Eam ut consul contentiones, pri an timeam erroribus. No fugit nihil atomorum per, vim adhuc atomorum ei. Te autem velit honestatis per, iisque aliquid tacimates et cum.

Ius sanctus facilisi vituperata ei, eius ipsum consul ne vel. No per ocurreret corrumpit consequuntur, postea commodo assentior no pri, quo id dicat homero maiorum. Cu dicam tation usu. No quo forensibus disputando, feugiat perpetua vituperata qui cu.

Ridens moderatius mel ut. Sed quot probo temporibus ei, quo tale adhuc doctus ne. Ne nam probo dicit. In pro equidem iracundia, nisl error ludus te nam, an vim brute delenit. Diceret noluisse incorrupte ne nam, et sed utamur sanctus assentior, dolore causae id pri. Copiosae consequat ius id, elitr gloriatur ius ad. Te choro molestiae qui.

Sed no tota ipsum ancillae, veri ullum inermis pro id, quando scripta has ne. Pro electram complectitur ei. Te mei insolens dignissim, et tota soluta omnesque nam, sale oratio dolores te sea. Ignota postulant usu an. Oblique voluptua mei cu, est instructior necessitatibus cu. Everti mollis quo ea, oporteat deterruisset eu vel.



