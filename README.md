# Générateurs de fiches de calcul mental — CE1

Deux générateurs de fiches d'entraînement au calcul mental pour le CE1,
conçus pour une pratique **quotidienne, courte et mesurée**, dans l'esprit du
programme de mathématiques entré en vigueur à la rentrée 2025 (cycle 2,
BOEN du 31 octobre 2024).

- **Générateur de grilles** : l'entraînement de la classe, avec chrono.
- **Générateur de soutien** : la même notion en version adaptée, sans chrono,
  avec un coup de pouce, pour les élèves qui en ont besoin.

Une fiche nouvelle à chaque clic, avec son corrigé, à imprimer, à télécharger
(HTML ou PDF) ou à faire directement sur écran.

Site en ligne : <https://eautsu.github.io/ceintures_calcul_mental/>

---

## 🎯 Ce que vise le programme 2025, et comment les générateurs y répondent

Le programme de 2025 fait du calcul une priorité et distingue clairement deux
objets, chacun avec un repère de **fluence** pour la fin du CE1 :

| Ce que dit le programme | Repère fin CE1 | Réponse des générateurs |
|---|---|---|
| **Mémoriser des faits numériques** pour les restituer de façon quasi instantanée ; connaître **dans les deux sens** les tables d'addition | 12 égalités en 1 minute | Tables travaillées sous trois formes : table stricte, terme manquant, soustraction associée |
| **Maîtriser des procédures de calcul mental** efficaces, progressivement automatisées, en s'appuyant sur la numération | 12 calculs en 3 minutes | Blocs « sans passage de dizaine », « avec passage », « mélange » ; coup de pouce qui explicite la procédure |
| Faits multiplicatifs usuels (doubles, moitiés…) et tables de multiplication | 8 égalités en 1 minute | Doubles, presque-doubles, moitiés, tables de multiplication |
| Pratique **régulière, ritualisée**, courte et fréquente | — | Fiches courtes, chronométrées par bloc, renouvelées à chaque clic |
| Pour les élèves fragiles : **réduire le nombre de calculs**, regrouper en APC, accorder un temps d'entraînement plus long | — | Générateur de soutien : 26 calculs, sans chrono, appuis visuels |

L'idée directrice : **on ne mesure pas seulement si c'est juste, mais si c'est
juste et rapide**. Un fait « su » est un fait disponible sans y penser, qui
libère la mémoire de travail pour raisonner, notamment en résolution de
problèmes.

---

## ✨ Le générateur de grilles (`generateur_grilles.html`)

### Les types de fiches

- **Table stricte** (25 + 5, 5 + 25), **terme manquant** (25 + … = 30,
  … + 5 = 30), **soustraction associée** (30 − 5) : 3 blocs de 20 + 20 + 32 calculs.
- **Défis vitesse** : 3 manches de 18 calculs, additions seules, soustractions
  seules ou mélange.
- **Blocs uniques** de 40 calculs (format type micetf), additions,
  soustractions ou mélange.
- **Doubles, presque-doubles** (jusqu'à N) et **tables de multiplication**.

### Les choix pédagogiques et leurs raisons

**1. Une table se travaille « dans les deux sens ».**
Le programme demande de connaître les tables d'addition dans les deux sens.
Savoir que 25 + 5 = 30 ne suffit pas : l'élève doit aussi retrouver le terme
manquant (25 + … = 30) et la différence (30 − 5). Les trois formes existent
pour chaque table, avec le même nombre de calculs et les mêmes durées, ce qui
rend les résultats comparables d'une forme à l'autre et révèle l'obstacle
précis (« il sait ajouter, mais pas encore chercher ce qui manque »).

**2. Trois blocs : sans passage, avec passage, mélange.**
Le passage de la dizaine est la vraie difficulté du calcul mental au CE1 :
c'est là que la procédure (« je vais à la dizaine, puis j'ajoute le reste »)
doit être mobilisée. Séparer les deux situations permet d'abord de les
travailler pour elles-mêmes, puis de les mêler pour que l'élève reconnaisse
seul laquelle s'applique. Le diagnostic gagne aussi en finesse : un élève
rapide sans passage mais lent avec passage n'a pas besoin du même
entraînement qu'un élève lent partout.

**3. Un temps calculé, pas imposé au hasard.**
La durée de chaque bloc suit une règle unique : 4,5 secondes par calcul
(soit 40 calculs en 3 minutes), arrondie à la demi-minute ; 6 secondes en
soustraction, plus coûteuse. Le chrono se lance bloc par bloc. Un temps
constant d'une fiche à l'autre permet de comparer les séances entre elles et
de calculer une **fluence** (calculs justes par minute) directement lisible
au regard des repères du programme.

**4. Des nombres variés, sans indice de position.**
Les nombres sont **dispersés sur toutes les dizaines** (le calcul ne doit pas
dépendre de « 20 + 5 » appris par cœur) et restent tous **inférieurs à 100**,
le champ numérique du CE1. Les formes alternent (a + 5 et 5 + a ; trou à
gauche et à droite) pour que l'élève lise le calcul au lieu d'appliquer une
routine de position, et travaille au passage la commutativité.

**5. Du défi court pour la vitesse.**
Les défis vitesse (manches d'une minute) entraînent la restitution rapide des
faits, celle que mesure le repère « 12 en 1 minute ». Ils sont préconisés pour
les élèves que le chrono global d'une longue fiche met sous stress (voir
ci-dessous). Les blocs uniques de
40 calculs en 3 minutes (format type micetf) mesurent la fluence sur un
volume suffisant pour être fiable.

**6. Une correction immédiate, sans note.**
Sur écran, chaque bloc se vérifie seul. Le retour donne la **précision**
(acquis à partir de 95 %, en cours, non acquis) et, si le temps est respecté,
la **fluence**. Précision et vitesse restent séparées : un élève juste mais
lent et un élève rapide mais imprécis n'ont pas besoin de la même aide.

### ⏳ Le défi vitesse en classe : sablier et binôme

**Le déroulement**

1. Les élèves travaillent **par deux**, avec un **sablier d'une minute** et
   chacun sa fiche de défi.
2. Le premier élève calcule pendant que le second **gère le temps** :
   il retourne le sablier et dit « stop » quand il est vide.
3. On **échange les rôles** pour la manche suivante. L'élève qui vient de
   calculer **souffle** pendant qu'il tient le sablier : la manche d'une minute
   alterne effort et récupération, et la séance reste courte et rythmée.

**La règle importante : finir avec une autre couleur**

Au « stop », l'élève **ne s'arrête pas**. Il change de crayon (vert, par
exemple) et **termine les calculs de la manche sans pression de temps**.

Cette seconde couleur sépare deux informations sur la même fiche :

| Ce qui est écrit… | … montre |
|---|---|
| **Dans le temps** (première couleur) | l'**automatisation** : les faits disponibles sans y penser |
| **Après le stop** (en vert) | la **compréhension** : ce que l'élève sait faire quand il a le temps |

Un élève qui réussit tout en vert mais peu dans le temps **comprend** : il lui
faut de l'entraînement pour **automatiser**. Un élève qui se trompe aussi en
vert a besoin qu'on **reprenne la procédure**, pas d'aller plus vite. La
remédiation n'est pas la même, et la fiche le montre d'un coup d'œil.

**Cibler précisément les calculs à retravailler**

Le défi donne aussi la **liste des calculs ratés**, et c'est souvent elle qui
dit quoi travailler. Il suffit de regarder ce qu'ils ont en commun.

Exemple : un élève échoue sur 38 + 7, 27 + 8 et 58 + 7. Ce n'est pas « la
table de +7 » qui pose problème : ces trois calculs reposent tous sur le
même fait, **7 + 8 = 15** (8 + 7 et 7 + 8 dans les unités), et tous passent la
dizaine. L'aide ne consiste donc pas à refaire une fiche entière, mais à :

- revoir ce fait précis (presque-double : 7 + 7 = 14, donc 7 + 8 = 15) ;
- revoir la procédure de passage de la dizaine sur ces seuls cas
  (38 + 7 → 38 + 2 = 40, puis + 5 = 45) ;
- reprendre ensuite un défi ou un bloc « avec passage » de la même table pour
  vérifier que le fait est devenu disponible.

Ce regard sur les erreurs évite de faire retravailler à l'élève ce qu'il sait
déjà, et lui montre un objectif court et atteignable.

**Pourquoi le défi plutôt que le chrono global**

Pour certains élèves, une longue fiche sous un chrono unique est une source de
stress qui fait perdre ses moyens et abandonner la procédure apprise. Le défi
vitesse réduit l'enjeu : une minute seulement, un camarade qui tient le temps
plutôt que l'adulte, une pause à chaque manche, et la certitude de pouvoir
finir en vert. Il mesure la même chose, la vitesse de restitution, dans un
cadre plus rassurant.

---

## 🤝 Le générateur de soutien (`generateur_soutien.html`)

Le programme le dit explicitement : pour les élèves fragiles, on peut
**réduire le nombre de calculs**, les regrouper (en classe ou en APC) avec du
matériel, et leur laisser **plus de temps d'entraînement**. Le générateur de
soutien applique ces trois principes **sans changer la notion travaillée**.

### Ce qui change, et pourquoi

| Choix | Raison |
|---|---|
| **Mêmes types de fiches** que le générateur de grilles (table stricte, terme manquant, soustraction, doubles, presque-doubles, moitiés) | L'élève aidé travaille la **même notion** que la classe, au même moment : le soutien n'est pas une voie parallèle, c'est la même marche avec une rampe. |
| **26 calculs** (8 + 8 + 10) au lieu de 72 | Réduire la quantité, comme le recommande le programme, pour que l'élève finisse sa fiche et vive une réussite. |
| **Sans chrono** | On construit d'abord la justesse ; la vitesse viendra quand la procédure est sûre. La pression du temps fait abandonner la procédure apprise au profit du comptage. |
| **Petits nombres d'abord** (résultat ≤ 20), puis nombres jusqu'à 29, 49 ou 99 au choix | La procédure se comprend sur des nombres simples avant de s'étendre ; le champ numérique s'élargit au rythme de l'élève. |
| **Écriture plus grande**, deux colonnes, plus d'espace | Moins de charge visuelle, repérage plus facile dans la grille. |
| **Coup de pouce** imprimé en haut de la fiche | La procédure enseignée est **explicitée et sous les yeux** (« je passe par la dizaine », « je regarde les unités », « je pense à l'addition », « je cherche le double caché »), avec des exemples **différents des calculs de la fiche** pour que l'élève applique la méthode au lieu de recopier. |
| **Tableau des nombres** (dizaines grisées) | Appui visuel pour avancer et reculer de 1 ou de 10, en lien avec le travail de numération. |
| Coup de pouce et tableau **se décochent** | Les aides se retirent progressivement, jusqu'à la fiche ordinaire. |

### Trois niveaux d'aide pour une même notion

1. **Soutien complet** : coup de pouce + tableau des nombres, petits nombres.
2. **Soutien allégé** : coup de pouce seul, nombres jusqu'à 49.
3. **Retour à la fiche de la classe** (générateur de grilles), d'abord sans
   chrono, puis avec.

---

## 👩‍🏫 Mode d'emploi

1. Choisir le type de fiche et la table (N), puis « Générer ».
2. Cocher « Corrigé » pour afficher les réponses.
3. Imprimer, ou télécharger en HTML ou en PDF.
   Chaque fiche porte un **code** (ex. `TM5-48213` : terme manquant, table de 5,
   tirage 48213), imprimé en haut à droite et repris dans le nom du fichier.
   Retaper ce code dans « Code fiche » → « Retrouver » refait **exactement la
   même fiche** (pour la redonner plus tard et comparer, ou la donner à un autre
   groupe). « Fiche du jour » donne la même fiche à tout le monde le même jour.
4. Sur écran : démarrer le chrono du bloc (générateur de grilles), puis
   « Vérifier ».

---

## 🚀 Utiliser sans installation

Aucun compte, aucune installation, aucune donnée personnelle collectée (seul
un comptage anonyme des visites, sans cookie, via GoatCounter) : tout
fonctionne dans le navigateur.

- En ligne : <https://eautsu.github.io/ceintures_calcul_mental/>
- Hors ligne : télécharger les fichiers du dépôt et ouvrir `index.html`
  (l'export PDF demande une connexion pour charger la bibliothèque jsPDF ;
  « Imprimer → Enregistrer en PDF » fonctionne partout).

---

## 📚 Références

- Programme de mathématiques du cycle 2, arrêté du 22 octobre 2024,
  BOEN n° 41 du 31 octobre 2024 (applicable en CE1 à la rentrée 2025).
- Éduscol, *Mathématiques — Livret d'accompagnement de programme, cycle 2*
  (2025) : <https://eduscol.education.fr/document/67770/download>
  (automatisation des tâches élémentaires, faits numériques restitués de façon
  instantanée, pratique ritualisée, différenciation pour les élèves fragiles).
- Repères de fluence du programme repris dans la présentation de circonscription
  « Programme cycle 2 — mathématiques » (IEN Avion, 2025) :
  <https://ienavion.etab.ac-lille.fr/files/2025/04/2-Diapo-C2-Partie-Maths-1.pdf>

---

## ⚖️ Licence

© 2026 Eautsu. Contenu pédagogique et pages : **CC BY-NC-SA 4.0** — voir
`LICENSE` et `LICENSE-NOTICE.md`. Bibliothèque externe : jsPDF (MIT),
chargée via CDN.

## 📬 Signaler un problème

Les coquilles et idées d'amélioration sont bienvenues : ouvrir une *issue*
sur ce dépôt.
