# Quiz des épisodes 1 à 6 · CV portfolio web TSSR

> **Ondea Web Studio · Centre de Formation MODE 83 · Draguignan**
> Quiz de fin de séance : qu'avez-vous retenu de la construction pas à pas, ensemble, des épisodes 1 à 6 du CV portfolio web TSSR (séance du **28 octobre 2026**) ?

![Écran d'accueil du quiz](images/02-accueil.png)

Ce quiz est une page web autonome (un seul fichier `index.html`). Les stagiaires y répondent à **15 questions** (HTML, CSS et JavaScript) sur le code construit pendant la séance. Ils obtiennent ensuite un **bilan PDF personnalisé** qu'ils envoient à leur formateur en message privé sur Microsoft Teams.

---

## Sommaire

1. [En bref](#en-bref)
2. [Les épisodes couverts](#les-épisodes-couverts)
3. [Les 15 questions](#les-15-questions)
4. [Déroulé du quiz en images](#déroulé-du-quiz-en-images)
5. [Le minuteur de 15 minutes](#le-minuteur-de-15-minutes)
6. [Le bilan et le PDF](#le-bilan-et-le-pdf)
7. [Envoi au formateur sur Microsoft Teams](#envoi-au-formateur-sur-microsoft-teams)
8. [Accessibilité et confort de lecture](#accessibilité-et-confort-de-lecture)
9. [Sur mobile](#sur-mobile)
10. [Lancer le quiz](#lancer-le-quiz)
11. [Personnaliser le quiz](#personnaliser-le-quiz)
12. [Données enregistrées sur le poste](#données-enregistrées-sur-le-poste)
13. [Contenu du dossier](#contenu-du-dossier)
14. [Auteur](#auteur)

---

## En bref

| | |
|---|---|
| **Public** | Stagiaires TSSR (RNCP 37682), MODE 83 |
| **Séance évaluée** | 28 octobre 2026 : épisodes 1 à 6 du CV portfolio web |
| **Questions** | 15 : 5 en HTML, 5 en CSS, 5 en JavaScript |
| **Format** | Choix unique (4 réponses), corrigé aussitôt avec explication |
| **Seuil de réussite** | 70 %, soit 11 bonnes réponses sur 15 |
| **Durée** | 15 minutes, avec un décompte affiché |
| **Résultat** | Bilan à l'écran et bilan PDF à envoyer au formateur sur Teams |
| **Technique** | HTML, CSS et JavaScript « vanilla », dans un seul fichier, sans serveur |

L'ordre des réponses est **mélangé pour chaque stagiaire**, ce qui limite la copie entre voisins.

---

## Les épisodes couverts

Chaque question est rattachée à l'épisode où la notion a été construite. En cas d'erreur, le bilan renvoie directement vers la page de l'épisode à revoir.

| Épisode | Thème | Questions | Page de l'épisode |
|:---:|---|:---:|---|
| 1 | La base HTML5 | 2 | [cv-portfolio-tssr-episode-1](https://lugo795.github.io/cv-portfolio-tssr-episode-1/) |
| 2 | Le système graphique (variables, thème clair, lien d'évitement) | 3 | [cv-portfolio-tssr-episode-2](https://lugo795.github.io/cv-portfolio-tssr-episode-2/) |
| 3 | La barre de navigation | 3 | [cv-portfolio-tssr-episode-3](https://lugo795.github.io/cv-portfolio-tssr-episode-3/) |
| 4 | Le Hero | 3 | [cv-portfolio-tssr-episode-4](https://lugo795.github.io/cv-portfolio-tssr-episode-4/) |
| 5 | La section À propos | 2 | [cv-portfolio-tssr-episode-5](https://lugo795.github.io/cv-portfolio-tssr-episode-5/) |
| 6 | La section Compétences | 2 | [cv-portfolio-tssr-episode-6](https://lugo795.github.io/cv-portfolio-tssr-episode-6/) |

---

## Les 15 questions

Les notions évaluées sont listées ci-dessous, **sans les réponses**. Le corrigé et les explications sont dans le tableau `Q` du fichier `index.html`.

| N° | Langage | Épisode | Notion évaluée |
|:---:|:---:|:---:|---|
| 1 | HTML | 1 | Le rôle de l'attribut `data-theme="dark"` sur la balise `<html>` |
| 2 | HTML | 3 | `data-bs-target="#navContent"` sur le bouton burger |
| 3 | HTML | 2 | La place du lien « Passer au contenu principal » juste après `<body>` |
| 4 | HTML | 4 | Le nom écrit en dur dans le `<h1>` alors que le JavaScript le retape |
| 5 | HTML | 6 | `aria-hidden="true"` sur le pourcentage d'une carte de compétence |
| 6 | CSS | 2 | La déclaration d'une variable `--clr-bg` dans `:root` |
| 7 | CSS | 2 | Quand s'applique le bloc `[data-theme="light"]` |
| 8 | CSS | 3 | Le soulignement animé des liens avec `::before` |
| 9 | CSS | 4 | `font-size: clamp(2.4rem, 6vw, 4.2rem)` sur le titre du Hero |
| 10 | CSS | 5 | La spécificité : `#hero` face à `section` |
| 11 | JS | 3 | La mémorisation du thème avec `localStorage` |
| 12 | JS | 1 | Où lire le message `console.log` de `config.js` |
| 13 | JS | 4 | La machine à écrire : `target.textContent += text[i++]` |
| 14 | JS | 5 | L'`IntersectionObserver` et la classe `visible` |
| 15 | JS | 6 | `e.target.dataset.width + '%'` pour remplir une barre |

---

## Déroulé du quiz en images

### 1. Ouverture

Une courte animation d'ouverture présente le quiz. Un clic la passe. Elle est désactivée automatiquement si le poste demande moins d'animations (`prefers-reduced-motion`).

![Animation d'ouverture](images/01-intro.png)

### 2. Identification

Le stagiaire saisit son prénom et son nom, qui figureront sur le bilan PDF. Le bouton **Commencer le quiz** ne s'active qu'une fois les deux champs correctement remplis.

![Étape 1 : identification](images/03-identification.png)

### 3. Les questions

Chaque question affiche son langage (HTML, CSS ou JS) et l'épisode concerné. Le stagiaire choisit une réponse, puis la valide.

![Étape 2 : une question](images/04-question.png)

Une fois validée, la réponse est définitive. La bonne réponse s'affiche en vert, avec une explication tirée du code de l'épisode.

![Bonne réponse et explication](images/05-bonne-reponse.png)

En cas d'erreur, le choix du stagiaire apparaît en rouge et la réponse attendue est indiquée.

![Mauvaise réponse et réponse attendue](images/06-mauvaise-reponse.png)

---

## Le minuteur de 15 minutes

Le temps restant reste visible en haut des questions. Il change d'aspect quand la fin approche. Les lecteurs d'écran annoncent le temps restant à 10 min, 5 min, 2 min, 1 min, 30 s et 10 s.

| Moins de 5 minutes | Dernière minute |
|---|---|
| ![Minuteur orange](images/07a-minuteur-moins-5-min.png) | ![Minuteur rouge](images/07b-minuteur-derniere-minute.png) |

À 00:00, le quiz se verrouille et le bilan s'affiche. Les questions sans réponse comptent comme non réussies et sont signalées comme telles.

![Bilan après temps écoulé](images/07c-temps-ecoule.png)

Les boutons **Recommencer** et **Nouvelle tentative** restent verrouillés jusqu'à la fin des 15 minutes, et le numéro de tentative est inscrit sur le bilan.

---

## Le bilan et le PDF

Le bilan affiche le score, le pourcentage, le verdict par rapport au seuil de 70 %, le résultat par langage, un commentaire personnalisé et la liste des **épisodes à revoir en priorité**, avec un lien vers chacun.

![Étape 3 : bilan](images/08-bilan.png)

Le stagiaire peut revoir ses 15 réponses une par une, avec la réponse attendue et l'explication.

![Revoir mes 15 réponses](images/10-revoir-reponses.png)

Le bouton **Télécharger mon bilan PDF** produit un document A4 avec du vrai texte (sélectionnable et lisible par les lecteurs d'écran), nommé :

```
Bilan-quiz-episodes-1-6-TSSR_NOM_Prénom_AAAA-MM-JJ.pdf
```

| Page 1 : identité, score, résultats par langage | Page 2 : commentaire, épisodes à revoir, détail |
|---|---|
| ![PDF page 1](images/16-pdf-page-1.png) | ![PDF page 2](images/16-pdf-page-2.png) |

Chaque PDF porte un **code de référence** calculé à partir du nom, de l'heure de départ et des réponses.

Si la bibliothèque PDF ne peut pas se charger (poste hors ligne), la page propose l'impression du navigateur : **Enregistrer au format PDF**.

---

## Envoi au formateur sur Microsoft Teams

La page rappelle les quatre étapes pour envoyer le bilan **en message privé** à Jean-Claude Lugo, et affiche le nom exact du fichier à joindre.

![Envoi du bilan sur Teams](images/09-envoi-teams.png)

---

## Accessibilité et confort de lecture

Le quiz vise le niveau WCAG 2.2 AAA :

- **Police Atkinson Hyperlegible**, conçue pour les personnes malvoyantes, et IBM Plex Mono pour le code.
- **Taille du texte réglable** de 85 % à 200 % (boutons A− et A+).
- **Thème clair ou sombre**, qui suit par défaut le réglage du poste.
- **Trois niveaux de contraste** : Standard, Renforcé, Maximal.
- **Pluie Matrix décorative** derrière les textes, qu'on peut mettre en pause.
- Navigation complète au clavier, lien d'évitement, focus toujours visible.
- Statuts écrits en toutes lettres (« Correct », « Incorrect », « Sans réponse »), pas seulement en couleur.
- Messages annoncés aux lecteurs d'écran (`aria-live`), barres de progression accessibles (`role="progressbar"`).
- Réglages mémorisés sur le poste d'un quiz à l'autre.

| Thème sombre | Contraste maximal | Texte à 150 % |
|---|---|---|
| ![Thème sombre](images/11-theme-sombre.png) | ![Contraste maximal](images/12-contraste-maximal.png) | ![Texte agrandi à 150 %](images/13-texte-150.png) |

---

## Sur mobile

La page s'adapte aux petits écrans, sans défilement horizontal.

| Accueil | Question et minuteur |
|---|---|
| <img src="images/14-mobile-accueil.png" alt="Accueil sur mobile" width="300"> | <img src="images/15-mobile-question.png" alt="Question sur mobile" width="300"> |

---

## Lancer le quiz

### En salle, sur chaque poste

1. Copiez `index.html` sur le poste, par exemple dans `Documents`.
2. Double-cliquez sur le fichier : il s'ouvre dans le navigateur (Chrome, Edge ou Firefox).
3. Le stagiaire saisit son prénom et son nom, puis clique sur **Commencer le quiz**.

Aucun serveur n'est nécessaire. Une connexion Internet permet de charger les polices et la bibliothèque PDF ; sans connexion, la page utilise les polices du système et propose l'impression en PDF.

### En ligne, avec GitHub Pages

1. Créez un dépôt, par exemple `quiz-episodes-1-6`, sur le compte GitHub de la série.
2. Déposez `index.html` à la racine du dépôt.
3. Dans **Settings › Pages**, choisissez la branche `main` et le dossier `/ (root)`.
4. Partagez l'adresse obtenue avec les stagiaires (par exemple dans le canal Teams de la promotion).

---

## Personnaliser le quiz

Tous les réglages se trouvent dans `index.html`.

| Réglage | Où le modifier | Valeur actuelle |
|---|---|---|
| Nom et rôle du formateur | Objet `TRAINER` | Jean-Claude Lugo, Formateur expert |
| Bouton « Ouvrir la conversation Teams » | `TRAINER.teamsEmail` (laisser vide pour le masquer) | vide |
| Formation affichée sur le bilan | Constante `PROGRAM` | TSSR · Centre de Formation MODE 83 · Draguignan |
| Seuil de réussite | Constante `PASS` | `70` (en %) |
| Durée du quiz | Constante `DUREE` dans **les deux** scripts « décompte » et « verrou » | `15 * 60 * 1000` (15 minutes) |
| Questions | Tableau `Q` | 15 questions |
| Épisodes et liens | Objet `LESSONS` et fonction `EPURL` | Épisodes 1 à 6, GitHub Pages `lugo795` |

### Structure d'une question

```js
{
  id: "q12",                 // identifiant unique (q1 à q15)
  lang: "js",                // "html", "css" ou "js"
  lesson: "ep1",             // épisode où la notion a été construite
  q: "Où voit-on le message `config.js chargé ✔` écrit par `console.log` ?",
  o: ["…", "…", "…", "…"],   // les 4 réponses proposées
  a: 3,                      // index de la bonne réponse dans o (0 = la première)
  why: "…"                   // explication affichée après validation
}
```

Le texte placé entre accents graves (`` `…` ``) s'affiche en police de code.

> ⚠️ Si vous écrivez une balise de fermeture `</script>` dans un texte de question, notez-la `<\/script>` : sinon le navigateur croit que le script s'arrête là et le quiz ne démarre plus.

Le quiz est prévu pour **15 questions, 5 par langage** : le seuil affiché (« 11 bonnes réponses sur 15 ») et le minuteur s'appuient sur ce nombre.

---

## Données enregistrées sur le poste

Les réponses restent **sur le poste du stagiaire** : rien n'est envoyé sur Internet. Seul le PDF généré à la fin est transmis au formateur.

| Clé `localStorage` | Contenu |
|---|---|
| `ondea-ep1-6-quiz-state` | Quiz en cours : identité, ordre des réponses, réponses, heure de départ (reprise possible après un rechargement) |
| `ondea-ep1-6-quiz-attempts` | Nombre de tentatives par stagiaire |
| `ondea-ep1-6-quiz-timeout` | Tentative arrêtée par le minuteur |
| `ondea-mc-theme`, `ondea-mc-contrast`, `ondea-mc-scale`, `ondea-mc-matrix-v2` | Réglages d'affichage, partagés avec les autres supports Ondea |

Les clés `ondea-ep1-6-quiz-*` sont distinctes de celles du quiz de positionnement (`ondea-pos-quiz-*`). Un stagiaire qui a déjà passé le quiz de positionnement sur le même poste ne retrouve donc pas ses anciennes réponses.

Pour remettre un poste à zéro entre deux groupes : bouton **Recommencer** (après la fin du décompte), ou effacement des données du site dans le navigateur.

---

## Contenu du dossier

```
quiz-episodes-1-6/
├── index.html        ← le quiz complet (HTML, CSS et JavaScript dans un seul fichier)
├── README.md         ← ce document
└── images/           ← les captures d'écran de ce README
    ├── 01-intro.png
    ├── 02-accueil.png
    ├── 03-identification.png
    ├── 04-question.png
    ├── 05-bonne-reponse.png
    ├── 06-mauvaise-reponse.png
    ├── 07a-minuteur-moins-5-min.png
    ├── 07b-minuteur-derniere-minute.png
    ├── 07c-temps-ecoule.png
    ├── 08-bilan.png
    ├── 09-envoi-teams.png
    ├── 10-revoir-reponses.png
    ├── 11-theme-sombre.png
    ├── 12-contraste-maximal.png
    ├── 13-texte-150.png
    ├── 14-mobile-accueil.png
    ├── 15-mobile-question.png
    ├── 16-pdf-page-1.png
    └── 16-pdf-page-2.png
```

### Bibliothèques externes

| Ressource | Rôle | Sans connexion |
|---|---|---|
| Google Fonts : Atkinson Hyperlegible, IBM Plex Mono | Polices du quiz | Polices du système (Verdana, Consolas…) |
| [jsPDF 2.5.1](https://cdnjs.cloudflare.com/ajax/libs/jspdf/2.5.1/jspdf.umd.min.js) (cdnjs) | Génération du bilan PDF | Impression du navigateur en PDF |

---

## Auteur

**Jean-Claude Lugo** · Formateur expert, Centre de Formation MODE 83, Draguignan (Var)
**Ondea Web Studio** · Série « Portfolio TSSR — Lucas Moreau »

Les personnes, données et résultats présentés sur les captures (Marie Dupont, scores) sont fictifs et servent uniquement d'exemple.
