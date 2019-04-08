# Tutoriel Visual Studio Code

## Configuration

- `File > Preferences > Settings`, ou via `Ctrl + Shift + P` (Command Palette) en tappant `Open Settings`
- la configuration est enregistrée dans les fichiers `settings.json`
    - **User Settings** appliqué à l'instance de VS Code
    - **Workspace Settings** appliqué uniquement quand le workspace est ouvert
    - **Folder Settings** dans le dossier `.vscode` à la racine du projet
- il est possible d'avoir de la configuration globale et de la configuration spécifique à certains langage

## Raccourcis claviers

- formatter le code : `Alt + Shift + F` (`Ctrl + Shift + I` sur Linux)

## Exécuter un main Java

- cliquer sur `Run` (`Ctrl + F5`) ou `Debug` (`F5`) au dessus de la classe **Main**
- possibilité de faire `F5` pour faire Run, il faut alors supprimer ou désactiver les points d'arrêts pour tout exécuter sans s'arrêter
- création d'un fichier `launch.json` dans le dossier `.vscode` à la racine du projet

## Mode débug

- appuyer sur `F9` lorsqu'on est sur une ligne permet de mettre ou d'enlever un breakpoint (rond rouge si activé, rond gris si désactivé)
- on peut ajouter un logpoint (forme de diamant) qui n'arrête pas le programme mais écrit dans la log (le texte entre accolades est interprété)