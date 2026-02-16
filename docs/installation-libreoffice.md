# Guide d'installation - LibreOffice (Windows 10/11)

:::note Version d'installation
Ce guide utilise la version **26.2.0** de libre office
:::

## 1. Mise en contexte

LibreOffice est une suite bureautique libre et gratuite qui permet de creer :

- des documents texte (`Writer`)
- des feuilles de calcul (`Calc`)
- des presentations (`Impress`)

Ce guide présente l'installation de la suite LibreOffice sur un poste Windows 10 ou Windows 11 en français.

:::info Information complementaire
Il est recommande de telecharger LibreOffice uniquement depuis le site officiel afin d'eviter les versions modifiees.
Les instructions pour
mettre à jour **Windows** sont
disponibles [ici](https://support.microsoft.com/en-us/windows/install-windows-updates-3c5ae7fc-9fb6-9af1-1984-b5e0412c556a)
:::

## 2. Configuration requise

- Systeme d'exploitation : Windows 10 ou Windows 11 (64 bits)
- Droits requis : administrateur local
- Espace disque : environ 1,5 Go disponibles
- Memoire vive : 256 Mo minimum
- Resolution d'ecran : 1280 x 800 minimum
- Connexion Internet : requise pour le telechargement

:::tip Bon réflexe
Assurez-vous que Windows est a jour avant l'installation. Cela reduit les risques d'erreurs d'installation.
:::

## 3. Prerequis

- Un navigateur web fonctionnel
- Un accès au site
  officiel : [https://www.libreoffice.org/download/download-libreoffice/](https://www.libreoffice.org/download/download-libreoffice/)

## 4. Procedure d'installation

### 4.1 Téléchargement de libre office

Pour télécharger LibreOffice,

1. Ouvrir un navigateur web.
2. Acceder à la page de téléchargement officielle de libre
   office. [https://www.libreoffice.org/download/download-libreoffice/](https://www.libreoffice.org/download/download-libreoffice/)
3. Cliquer sur **Telecharger** (version Windows 64 bits).
4. Enregistrer le fichier d'installation (`.msi`) sur le poste.

### 4.2 Installation de libre office

Pour installer LibreOffice,

#### 4.2.1 Exécuter le fichier téléchargé.

À partir de votre explorateur de fichiers, exécuter le fichier d'installation téléchargé (`.msi`) en double-cliquant
dessus.

#### 4.2.2 Accueil de l'assistant d'installation

L'installation commence par l'accueil de l'assistant d'installation. Appuyer sur **Next** pour continuer.

![Accueil de l'assistant d'installation](assets/installation-libreoffice/Screenshot%202026-02-14%20231507.png)

#### 4.2.3 Type d'installation

Dans le menu de type d'installation, choisissez (**Custom**) afin de pouvoir changer la langue de l'interface de libre
office.

![Type d'installation](assets/installation-libreoffice/Screenshot%202026-02-14%20231521.png)

#### 4.2.4 Choix des composants

Dans le menu de choix des composants, sélectionner le module `User interface languages`

![Choix des composants](assets/installation-libreoffice/Screenshot%202026-02-14%20231619.png)

Puis dans la liste qui s'affiche sélectionner `French` et sélectionner
`This feature will be installed on local hard drive` afin d'installer la langue française pour l'interface de libre
office.

![Choix des composants](assets/installation-libreoffice/Screenshot%202026-02-14%20234539.png)

Désélectionner les langues anglaises déja sélectionnées dans la liste en cliquant sur
`This feature will not be available` pour la langue sélectionnée.

![Choix des composants](assets/installation-libreoffice/Screenshot%202026-02-14%20234557.png)

:::info Information complementaire
Si vous souhaitez installer d'autres langues, vous pouvez les sélectionner à cette étape.
:::

#### 4.2.5 Définir les applications par défaut

Dans ce menu, vous pouvez configurer quel application qui sera utilisé pour ouvrir les fichiers de type `docx`, `xlsx`
et `pptx`. Par défaut, les applications Microsoft Office sont sélectionnées pour ouvrir ces types de fichiers. Si vous
souhaitez que les applications de libre office soient utilisées par défaut pour ouvrir ces types de fichiers,
sélectionner les options correspondantes.

![Aplication par defaut](assets/installation-libreoffice/Screenshot%202026-02-14%20231738.png)

#### 4.2.6 Configuration bureau
Dans le prochain menu, pour rendre la suite libre office accessible depuis le bureau, sélectionner l'option **Ajouter
   une icone sur le bureau**.

![Configuration bureau](assets/installation-libreoffice/Screenshot%202026-02-14%20231756.png)

#### 4.2.7 Installation
1.  Cliquer sur **Installer**. 
2. 2Attendre la fin du processus.
3. Fermer l'assistant d'installation.

:::warning Information complémentaire
Si une fenêtre de contrôle de compte utilisateur (UAC) apparait, cliquer sur **Oui** pour autoriser l'installation.
:::

## 5. Verification post-installation

Verifier les elements suivants :

1. LibreOffice s'ouvre correctement.
2. Les modules `Writer`,  `Calc`,  `Impress`, `Math`, `Draw` et `Base` sont accessibles ainsi que l'application `LibreOffice`
3. La version installée est visible dans **Aide > A propos** dans LibreOffice.

:::info Information complémentaire
Vous pouvez épingler LibreOffice a la barre des taches pour un acces rapide.
:::

## 6. Dépannage

### 6.1 L'installation ne démarre pas

- **Symptôme** : l'installation ne démarre pas.
- **Cause probable** : droits insuffisants.
- **Solution** : relancer le programme d'installation en tant qu'administrateur.

### 6.2 L'application ne s'ouvre pas

- **Symptome** : LibreOffice ne s'ouvre pas apres l'installation.
- **Cause probable** : installation incomplete.
- **Solution** : redemarrer le poste puis relancer l'application. Reinstaller si necessaire.

:::tip Information complementaire
En cas de probleme persistant, desinstaller LibreOffice puis refaire une installation propre avec la version la plus
recente.
:::

## 7. Metadonnees

- Version du document : 1.1
- Derniere mise a jour : 2026-02-15
- Public cible : interne (TI)
