# DaySmart — suite du projet

DaySmart est actuellement une application web hébergée gratuitement avec GitHub Pages.

## État actuel

- Tâches, habitudes et activités : conservées.
- Calendrier et objectifs : ajoutés.
- Exportation/importation JSON : disponible pour sauvegarder et restaurer les données.
- Application web installable (PWA) : manifeste et service worker présents.
- Synchronisation entre plusieurs appareils : **pas encore activée**.
- Publication Google Play : pas encore préparée ni soumise.

## Vérification sur Android

1. Ouvrir https://daysmart233.github.io/DaySmart/
2. Tester la création, la modification et la suppression d'une tâche.
3. Tester une habitude, une activité, le calendrier et un objectif.
4. Dans Réglages, choisir **Exporter mes données** et conserver le fichier.
5. Tester l'importation uniquement avec une copie de sauvegarde.
6. Dans Chrome, ouvrir le menu ⋮ et choisir **Ajouter à l'écran d'accueil** ou **Installer l'application** si l'option est proposée.

## Sauvegarde en ligne : pourquoi il reste une étape

Les données sont pour l'instant stockées dans le navigateur de l'appareil. Pour synchroniser plusieurs téléphones, il faut configurer un service cloud (par exemple Supabase ou Firebase), définir les règles de sécurité et tester l'accès utilisateur. Il ne faut jamais mettre une clé secrète d'administration dans le code public. Avant la configuration du cloud, exporter une sauvegarde JSON.

## Publication Google Play

Une application web peut être installée depuis le navigateur sans frais. Une publication dans Google Play est une procédure différente : il faut un compte Play Console, des informations de développeur, un paquet Android conforme et des tests. Google demande généralement des frais d'inscription de 25 USD pour le compte développeur; les comptes personnels récents peuvent aussi devoir effectuer un test fermé avant de demander l'accès à la production. Si le développeur est mineur, un adulte éligible doit gérer le compte selon les règles de Google.

## Liens

- Application : https://daysmart233.github.io/DaySmart/
- Dépôt : https://github.com/DaySmart233/DaySmart
- Aide Google Play Console : https://support.google.com/googleplay/android-developer/
