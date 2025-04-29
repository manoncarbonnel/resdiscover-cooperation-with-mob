---
theme: ./slidev-theme-shodo
title: "Redécouvrir la coopération : Atelier de Mob Programming"
info: |  
highlighter: shiki
drawings:
  persist: false
transition: slide-left
mdc: true
layout: cover
---

# Redécouvrir la coopération

<div class="subtitle">Atelier de mob programming</div>

<!--
The last comment block of each slide will be treated as slide notes. It will be visible and editable in Presenter Mode along with the slide. [Read more in the docs](https://sli.dev/guide/syntax.html#notes)
-->

---
layout: intro
---

**Manon Carbonnel**
<br/>

<ul>
    <li>Développeuse et intégratrice web</li>
    <li>Facilitatrice Agile</li>
    <li>Animatrice chez <a target="_blank" href='https://mobilizon.fr/@dev_en_equipe' title="Mob Prog FR - lien externe">MobProgFR</a></li>
    <li><a target="_blank" href='https://bento.me/manoncarbonnel' title="Site web de Manon - lien externe">https://bento.me/manoncarbonnel</a></li>
</ul>


---
layout: intro
---

**Nathan Castelein**
<br/>

<ul>
    <li>Développeur</li>
    <li>Cofondateur de Shodo Lille</li>
    <li><a target="_blank" href='https://bento.me/nathancastelein' title="Site web de Nathan - lien externe">https://bento.me/nathancastelein</a></li>
</ul>

---
transition: slide-up
---

# C'est quoi le mob programming ?

|     |     |
| --- | --- |
| ✋ Vous avez déjà entendu parler de la pratique  | <Counter :count="0" /> |
| <v-click>✋ Vous avez déjà pratiqué </v-click> | <Counter :count="0" /> |

<br/>
<br/>

<v-click>

Le développement en équipe (mob ou ensemble programming ou Software Teaming) c'est rassembler

<span v-mark.red="3">toutes les personnes</span> nécessaires
au succès d'<span v-mark.red="3">une tâche</span>
autour d'<span v-mark.red="3">un seul poste de travail</span>.

</v-click>

---

# Vos attentes

```md {monaco} { editorOptions: { wordWrap:'on'} }
Pourquoi êtes-vous ici ?

- 
- 
- 
-
-

Vous avez envie de repartir avec :

- 
- 
- 
-

```
---
layout: quote
class: text-center
transition: slide-up
---

Pour qu'une idée arrive dans le code, elle doit passer par le cerveau de quelqu'un d'autre.

*Llewellyn Falco*


---
layout: image
image:  /baba-is-you.avif
transition: slide-up
---


---
layout: image-right
image:  /mob-andrea-zuill.png
transition: slide-up
---

# Roles

---

# Driver ou traducteur-ice

Personne au clavier

- Ne décide pas
- Implémente du mieux qu'iel peut
- Pose des questions pour clarifier

ℹ️ Aucune initiative.

---

# Navigator ou co-pilote

Extrait la connaissance de l'équipe

- Explique l'intention au driver
- Au plus haut niveau possible
- Jusqu'à l'explication des touches

ℹ️ Sélectionne une idée du groupe.

<v-click>

Par exemple :

```md {monaco} { editorOptions: { wordWrap:'on'} }
1 - « Peux-tu écrire un test pour le cas Buzz ? »
2 - « Écris un test qui vérifie que quand on appelle la fonction avec le nombre 5 on retourne "Buzz" »
3 - « Tu peux dupliquer le bloc de code entre la ligne 17 et 23, et changer les valeurs ligne 18 et 22 »
```
</v-click>

---

# Mobber ou équipier-ère

- Proposer des idées
- Soutenez les idées des autres
- Lâchez prise
- Parlez au bon moment

ℹ️ Cherche comment aider, ou écoute attentivement.

---
layout: quote
class: text-center
transition: slide-up
---

Le but n’est pas de faire de l’art, c’est d’être dans cet état merveilleux qui rend l’art inévitable.

*Robert Henri*

---
transition: slide-up
layout: image-right
image: /psychological-safety-daniel-tuttle-DezqNIFG8jk-unsplash.jpg
---

# Sécurité psychologique

Partez du principe que nous sommes toustes très compétents et compétentes.

<v-click>
  <ul>
    <li>Droit à l’erreur</li>
    <li>Partager ses échecs</li>
    <li>Favoriser la parole des personnes moins privilégiées</li>
    <li>Esprit de soutien et entraide</li>
    <li>Écoute active</li>
    <li>Laisser son ego de côté</li>
    <li>Évite l'aide infligée</li>
  </ul>
</v-click>

<small>Amy Edmondson & Aristote project</small>

---

# TDD - Développement guidé par les tests

|                                                |                        |
|------------------------------------------------|------------------------|
| ✋ Vous avez déjà entendu parler de la pratique | <Counter :count="0" /> |
| <v-click> ✋ Vous avez déjà pratiqué </v-click> | <Counter :count="0" /> |

<v-click>
</br>

3 phases du cycle
1. Rouge (test simple qui échoue)
2. Green (solution la plus facile)
3. Refactor (plus propre si nécessaire)

</v-click>

---

# Disclaimer

- On ne finira l'exercice de code
- On ne codera pas comme vous l'auriez fait seul·e

<v-click>Mais <span v-mark.red="1">c'est pas grave</span>, avancer ensemble et s'amuser c'est plus important.</v-click>

---
transition: slide-up
---

# Bilan de vos attentes

```md {monaco} { editorOptions: { wordWrap:'on'} }
Vous avez validé :

- 
- 
- 
-

Vous auriez aimé repartir avec :

- 
- 
- 

```

---
layout: center
class: text-center
---

# Bonus

Des petits liens cool

---
layout: center
class: text-center
---

<div grid="~ cols-2 gap-20">
    <div>
      <h2>Ensemble Toolbox</h2>
      <h3>Facilitez vos sessions de travail en équipe</h3>
      <br/>
      <Youtube id="c_oW0yJWveQ" width="100%" height="250px" />
    </div>
    <div>
      <h2>Ca vaut le coût !</h2>
      <h3>Combien coûte vraiment "ce truc là" ?</h3>
      <br/>
      <Youtube id="JXs7wNMq5dk" width="100%" height="250px" />
    </div>
</div>

---
layout: center
class: text-center
---

# Mob Time

Gérer le chrono et la rotation des rôles facilement

<a target="_blank" href="https://mobtime.hadrienmp.fr/" title="Appli Mob Time - lien externe">mobtime.hadrienmp.fr</a>

<small>Une application développée par
  <a target="_blank" href="https://www.linkedin.com/in/hadrien-mens-pellen-39071231" title="Profil LinkedIn de Hadrien Mens Pellen - lien externe">Hadrien Mens Pellen</a> 🐙
</small>

---
layout: end
---

Vous étiez au top !

---
layout: image-left
image:  /qrcode_openfeedback.io.png
---

## 👈 Feedback ici



