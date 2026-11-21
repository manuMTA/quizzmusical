# 🎵 Quiz musical — version 2 : mode d'emploi

## 1. Mise en ligne
Déposez **index.html**, **buzzer.html** et le dossier **paroles** dans un même dossier de votre hébergement (par ex. un sous-dossier `v2` sur GitHub Pages, à côté de la version 1).
La version 2 garde sa propre préparation, ses équipes et ses scores : elle ne touche pas à la version 1.
Les joueurs scannent le QR code affiché par l'animateur (📱 Rejoindre) et choisissent leur équipe.

## 2. Les 5 jeux
1. **Nuage de mots** : jusqu'à 20 mots tirés des paroles apparaissent un par un (sans les mots du titre). Quand le nuage est terminé, les paroles s'affichent (flèches ↓ ↑ par écrans de 10 lignes) ; « ☁️ Revoir le nuage » permet d'y revenir ; « 🎉 Révéler » donne le titre.
2. **Devine la chanson** : une seule équipe joue (choisie en haut). L'animateur fait défiler les chansons une par une : **flèche → (✓ OK)** = 1 point de manche et chanson suivante, **flèche ↓ (✗ Passer)** = chanson suivante sans point, **←** = revenir en arrière. 100 chansons sont déjà prêtes. Chrono par équipe réglable. « ➕ Au score général » ajoute les points de manche au score de l'équipe ; « ↺ Nouvelle manche » remet à zéro. « 🙈 Masquer le titre » cache le titre à l'écran.
3. **N'oubliez pas les paroles** : les équipes choisissent leur chanson ; les paroles s'affichent par écrans de 10 lignes, 7 ou 8 mots sont cachés par des ____ sur la 8e ligne de l'écran ; « 👀 Révéler » les affiche.
4. **À côté de la plaque** : on joue une musique et l'écran affiche les paroles d'une autre chanson : il faut trouver les 2 chansons. « 🎵 Révéler la musique » et « 📝 Révéler les paroles » donnent chaque réponse.
5. **Blind test par catégorie** : Séries TV, Rap, Chansons françaises, Ambiance, Décalé. On choisit la catégorie, puis on passe les extraits un par un ; « 🎉 Révéler » donne titre et artiste.

Buzzers : au premier buzz, la lampe de l'équipe s'allume ; **✓ Bonne réponse** (V) = +1 point, **✗ Mauvaise** (X) = l'équipe est hors jeu pour cette question.

## 3. Préparer (✏️ Préparer)
- Jeu 2 et jeu 5 : une chanson par ligne, au format « Titre — Artiste ».
- Jeu 4 : pour chaque manche, le titre et l'artiste de la musique jouée, et de la chanson dont on affiche les paroles.
- Paroles (jeux 1, 3 et 4) : un fichier texte par chanson dans le dossier `paroles/`, nommé d'après le titre (minuscules, sans accents, tirets), par ex. « Je t'emmène au vent » → `je-t-emmene-au-vent.txt`. Pour le jeu 4, c'est le titre de la chanson **dont on affiche les paroles**. Les lignes commençant par # sont ignorées.
- ⬇ Exporter / ⬆ Importer : sauvegarder la préparation ou la passer sur un autre ordinateur.

## 4. Raccourcis
Espace : lecture/pause · A : écran d'accueil · R : réarmer les buzzers · B : ouvrir/fermer · V / X : bonne / mauvaise réponse · jeu 2 : → OK +1 · ↓ passer · ← précédente · ↑ ↓ : 10 lignes de paroles suivantes / précédentes · ← → : chanson précédente / suivante · 1 à 9 : +1 point à l'équipe n° (Maj : −1)

## 5. Liste des chansons par jeu
```
JEU 1 — NUAGE DE MOTS
(ordre tiré au hasard à l'écran ; les paroles s'affichent quand le nuage est terminé)
------------------------------------------------------------
 1. Le Jerk — Thierry Hazard
 2. Aïcha — Khaled
 3. Caroline — MC Solaar
 4. Allumer le feu — Johnny Hallyday
 5. Au soleil — Jenifer
 6. La Boulette — Diam's
 7. Ma philosophie — Amel Bent
 8. Parle à ma main — Fatal Bazooka feat. Yelle
 9. Le temps — Tayc
10. Sous le vent — Garou et Céline Dion
11. La Tribu de Dana — Manau
12. Sapés comme jamais — Maître Gims feat. Niska
13. Ciel — Gims
14. Balance ton quoi — Angèle
    Total : 14 chansons

JEU 2 — DEVINE LA CHANSON
(une équipe joue ; → = OK +1 point de manche, ↓ = passer)
------------------------------------------------------------
  1. Le Sud — Nino Ferrer
  2. Mistral gagnant — Renaud
  3. Les Démons de minuit — Images
  4. Ella, elle l'a — France Gall
  5. Nuit de folie — Début de Soirée
  6. Les Mots bleus — Christophe
  7. Aline — Christophe
  8. Le Lion est mort ce soir — Pow Wow
  9. Joe le taxi — Vanessa Paradis
 10. Marcia Baïla — Les Rita Mitsouko
 11. C'est comme ça — Les Rita Mitsouko
 12. L'Aventurier — Indochine
 13. Tous les cris les SOS — Daniel Balavoine
 14. L'Aziza — Daniel Balavoine
 15. Ça plane pour moi — Plastic Bertrand
 16. Partenaire particulier — Partenaire Particulier
 17. Femme libérée — Cookie Dingler
 18. Week-end à Rome — Étienne Daho
 19. Alexandrie Alexandra — Claude François
 20. Ces soirées-là — Yannick
 21. Laisse tomber les filles — France Gall
 22. La Bombe humaine — Téléphone
 23. Cendrillon — Téléphone
 24. Un autre monde — Téléphone
 25. Le Bal masqué — La Compagnie créole
 26. La Groupie du pianiste — Michel Berger
 27. Quand la musique est bonne — Jean-Jacques Goldman
 28. Envole-moi — Jean-Jacques Goldman
 29. Comme toi — Jean-Jacques Goldman
 30. Casser la voix — Patrick Bruel
 31. Place des grands hommes — Patrick Bruel
 32. Ma liberté de penser — Florent Pagny
 33. Chanter — Florent Pagny
 34. Né quelque part — Maxime Le Forestier
 35. San Francisco — Maxime Le Forestier
 36. Le Coup de soleil — Richard Cocciante
 37. Il venait d'avoir 18 ans — Dalida
 38. Gigi l'amoroso — Dalida
 39. Les Rois du monde — Roméo et Juliette
 40. La Bohème — Charles Aznavour
 41. Emmenez-moi — Charles Aznavour
 42. L'Encre de tes yeux — Francis Cabrel
 43. Si tu vas à Rio — Dario Moreno
 44. Il jouait du piano debout — France Gall
 45. Pour un flirt — Michel Delpech
 46. Le Loir-et-Cher — Michel Delpech
 47. L'Été indien — Joe Dassin
 48. Salut les amoureux — Joe Dassin
 49. Siffler sur la colline — Joe Dassin
 50. Comme d'habitude — Claude François
 51. Le Téléphone pleure — Claude François
 52. Belles ! Belles ! Belles ! — Claude François
 53. Avec le temps — Léo Ferré
 54. La Javanaise — Serge Gainsbourg
 55. Le Poinçonneur des Lilas — Serge Gainsbourg
 56. Couleur café — Serge Gainsbourg
 57. Poupée de cire, poupée de son — France Gall
 58. Hexagone — Renaud
 59. Dès que le vent soufflera — Renaud
 60. Laisse béton — Renaud
 61. J'ai encore rêvé d'elle — Il était une fois
 62. Il est cinq heures, Paris s'éveille — Jacques Dutronc
 63. Les Play-boys — Jacques Dutronc
 64. L'Opportuniste — Jacques Dutronc
 65. La Ballade des gens heureux — Gérard Lenorman
 66. Voici les clés — Gérard Lenorman
 67. Une belle histoire — Michel Fugain
 68. Fais comme l'oiseau — Michel Fugain
 69. Tu es foutu — In-Grid
 70. Encore un soir — Céline Dion
 71. S'il suffisait d'aimer — Céline Dion
 72. Libertine — Mylène Farmer
 73. Sans contrefaçon — Mylène Farmer
 74. Les Vacances au bord de la mer — Michel Jonasz
 75. Lucie — Pascal Obispo
 76. Fan — Pascal Obispo
 77. Tombé du ciel — Jacques Higelin
 78. Allô maman bobo — Alain Souchon
 79. Jamais content — Alain Souchon
 80. Belle-Île-en-Mer, Marie-Galante — Laurent Voulzy
 81. Rockollection — Laurent Voulzy
 82. Elle a les yeux revolver — Marc Lavoine
 83. Tout le bonheur du monde — Sinsemilia
 84. Ma Benz — Suprême NTM
 85. Pas le temps — Faf Larage
 86. Elle me dit — Mika
 87. Je veux tes yeux — Angèle
 88. Les Passants — Zaz
 89. On écrit sur les murs — Kids United
 90. J'aime plus Paris — Thomas Dutronc
 91. Le Jardin d'hiver — Henri Salvador
 92. Un jour en France — Noir Désir
 93. Sous le ciel de Paris — Yves Montand
 94. La Grenade — Clara Luciani
 95. Tout va bien — Orelsan
 96. Jour de neige — Elsa
 97. Mourir d'aimer — Charles Aznavour
 98. Résiste — France Gall
 99. Sauver l'amour — Daniel Balavoine
100. Le Chanteur — Daniel Balavoine
     Total : 100 chansons


JEU 3 — N'OUBLIEZ PAS LES PAROLES
(mots cachés à retrouver ; les équipes choisissent leur chanson)
------------------------------------------------------------
 1. Les Lacs du Connemara — Michel Sardou
 2. Les Champs-Élysées — Joe Dassin
 3. Santiano — Hugues Aufray
 4. Je te donne — Jean-Jacques Goldman et Michael Jones
 5. Mexico — Luis Mariano
 6. Petite Marie — Francis Cabrel
 7. La même — Gims et Vianney
 8. Dommage — Bigflo & Oli
 9. Moi... Lolita — Alizée
10. En feu — Soprano
11. Melodrama — Disiz et Theodora
12. Coco — Wejdene
13. Beau-papa — Vianney
    Total : 13 chansons

JEU 4 — À CÔTÉ DE LA PLAQUE
(on joue la musique, l'écran affiche les paroles d'une autre chanson : trouver les 2)
------------------------------------------------------------
 1. 🎵 Musique : Alors on danse — Stromae   |   📝 Paroles : Désenchantée — Mylène Farmer
 2. 🎵 Musique : Andalouse — Kendji Girac   |   📝 Paroles : Pour que tu m'aimes encore — Céline Dion
 3. 🎵 Musique : Dernière danse — Indila   |   📝 Paroles : Que je t'aime — Johnny Hallyday
 4. 🎵 Musique : Je veux — Zaz   |   📝 Paroles : Foule sentimentale — Alain Souchon
 5. 🎵 Musique : Bella — Gims   |   📝 Paroles : Toi + Moi — Grégoire
 6. 🎵 Musique : Jour 1 — Louane   |   📝 Paroles : Femme Like U — K.Maro
 7. 🎵 Musique : Formidable — Stromae   |   📝 Paroles : Le Lac — Julien Doré
 8. 🎵 Musique : Ramenez la coupe à la maison — Vegedream   |   📝 Paroles : Basique — Orelsan
    Total : 8 manches


JEU 5 — BLIND TEST PAR CATÉGORIE
(Séries TV · Rap · Chansons françaises · Ambiance · Décalé ; extraits à saisir dans ✏️ Préparer)
------------------------------------------------------------
```
