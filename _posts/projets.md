---
layout: default
title: Projets
permalink: /projets/ 
---

<h2 class="soustitre">Les projets</h2>
<p class="texte">
  Ici on peut mettre un texte explicatif pour décrire nos attentes vis-à-vis des projets proposés, les
  conditions à respecter.
  Et donner des informations essentielles comme par exemple ce qu'il est possible ou non de faire.
</p>

<section class="container-formulaire">
    <h2 class="soustitre">Nous proposer un projet ?</h2>
    <form action="/submit" method="POST">
        <p><label for="name">Votre Nom :</label>
        <input type="name" id="name" name="name" required placeholder="Entrez votre nom"></p>
        <p><label for="email">Votre Email :</label>
        <input type="email" id="email" name="email" required placeholder="Entrez votre email"></p>
        <p><label for="project-name">Le nom du projet :</label>
        <input type="text" id="project-name" name="project-name" required placeholder="Nom du projet"></p>
        <p><label for="message">Message :</label>
        <textarea id="message" name="message" rows="4" cols="50" placeholder="Entrez votre message"
            required></textarea></p>

        <button type="submit">Envoyer</button>
    </form>
</section>
