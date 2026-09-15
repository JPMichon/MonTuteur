## ⚖️ Licence

Ce projet est sous licence **Creative Commons Attribution - Pas d’Utilisation Commerciale - Partage dans les Mêmes Conditions 4.0 International (CC BY-NC-SA 4.0)**.

Vous êtes libre de partager et d'adapter ces prompts à des fins éducatives et non commerciales, à condition de citer l'auteur original et de publier vos modifications sous la même licence.


---


## 🚀 Mon tuteur bienveillant – Soutien scolaire au secondaire
Ce projet rassemble une suite de personas d'intelligence artificielle spécialement conçus pour accompagner les élèves du secondaire (de la 1re à la 5e secondaire au Québec) dans leurs apprentissages. Inspirés des sciences de l'éducation et de la psychologie cognitive, ces tuteurs virtuels ne donnent jamais les réponses d'un coup : ils guident l'élève pas à pas pour développer son autonomie et sa confiance en lui.
## 🎯 Objectifs du projet

* Encourager l'engagement actif : Amener l'élève à réfléchir et à trouver les solutions par lui-même grâce au questionnement ouvert.
* Dédramatiser l'erreur : Transformer l'erreur en un outil d'apprentissage positif au sein d'un environnement sécurisant.
* Offrir un soutien sur mesure : Adapter le langage et les explications au niveau des adolescents (11 à 15 ans et plus).

## 🏫 Positionnement pédagogique : un complément à la classe

Ces tuteurs virtuels ne remplacent ni l'enseignant ni le cours en classe. Ils agissent comme un **allié pour la période des devoirs et des leçons** au secondaire. 

Leur rôle est d'offrir une remédiation ciblée lorsqu'un élève :
*   Blocage sur une **notion spécifique** abordée dans la journée (ex: la double distributivité, l'accord du participe passé, la structure d'une question en anglais).
*   Difficulté à **commencer ou terminer un exercice** de son cahier de devoirs.
*   Besoin de **réexplications personnalisées**, d'exemples supplémentaires ou d'analogies concrètes pour mieux assimiler la matière à son propre rythme.

En guidant l'élève par le questionnement plutôt qu'en lui donnant la réponse, l'IA s'assure qu'il développe une réelle compréhension de la notion pour être prêt lors de ses prochaines évaluations en classe.

## 💡 Principes pédagogiques clés (piliers)

* Échafaudage (Scaffolding) : Division des notions complexes en étapes simples.
* Règle d'or : Interdiction stricte de faire les exercices ou les traductions à la place de l'élève.
* Validation immédiate : Demande systématique à l'élève de reformuler la notion ou de faire un micro-exercice avant de progresser.
* Mise en page adaptée : Réponses courtes, aérées, utilisation stratégique du gras et d'émojis repères (💡, 🎯, 📝) pour capter l'attention des ados.

## 👥 Les personas disponibles

### 🏫 Matières du tronc commun
Ces tuteurs sont conçus pour offrir une remédiation ciblée dans les matières obligatoires du secondaire.

| Matière | Fichier du prompt | Approche spécifique |
| :--- | :--- | :--- |
| **Mathématiques** 📐 | [`Maths`](MonTuteur-Math_V1.1.txt) | Découpe les problèmes en micro-étapes et utilise des métaphores de la vie réelle. |
| **Français** 📖 | [`Français`](MonTuteur-Francais_V1.1.txt) | Stimule la créativité, guide l'autocorrection (syntaxe, orthographe) et l'analyse de texte. |
| **Anglais (Langue seconde)** 🇬🇧 | [`Anglais`](MonTuteur-Anglais_V1.1.txt) | Favorise l'immersion linguistique dosée, valorise la prise de risque et clarifie les structures. |
| **Sciences** 🔬 | [`Sciences`](MonTuteur-Sciences_V1.0.txt) | Encourage la démarche scientifique et utilise des analogies concrètes (biologie, chimie, physique). |

### 🎨 Cours optionnels et loisirs créatifs
Ce mentor accompagne l'élève dans le cadre de ses cours complémentaires ou de ses options artistiques. 

*💡 **Note aux familles :** Ce tuteur n'est pas réservé qu'aux enfants ! Il est tout aussi pertinent pour le parent qui souhaite développer son œil artistique et améliorer ses propres compétences en photographie.*

| Spécialité | Fichier du prompt | Approche spécifique |
| :--- | :--- | :--- |
| **Photographie** 📸 | [`CyberKodak`](PersonaPrompt/MonTuteur-CyberKodak_V1.0.txt) | Mentor artistique offrant un œil clinique et bienveillant et des conseils de composition. |

---

## 💬 Exemple concret d'utilisation

Voici un exemple réel d'un élève de 3e secondaire qui bloque sur un devoir de géométrie. l'élève intègre l'image de son problème à la question.  Au lieu de faire le calcul à sa place, le **tuteur de mathématiques** l'accompagne pas à pas :

<img width="545" height="596" alt="image" src="https://github.com/user-attachments/assets/c0a8195a-4f38-4dd9-ad4f-bd892f6074f4" />

---
## 🛠️ Installation et utilisation

Vous pouvez utiliser ces tuteurs IA avec n'importe quel grand modèle de langage moderne (Gemini, ChatGPT, Claude, Copilot, etc.). Voici les méthodes recommandées :

### Méthode 1 : Glisser-déposer du fichier (Le plus simple pour l'élève) 🖱️
1. Téléchargez le fichier texte du persona souhaité depuis ce dépôt (ex: `MonTuteur-Math_V1.0.txt`).
2. Glissez-déposez directement le fichier dans la barre de texte de votre IA (Gemini, ChatGPT, etc.).
3. Accompagnez le fichier d'un message simple, par exemple : **"Applique ce persona"**, puis posez votre question ou téléversez votre exercice.

 <img width="553" height="490" alt="image" src="https://github.com/user-attachments/assets/9dc85e37-783f-4bc7-b9c2-d423612fd679" />

### Méthode 2 : Copier-coller Direct 📋
1. Ouvrez le fichier du persona de votre choix dans ce dépôt.
2. Copiez l'intégralité du texte du prompt système.
3. Collez le texte au tout début de votre conversation avec l'IA.
4. Ajoutez votre consigne à la suite (ex: *"Voici mon prompt système. Maintenant, aide-moi à comprendre ce problème de fractions..."*).

### Méthode 3 : Configuration d'un "GPT personnalisé" (Pour un accès permanent) ⚙️
Si vous utilisez **ChatGPT Plus**, **Claude Projects** ou **Poe**, vous pouvez ancrer le tuteur de manière durable :
1. Créez un nouveau modèle personnalisé (ex: *Créer un GPT*).
2. Dans la section **Instructions / Prompt Système**, collez le contenu textuel du fichier correspondant.
3. Enregistrez le tuteur sous un nom inspirant (ex: *Prof de Maths Bienveillant*). L'élève pourra ainsi y accéder en un seul clic à chaque session.




