# Historique

Historique des décisions, réunions, et point d’étape, du plus récent au plus ancien.

## [2017-06-06] 

* Le projet éditorial concerne une grosse vingtaine de titres.
* À terme, un titre doit être composé d’un texte, précédé d’une introduction, suivi de notes longues, chacune raccrochée par un indentifiant à un paragraphe du texte.
* Les titres sont produits au traitement de textes, sous la forme de trois fichiers séparés. Le nom de fichier commence toujours par le code de texte (à définir), suivi pour les annexes par des suffixes standardisés -front (pour l’introduction), -back (pour les notes).
* La conversion XML peut avoir 2 états, "xmlwork" (xml temporaire, texté établi mais pas encore commenté), "xml" (xml définitif).
* Un fichier qui passe dans le dossier "xml" doit potentiellement pourvoir recevoir son ISBN, il est “fini”.
* Un formulaire doit être développé pour assurer la fusion entre les trois fichiers traitement de texte (format ODT), et rendre un fichier XML.
* Le site devra permettre de lire texte et notes en parallèle (si l’écran est assez large)
* Le site se mettra à jour en lisant les dossiers xmlwork et xml du github.
* La page d’accueil du site sera le README.md du github, avec un chapeau de présentation et la bibliographie du projet en trois sections : les textes commentés, les textes relus, et les textes prévus.
