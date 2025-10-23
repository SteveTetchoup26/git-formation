# git-formation
This project is dedicated to learning Git

## Processus de travail

1. Récupération du projet
```bash
    git clone https://github.com/SteveTetchoup26/git-formation.git
    cd git-formation
```

2. Chacun crée sa branche 
```bash
    git branch nom_de_la_branche
```

3. Chacun se met sur sa branche
```bash
    git checkout nom_de_la_branche
```
4. Création des fichiers HTML
    - /pages/about.html
    - /pages/contact.html

// Note: Veuillez copier la navbar et le footer dans vos fichiers HTML avant de commencer  à travailler

```html
    <nav>
        <div class="container">
            <div class="logo">CDWFS</div>
            <ul>
                <li><a href="/" class="nav-link active" data-page="home">Accueil</a></li>
                <li><a href="/pages/about.html" class="nav-link" data-page="about">À Propos</a></li>
                <li><a href="/pages/contact.html" class="nav-link" data-page="contact">Contact</a></li>
            </ul>
        </div>
    </nav>

    <!-- travaillez ici !!!!! -->

    <footer>
        <p>&copy; 202 CDWFS. Tous droits réservés.</p>
    </footer>
```

// Note: Ajoutez aussi le lien vers le fichier common-style dans l'entête de vos pages HTML

```html
    <link rel="stylesheet" href="common-style.css">
```

5. Création des fichiers CSS
    - /style/about.css
    - /style/contact.css

// Note: Veuillez ajouter le lien vers le fichier common-style au début de vos fichiers csss pour pouvoir utiliser les
// styles communs

```css
    @import url("../common-style");
    
```




<!-- A PROPOS-->
j'ai utilise ton code couleur et faire mon propre css dans style/about.css