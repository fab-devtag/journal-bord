✅ Projet Bloc 3 — Journal de Bord Personnel (App Router / Local / Sans Internet)
🧠 Objectif
Créer une mini-application Next.js en local, sans base de données distante, ni authentification en ligne, pour pratiquer :

App Router

Routing dynamique

React + state management

API Routes (mock en local)

Tailwind CSS

CRUD local (fichier JSON ou en mémoire)

Réactivité, logique métier

Bonne structuration

🧩 Fonctionnalité globale
Un journal de bord personnel où l’on peut :

Créer une entrée de journal (titre, date, contenu, humeur)

Lister toutes les entrées

Filtrer par humeur ou mot-clé

Modifier ou supprimer une entrée

Visualiser une entrée en détail

📁 Structure du projet
/app

/entries → page de liste

[id]/page.tsx → détail d’une entrée

new/page.tsx → création

[id]/edit/page.tsx → édition

/api/entries/route.ts → mock des opérations CRUD (lecture/écriture dans un entries.json ou simple array en mémoire)

/components

EntryCard.tsx, EntryForm.tsx, etc.

✅ Étapes à suivre
1. Setup de base
 Créer un nouveau projet Next.js (avec app directory)

 Installer et configurer Tailwind CSS

 Créer la structure /app/entries + pages nécessaires

 Créer un fichier de données JSON simulant quelques entrées

2. Page Liste
 Lister les entrées de journal (mockées ou stockées localement)

 Afficher titre, date, humeur dans des EntryCard

 Ajouter filtre par humeur / mot-clé

3. Page Détail
 Afficher le contenu complet d’une entrée

 Afficher l’humeur avec une couleur ou une icône

 Ajouter un bouton "Modifier"

4. Page Création
 Formulaire avec champs : titre, date, humeur (select), contenu

 Stockage en local (dans un array temporaire ou fichier JSON modifiable)

 Redirection vers la liste après soumission

5. Page Édition
 Charger les données de l’entrée sélectionnée

 Remplir le formulaire avec les données existantes

 Sauvegarder les modifications

6. Suppression
 Bouton "Supprimer" sur la page de détail

 Mise à jour du store local après suppression

7. UI / UX
 Utiliser Tailwind pour styliser joliment l’interface

 Responsivité minimum

 Ajouter un petit message si aucune entrée n’est présente

💡 Bonus (si temps restant)
 Tri par date (asc/desc)

 Animation avec Framer Motion

 Barre de recherche rapide

 Ajouter des tags (bonus de structure)

✅ Livrable final attendu
Un projet local Next.js proprement structuré

Fonctionnel en local sans Internet

Avec au moins 5 entrées de test (mock)

Code lisible, clair, structuré

Quand tu as terminé, reviens ici et on fera :

Revue de code,

Vérification de la logique,

Passage au Bloc 4 (entretiens blancs / finalisation avant postuler).

Bon trajet et bon code ! 💪🚆