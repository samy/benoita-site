---
layout: post
title:  "Extraire le texte des images"
---
Une des étapes de ce projet sera de scanner toutes les pages de l'ouvrage pour le rendre disponible, mais il faudra en extraire le texte pour qu'il soit exploitable.

J'ai donc développé un outil très simple pour cette tâche: https://github.com/samy/benoita

Il s'agit d'un petit programme en Python, qui permet de générer ensuite des PDF dans lesquels on peut copier le texte.

Petit exemple ci dessous avec une page issue de l'Ile Mystérieuse.

<object data="https://benoita.fr/assets/exemple.pdf" type="application/pdf" width="100%" height="500px">
      <p>Unable to display PDF file. <a href="https://benoita.fr/assets/exemple.pdf">Exemple</a> instead.</p>
</object>