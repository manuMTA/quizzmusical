# 🎵 Quiz musical — mode d'emploi

## 1. Mise en ligne
Déposez **index.html** et **buzzer.html** dans le même dossier de votre hébergement (site de l'association, Netlify, GitHub Pages, OVH…). Il faut une adresse en **https**.
- Écran animateur : `https://votre-site/quiz/` (ou `.../index.html`)
- Les joueurs n'ont pas à connaître l'adresse : ils scannent le QR code affiché par l'animateur.

Aucun serveur ni base de données : les buzz vont directement du téléphone à l'écran de l'animateur (WebRTC, service gratuit PeerJS). Il faut Internet sur l'ordinateur de l'animateur et sur les téléphones (Wi-Fi ou 4G).

## 2. Avant la soirée (ordinateur de l'animateur, avec Chrome ou Edge de préférence)
1. Ouvrez l'écran animateur et cliquez sur **📁 Charger les musiques** : choisissez le dossier où se trouvent vos MP3. Les fichiers restent sur l'ordinateur, rien n'est mis en ligne. Chrome et Edge se souviennent du dossier (bouton « Réactiver » à la réouverture).
2. **👥 Équipes** : noms, couleurs, ordre (de 2 à 10 équipes).
3. **✏️ Préparer** : remplissez chaque jeu. Le bouton ▶ à côté d'un fichier lance l'écoute ; le bouton ⏱ à côté d'un temps reprend le moment exact de l'écoute (pratique pour régler l'arrêt du jeu « Terminer les paroles » ou la coupure du karaoké).
4. **⬇ Exporter** pour garder une copie de la préparation. Sur un autre ordinateur, utilisez **⬆ Importer**.

La préparation, les équipes et les scores sont gardés dans le navigateur de cet ordinateur.

## 3. Pendant la soirée
- Projetez l'écran animateur, affichez **📱 Rejoindre** : chaque joueur scanne, tape son prénom et choisit sa couleur.
- Au premier buzz, la lampe de l'équipe s'allume, un son retentit et la musique se met en pause. Cliquez ensuite sur **✓ Bonne réponse** (+1 point, buzzers réarmés) ou **✗ Mauvaise** (l'équipe est hors jeu pour cette question, la main passe à l'équipe suivante ou la musique reprend).
- Scores : boutons + / − à droite.

| Touche | Action |
|---|---|
| Espace | lecture / pause |
| R | réarmer les buzzers |
| B | ouvrir / fermer les buzzers |
| V / X | bonne / mauvaise réponse |
| ← → | chanson précédente / suivante |
| 1 à 9 | +1 point à l'équipe n° (Maj + chiffre : −1) |

## 4. Les jeux
1. **Nuage de mots** : les mots que vous avez saisis apparaissent un par un ; « Révéler » affiche le titre et lance la chanson.
2. **Terminer les paroles** : la musique s'arrête toute seule au temps choisi, vos paroles s'affichent avec des cases vides, puis « Révéler » les remplit.
3. **Blind test** : extrait à partir du temps de départ, pause automatique au buzz.
4. **Karaoké – garde le rythme** : le son se coupe pendant X secondes (la chanson continue en silence), puis revient : on voit qui est resté dans le rythme.
5. **Chacun son tour** : choisissez l'artiste ; chaque équipe cite un titre à son tour, vous le tapez et l'appli vérifie (accents, majuscules et petites fautes tolérés, doublons détectés). Chrono par tour, élimination et point par titre se règlent dans ✏️ Préparer. Les listes de Cabrel (80 titres), Gims (134), Vianney (50), Stromae (51) et Johnny (167) sont pré-remplies, duos et featurings compris (le partenaire s'affiche entre parenthèses, il n'a pas à être cité) ; si une préparation était déjà enregistrée, les titres manquants y sont ajoutés automatiquement. « Valider quand même » ajoute un titre manquant à la liste.

Les paroles ne sont pas fournies : c'est vous qui les saisissez dans ✏️ Préparer.

## 5. Liste des chansons par jeu
Le numéro est celui affiché à l'écran.

```
JEU 1 — NUAGE DE MOTS
(ordre de passage tiré au hasard à l'écran : repérez la chanson par son titre)
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

JEU 2 — TERMINER LES PAROLES
(les équipes choisissent leur chanson)
------------------------------------------------------------
 1. Melodrama — Disiz et Theodora
 2. Clic clic pan pan — Yanns
 3. Et bam — Mentissa
 4. Tahiti — Keen'V
 5. Beau-papa — Vianney
 6. Je t'emmène au vent — Louise Attaque
 7. Tu m'oublieras — Larusso
 8. Je danse le Mia — IAM
 9. Tomber la chemise — Zebda
    Total : 9 chansons

JEU 3 — BLIND TEST
(liste à compléter dans ✏️ Préparer)
------------------------------------------------------------


JEU 4 — KARAOKÉ « GARDE LE RYTHME »
(les équipes choisissent leur chanson)
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

JEU 5 — CHACUN SON TOUR
(choisir un artiste ; titres acceptés vérifiés par l'application)
------------------------------------------------------------
 1. Francis Cabrel (80 titres dans la liste)
 2. Gims (133 titres dans la liste)
 3. Vianney (50 titres dans la liste)
 4. Stromae (51 titres dans la liste)
 5. Johnny Hallyday (167 titres dans la liste)
```
