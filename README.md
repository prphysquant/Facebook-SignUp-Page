1. Structure générale de mon travail

index.html → structure de la page et le styles.css et un readme.md

2. Balises HTML importantes que j'ai utilusé

<div class="card"> → le conteneur principal du formulaire

<input> → les champs où l’utilisateur écrit (nom, email, mot de passe…)

<select> → les menus déroulants pour choisir la date de naissance

<label> → les textes associés aux boutons radio (Homme, Femme, Personnalisé)

<button> → le bouton “S’inscrire”

<hr> → une ligne horizontale de séparation

3. CSS et mise en page

.card → crée une carte blanche au centre de la page, avec ombre et coins arrondis

display: flex; → utilisé pour aligner les éléments sur la même ligne

gap: → espace entre les éléments

border-radius: → arrondit les coins

transition: → rend les effets plus doux (par exemple, le changement de couleur des bordures)

4. Effet interactif

Quand tu cliques sur un champ (input ou select), la bordure devient noire grâce à :

input:focus {
  border-color: black;
}


Cela rend le formulaire plus dynamique et professionnel.

5. Responsive design

Les media queries à la fin du fichier permettent d’adapter l’affichage aux petits écrans :

@media (max-width: 768px) { ... }


Sur mobile, les champs passent en colonne, et les marges changent pour garder un bon rendu.

Et enfin la del déployement de la page : 
