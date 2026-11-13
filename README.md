# Hangar — MSFS Addon Manager · **BETA**

Gestionnaire d'add-ons pour Microsoft Flight Simulator 2024 et 2020, avec carte et module SGM intégré.
Par **Fabian Fuchs**.

---

## Français

### Ce qu'est Hangar

Hangar range vos add-ons **hors** du dossier Community, dans des bibliothèques que vous choisissez.
Activer un add-on crée un **lien** vers lui dans Community ; le désactiver supprime ce lien.
Le simulateur ne charge que ce qui est actif.

Hangar contient aussi :

- une **carte** : chaque scène est placée sur son aéroport ;
- le module **SGM** (Statics & GSX Manager).

Hangar est un programme **portable** : rien à installer.

### Configuration requise

- Windows 10 ou 11 (64 bits)
- Microsoft Flight Simulator 2024 et/ou 2020
- Pas de droits administrateur nécessaires.

### Télécharger

Les versions sont publiées dans l'onglet **Releases** de ce dépôt. Si aucune version n'y figure encore, les versions publiques arriveront ici.

À partir de la 0.8.4, Hangar peut se mettre à jour lui-même (Aide › Rechercher une mise à jour…).

### Premier lancement

Windows peut afficher « Windows a protégé votre ordinateur », car le programme n'est pas encore signé.
Cliquez sur « Informations complémentaires », puis sur « Exécuter quand même ».

### Signaler un problème ou proposer une idée

- Depuis Hangar : **Aide › Signaler un problème…** ou **Aide › Proposer une idée…**. Une page GitHub s'ouvre
  avec le texte déjà rempli.
- Ou directement ici : onglet **Issues**, bouton **New issue**.

Un compte GitHub gratuit est nécessaire. Le texte est transmis à GitHub pour remplir la page ; rien n'est publié tant que vous ne l'avez pas validé.
Le signalement est **public**.

- Joindre le journal des erreurs est facultatif. Hangar masque vos dossiers personnels et les clés d'API qu'il reconnaît : relisez quand même l'aperçu avant d'envoyer.
- Ne collez jamais une clé d'API ni une adresse e-mail.

### Vie privée

Hangar n'envoie rien tout seul : pas de télémétrie. Hangar ne se connecte à Internet que sur votre demande,
pour récupérer un plan de vol SimBrief, pour afficher une carte en ligne ou pour vérifier une mise à jour.

La vérification de mise à jour contacte github.com. Elle a lieu si vous cliquez sur **Aide › Rechercher une mise à
jour…**, ou une fois par jour au plus si vous avez coché **Vérifier les mises à jour au démarrage** (décochée par
défaut). Elle envoie une seule demande à GitHub, qui contient votre adresse Internet et le numéro de version de
Hangar. Le téléchargement d'une nouvelle version ne commence que si vous cliquez sur **Mettre à jour et redémarrer**.

### Mises à jour

Hangar peut chercher et installer une nouvelle version. Le fichier téléchargé est vérifié (taille et empreinte
SHA-256) avant d'être installé. Ce contrôle protège contre un fichier abîmé, pas contre un compte GitHub piraté.

Les versions 0.8.3 et avant ne savent pas se mettre à jour : téléchargez une fois la nouvelle version à la main,
depuis l'onglet **Releases**.

### Auteur et licence

Hangar est créé par **Fabian Fuchs**. Le projet est indépendant : il n'est ni affilié, ni approuvé par Microsoft,
Asobo Studio ou les développeurs d'add-ons. Microsoft Flight Simulator est une marque de Microsoft Corporation.

Hangar est fourni « tel quel », sans garantie.

---

## English

### What Hangar is

Hangar keeps your add-ons **outside** the Community folder, in libraries of your choice.
Turning an add-on on creates a **link** to it in Community; turning it off removes that link.
The simulator only loads what is active.

Hangar also includes:

- a **map**: each scenery is placed on its airport;
- the **SGM** module (Statics & GSX Manager).

Hangar is **portable**: nothing to install.

### Requirements

- Windows 10 or 11 (64-bit)
- Microsoft Flight Simulator 2024 and/or 2020
- No administrator rights needed.

### Download

Versions are published in the **Releases** tab of this repository. If no version is listed there yet, public versions will be posted here.

From version 0.8.4, Hangar can update itself (Help › Check for updates…).

### First launch

Windows may show "Windows protected your PC", because the program is not signed yet.
Click "More info", then "Run anyway".

### Report a problem or suggest an idea

- From Hangar: **Aide › Signaler un problème…** (Help › Report a problem…) or **Aide › Proposer une idée…**
  (Help › Suggest an idea…). A GitHub page opens with the text already filled in.
- Or directly here: **Issues** tab, **New issue** button.

A free GitHub account is required. The text is passed to GitHub to fill in the page; nothing is published until you confirm it.
Reports are **public**.

- Attaching the error log is optional. Hangar hides your personal folders and the API keys it recognises: still read the preview before sending.
- Never paste an API key or an e-mail address.

### Privacy

Hangar does not send anything on its own: no telemetry. Hangar only connects to the Internet when you ask it to,
to fetch a SimBrief flight plan, to show an online map or to check for an update.

The update check contacts github.com. It happens when you click **Help › Check for updates…**, or at most once a
day if you have ticked **Check for updates at startup** (unticked by default). It sends a single request to GitHub,
which contains your Internet address and Hangar's version number. Downloading a new version only starts when you
click **Update and restart**.

### Updates

Hangar can check for and install a new version. The downloaded file is checked (size and SHA-256 fingerprint)
before it is installed. This check protects against a damaged file, not against a hacked GitHub account.

Versions 0.8.3 and earlier cannot update themselves: download the new version once by hand, from the **Releases** tab.

### Author and licence

Hangar is created by **Fabian Fuchs**. This is an independent project: it is not affiliated with or endorsed by
Microsoft, Asobo Studio or add-on developers. Microsoft Flight Simulator is a trademark of Microsoft Corporation.

Hangar is provided "as is", without warranty.
