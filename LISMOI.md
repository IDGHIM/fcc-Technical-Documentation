# 📝 fcc-Technical-Documentation ( Version française ) 

🔗 **Site en ligne** : [https://idghim.github.io/fcc-Technical-Documentation/](https://idghim.github.io/fcc-Technical-Documentation/)

> ✨ *Sur ce site, j’ai apporté quelques modifications aux consignes afin d’obtenir un résultat qui me plaît personnellement et qui correspond à mon style.*

---

## 🎯 Objectif du projet

Le but de ce projet est de créer une **page de documentation technique** servant de guide ou de référence sur un sujet de votre choix.

> 💡 Inspiré de :  
[Exemple de documentation technique](https://technical-documentation-page.freecodecamp.rocks)  
⚠️ *Ne pas copier le projet de démonstration.*

---

## 📌 Spécifications du projet

- [x] La page doit contenir un élément `<main>` avec l’identifiant `main-doc`, qui contient le contenu principal.
- [x] À l’intérieur de `#main-doc`, il doit y avoir au moins cinq éléments `<section>` avec la classe `main-section`.
- [x] Le **premier élément** de chaque `.main-section` doit être un élément `header` contenant du texte décrivant la section.
- [x] Chaque `.main-section` doit avoir un identifiant `id` correspondant au texte du `header` (les espaces remplacés par des underscores `_`).
- [x] Les sections doivent contenir **au total** au moins :
  - 10 éléments `<p>`
  - 5 éléments `<code>`
  - 5 éléments `<li>`
- [x] Il doit y avoir un élément `<nav>` avec l’identifiant `navbar`.
- [x] Ce `navbar` doit contenir :
  - Un seul `header` décrivant le sujet de la documentation
  - Des liens `<a>` avec la classe `nav-link`, un pour chaque section `.main-section`
- [x] Le `header` du `navbar` doit précéder tous les liens.
- [x] Chaque lien `.nav-link` doit pointer vers une section correspondante de `#main-doc`.
- [x] Sur les écrans larges (ordinateurs), le `#navbar` doit apparaître à gauche de l’écran et rester visible.
- [x] Le projet doit utiliser au moins une **media query** pour l’adaptabilité.

> ⚠️ **Important** : N’oubliez pas d’inclure le fichier CSS dans le HTML :  
> `<link rel="stylesheet" href="styles.css">`

---

## ✅ Liste de vérification des tests

1. Un élément `<main>` avec l’id `main-doc` est présent.
2. Il y a **au moins cinq** éléments `<section>` avec la classe `main-section`.
3. Tous les éléments `.main-section` sont bien des balises `<section>`.
4. Les éléments `.main-section` sont bien des descendants de `#main-doc`.
5. Le premier enfant de chaque `.main-section` est un élément `header`.
6. Aucun `header` ne doit être vide.
7. Chaque `.main-section` a un identifiant `id`.
8. L’identifiant doit correspondre au texte du `header` (avec des underscores `_` à la place des espaces).
9. Il y a au total **au moins 10** éléments `<p>` dans les `.main-section`.
10. Il y a **au moins 5** éléments `<code>` dans les `.main-section`.
11. Il y a **au moins 5** éléments `<li>` dans les `.main-section`.
12. Un élément `<nav>` avec `id="navbar"` est présent.
13. Ce `navbar` contient exactement **un seul** `header`.
14. Il y a au moins un élément `<a>` avec la classe `nav-link`.
15. Tous les `.nav-link` sont des balises `<a>`.
16. Tous les `.nav-link` sont dans `#navbar`.
17. Le nombre de `.nav-link` est égal au nombre de `.main-section`.
18. Le `header` du `navbar` est avant tous les liens dans la structure HTML.
19. Chaque `.nav-link` contient un texte qui correspond au `header` de la section liée.
20. Chaque `.nav-link` a un attribut `href` qui pointe vers l’`id` de la section correspondante.
21. Le `#navbar` reste toujours affiché à gauche de la fenêtre.
22. Le projet utilise **au moins une media query**.

---

## 🖼️ Contexte du projet

Ce projet fait partie des **projets obligatoires** pour obtenir la **certification Responsive Web Design** sur [freeCodeCamp](https://www.freecodecamp.org/).  
Il m’a permis de développer mes compétences dans :

- L’organisation et la hiérarchie du contenu HTML
- La navigation fluide entre les sections
- L’utilisation de Flexbox ou Grid pour la mise en page
- L’adaptation de la mise en page aux différents formats d’écran
- La structuration d’une documentation technique claire et accessible

---

## 📫 Me contacter

- GitHub : [@idghim](https://github.com/idghim)  
- freeCodeCamp : [Mon profil](https://www.freecodecamp.org/idghim)

---

⭐ *Merci pour votre visite ! N'hésitez pas à ⭐ le dépôt si vous avez trouvé ce projet utile ou intéressant.*
