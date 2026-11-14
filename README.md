# 3AM — Again, Another Addon Manager

Oui, encore un gestionnaire d'add-ons. Le vôtre fait peut-être déjà le travail. Celui-ci a quelques tours de plus dans son sac,
pour les soirs où l'on cherche encore pourquoi le simulateur plante à 3 h du matin.

Yes, yet another addon manager. Yours may already do the job. This one has a few more tricks up its sleeve, for the nights
when you're still asking yourself why the simulator crashes at 3 a.m.

---

## Français

### Ce que vous ne trouverez pas ailleurs (à notre connaissance)

- **Les scènes de votre plan SimBrief sur la carte.** Une distance réglable de part et d'autre de la route, et les coches
  départ, arrivée et dégagement. Aucun outil, à notre connaissance, ne combine tout cela.
- **Les avions statiques et les profils GSX dans un seul outil.** Le module SGM est intégré. À notre connaissance,
  c'est le seul outil qui gère les deux.
- **Les bibliothèques d'une scène, avec elle.** 3AM montre les bibliothèques d'objets dont une scène a besoin et les active
  avec elle. La liste dépend de ce que les éditeurs ont déclaré : elle peut être incomplète.
- **Une position devinée pour les scènes sans code d'aéroport.** Elle n'est jamais imposée : vous la confirmez ou vous
  placez la scène vous-même. Les fichiers de scène ne sont pas ouverts. Les scènes « mondiales » (relief, végétation,
  éclairage) sont rangées à part.
- **Gratuit, portable, sans compte ni activation en ligne.** Rien n'est envoyé sans une action de votre part.

### Et aussi

- Une bibliothèque pour ranger les add-ons hors de Community, avec un interrupteur par add-on.
- Des presets : activer exactement un ensemble d'add-ons, et importer ceux d'Addons Linker.
- Édition de Content.xml : une scène de base se désactive par un bouton, avec une copie de sauvegarde.
- Contrôle des fichiers qui se chevauchent (modelLib, materialLibs, layout.json), avec correction et annulation.
- Protection des liens posés par les installateurs (Orbx Central, Contrail…).
- Retour arrière : revenir à une version précédente de l'application.
- Thème clair ou sombre, interface de 75 % à 200 %.
- Recherche guidée de l'add-on qui fait planter le simulateur, avec retour exact à l'état d'avant.

### Configuration requise

- Windows 10 ou 11 (64 bits)
- Microsoft Flight Simulator 2024 et/ou 2020
- Pas de droits administrateur nécessaires.

### Télécharger

- Téléchargez le fichier `3AM.exe` de la dernière version sur la page des [Releases](https://github.com/FuchyBe/Hangar-MSFS/releases).
- Aucune installation : placez-le dans le dossier de votre choix et lancez-le.
- Version **BETA** : tout n'est pas encore parfait. Vos retours aident.

### Premier lancement

Windows peut afficher « Windows a protégé votre ordinateur », car le programme n'est pas encore signé.
Cliquez sur « Informations complémentaires », puis sur « Exécuter quand même ».

### Signaler un problème / proposer une idée

- Dans l'application : **Aide › Signaler un problème…** ou **Aide › Proposer une idée…**.
- Ou directement sur la page des [Issues](https://github.com/FuchyBe/Hangar-MSFS/issues). Un compte GitHub gratuit est nécessaire.
- Le texte est transmis à GitHub pour remplir la page ; rien n'est publié tant que vous ne l'avez pas validé, et le signalement est **public**.
- Ne collez jamais une clé d'API ni une adresse e-mail.

### Vie privée

3AM n'envoie rien tout seul : pas de télémétrie. 3AM ne se connecte à Internet que sur votre demande,
pour récupérer un plan de vol SimBrief, pour afficher une carte en ligne ou pour vérifier une mise à jour.

La vérification de mise à jour contacte github.com. Elle a lieu si vous cliquez sur **Aide › Rechercher une mise à
jour…**, ou une fois par jour au plus si vous avez coché **Vérifier au démarrage** (décochée par
défaut). Elle envoie une seule demande à GitHub, qui contient votre adresse Internet et le numéro de version de
3AM. Le téléchargement d'une nouvelle version ne commence que si vous cliquez sur **Mettre à jour et redémarrer**.

### Vos fichiers

3AM n'efface jamais un add-on : il ne supprime que ses propres liens, après les avoir vérifiés. Le simulateur doit être
fermé avant toute modification.

### Mises à jour

3AM peut chercher et installer une nouvelle version (**Aide › Rechercher une mise à jour…**, à partir de la 0.8.4).
Le fichier téléchargé est vérifié (taille et empreinte SHA-256) avant d'être installé. Ce contrôle protège contre un
fichier abîmé, pas contre un compte GitHub piraté.

Si vous avez **Hangar 0.8.x**, la mise à jour intégrée vous amène à 3AM : vos réglages sont repris.

Les versions 0.8.3 et avant ne savent pas se mettre à jour : téléchargez une fois la nouvelle version à la main,
depuis l'onglet **Releases**.

### Auteur et licence

3AM est créé par **Fabian Fuchs**. Le projet est indépendant : il n'est ni affilié, ni approuvé par Microsoft,
Asobo Studio ou les développeurs d'add-ons. Microsoft Flight Simulator est une marque de Microsoft Corporation.

3AM est fourni « tel quel », sans garantie.

---

## English

### What you won't find anywhere else (to our knowledge)

- **Your SimBrief flight plan scenery on the map.** An adjustable distance either side of the route, and tick boxes for
  departure, arrival and alternate. To our knowledge, no other tool combines all of this.
- **Static aircraft and GSX profiles in one tool.** The SGM module is built in. To our knowledge, it is the only tool
  that handles both.
- **A scene's libraries, along with the scene.** 3AM shows the object libraries a scene needs and turns them on with it.
  The list depends on what the publishers declared, so it may be incomplete.
- **A guessed position for scenery without an airport code.** It is never forced on you: you confirm it or place the
  scene yourself. Scene files are not opened. "Worldwide" scenery (terrain, vegetation, lighting) is kept apart.
- **Free, portable, no account and no online activation.** Nothing is sent without an action from you.

### Also included

- A library to keep your add-ons out of Community, with one switch per add-on.
- Presets: activate an exact set of add-ons, and import Addons Linker presets.
- Content.xml editing: a base scene is turned off with one button, with a backup copy first.
- Checks for overlapping files (modelLib, materialLibs, layout.json), with fixes you can undo.
- Protection for links placed by installers (Orbx Central, Contrail…).
- Rollback: go back to an earlier version of the application.
- Light or dark theme, interface from 75% to 200%.
- Guided search for the add-on that crashes the simulator, with an exact return to how things were.

### Requirements

- Windows 10 or 11 (64-bit)
- Microsoft Flight Simulator 2024 and/or 2020
- No administrator rights needed.

### Download

- Get the `3AM.exe` file of the latest version from the [Releases page](https://github.com/FuchyBe/Hangar-MSFS/releases).
- No installation: put it in the folder of your choice and run it.
- **BETA** version: not everything is perfect yet. Your feedback helps.

### First launch

Windows may show "Windows protected your PC", because the program is not signed yet.
Click "More info", then "Run anyway".

### Report a problem / suggest an idea

- In the app: **Help › Report a problem…** or **Help › Suggest an idea…**.
- Or directly on the [Issues page](https://github.com/FuchyBe/Hangar-MSFS/issues). A free GitHub account is required.
- The text is passed to GitHub to fill in the page; nothing is published until you confirm it, and reports are **public**.
- Never paste an API key or an e-mail address.

### Privacy

3AM does not send anything on its own: no telemetry. 3AM only connects to the Internet when you ask it to,
to fetch a SimBrief flight plan, to show an online map or to check for an update.

The update check contacts github.com. It happens when you click **Help › Check for updates…**, or at most once a
day if you have ticked **Check at startup** (unticked by default). It sends a single request to GitHub,
which contains your Internet address and 3AM's version number. Downloading a new version only starts when you
click **Update and restart**.

### Your files

3AM never deletes an add-on: it only removes its own links, after checking them. The simulator must be closed
before any change is made.

### Updates

3AM can check for and install a new version (**Help › Check for updates…**, from version 0.8.4).
The downloaded file is checked (size and SHA-256 fingerprint) before it is installed. This check protects against a
damaged file, not against a hacked GitHub account.

If you have **Hangar 0.8.x**, the built-in update brings you to 3AM: your settings are carried over.

Versions 0.8.3 and earlier cannot update themselves: download the new version once by hand, from the **Releases** tab.

### Author and licence

3AM is created by **Fabian Fuchs**. This is an independent project: it is not affiliated with or endorsed by
Microsoft, Asobo Studio or add-on developers. Microsoft Flight Simulator is a trademark of Microsoft Corporation.

3AM is provided "as is", without warranty.
