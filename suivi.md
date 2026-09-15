# Suivi J1 — Cap Web

Note ton avancée après chaque TP. Reste factuel, sans données personnelles. Ce fichier te sert pour la capsule et le bilan.

## TP00 — Diagnostic

- Hypothèse : le problème venait surtout de la cascade CSS et des largeurs fixes.
- Action : j'ai corrigé la hiérarchie des titres, ajouté `main`, j'ai rendu les largeurs plus souples et ainsi complété les deux fonctions JavaScript.
- Résultat : la validation avec `trim()` et le filtrage des personnes actives sont faits. La page reste affichable en local.
- Point non compris : les étiquettes associées aux champs et le vrai bouton du formulaire sont encore à reprendre dans le diagnostic.

## TP01 — Démarrer

- Hypothèse : si le JavaScript ne charge pas, la page HTML s'affiche quand même, mais le message de départ ne s'affiche pas.
- Action : j'ai vérifié la page de départ et essayé de lancer le serveur depuis le dossier `atelier`.
- Résultat : le serveur tournait déjà sur le port 3000. J'ai bien repéré `main`, `h1` et `p#status`.
- Point non compris : rien pour le moment.

## TP02 — HTML

- Hypothèse : remplacer `main` par `div` ne change pas vraiment le visuel, mais enlève le repère principal pour l'accessibilité.
- Action : j'ai ajouté le `header`, la section Discussion, la liste de messages et le `footer`.
- Résultat : il n'y a qu'un seul `h1`, la section est reliée à son titre et le statut est conservé.
- Point non compris : rien pour le moment.

## TP03 — Formulaire

- Hypothèse : dans un `textarea`, la touche Entrée ajoute une ligne ; pour envoyer, il faut aller sur le bouton avec Tab puis appuyer sur Entrée.
- Action : j'ai ajouté l'étiquette, la zone de texte, le bouton Envoyer et le JavaScript fourni.
- Résultat : après l'envoi, le statut affiche « Interface prête ; les réponses arrivent au J2. ».
- Point non compris : rien pour le moment.

## TP04 — Responsive

- Hypothèse : un mot très long peut faire déborder la page sur un petit écran s'il ne peut pas se couper.
- Action : j'ai ajouté `box-sizing`, des largeurs souples, un formulaire en colonne, un focus visible et une règle pour couper les mots trop longs.
- Résultat : le champ et le bouton gardent une largeur correcte dans la mise en page.
- Point non compris, test 360 / 1280 : les 9 tests ont été validés, avec 9 réussis et 0 échec.

## Commandes essayées

Note chaque commande avec son dossier de lancement et son résultat exact. Exemple d'état local, depuis la racine étudiante :

```sh
# depuis RACINE_ETUDIANT
git status
git diff
```

Mes essais :

- Dossier :
- Commande et résultat :
- Problème exact si blocage :

Si Node ou Git bloque, note le message exact et continue en local sans attendre. Le double-clic sur `diagnostic/index.html` ne remplace pas le serveur pour les modules et l'envoi du TP03.

## Auto-revue finale

- Ce qui s'affiche bien :
- Ce qui reste fragile au clavier ou à 360 px :
- Ce que je veux revoir en capsule :

## Rappel Git prudent

Git reste optionnel le matin. Vérifie l'état local, ne valide que des fichiers nommés un par un et seulement si Git est configuré. Reste en local ou en ZIP sauf si le formateur précise le circuit avec fork personnel. Aucune invitation ni demande de fusion requise le matin.

## Liens

- [README](README.md)
- [TP00](tp/00-diagnostic.md)
- [TP05](tp/05-bilan.md)
- [Aide-mémoire](ressources/aide-memoire.md)
