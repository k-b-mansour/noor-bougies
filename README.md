# Noor — site vitrine (GitHub Pages)

Site statique pour **Noor**. Version **Cormorant Garamond + Jost**, palette crème / rose / or. Le formulaire de contact envoie les messages via **FormSubmit** vers **kawlabm@gmail.com** (voir section contact ci-dessous).

## Formulaire de contact (FormSubmit)

1. Après le **premier** message envoyé depuis le site, **FormSubmit** envoie un e-mail de **confirmation** sur **kawlabm@gmail.com** : il faut cliquer le lien pour **activer** le formulaire (anti-spam).
2. Les envois suivants arrivent directement dans la boîte mail.
3. Après envoi, la page redirige vers `https://k-b-mansour.github.io/noor-bougies/#contact`. Si votre URL GitHub Pages change, modifiez la valeur de `_next` dans `index.html` (champ caché du formulaire).

## Prérequis

- Un compte [GitHub](https://github.com)
- [Git](https://git-scm.com/downloads) installé sur votre PC (optionnel si vous utilisez l’interface GitHub pour uploader les fichiers)

## Étapes : mettre le site sur GitHub Pages

### 1. Créer un dépôt sur GitHub

1. Sur GitHub : **New repository** (nouveau dépôt).
2. Nom du dépôt : par exemple `noor-bougies` (le nom peut être libre).
3. Public (recommandé pour Pages gratuit sans friction).
4. Créez le dépôt **sans** README si vous allez pousser depuis votre ordinateur.

### 2. Envoyer ce dossier vers GitHub

Dans un terminal, à la racine de ce projet (`site_vitrine_ecommerce`) :

```bash
git init
git add .
git commit -m "Site vitrine Noor"
git branch -M main
git remote add origin https://github.com/VOTRE_USER/VOTRE_REPO.git
git push -u origin main
```

Remplacez `VOTRE_USER` et `VOTRE_REPO` par votre identifiant GitHub et le nom du dépôt.

### 3. Activer GitHub Pages

1. Sur la page du dépôt : **Settings** → **Pages** (dans le menu de gauche).
2. Sous **Build and deployment** :
   - **Source** : **Deploy from a branch**
   - **Branch** : `main` et dossier **`/ (root)`**
3. Enregistrez. Après une ou deux minutes, le site sera disponible à une adresse du type :

`https://VOTRE_USER.github.io/VOTRE_REPO/`

### 4. Contact (e-mail du formulaire)

Le formulaire pointe vers **FormSubmit** (`kawlabm@gmail.com`). Aucune clé API n’est nécessaire sur le site ; pensez à activer le formulaire via le mail de confirmation au premier envoi.

## Fichiers importants

| Fichier | Rôle |
|--------|------|
| `index.html` | Contenu et textes du site |
| `css/style.css` | Couleurs, polices, mise en page |
| `images/logo-noor.jpg` | Logo / étiquette Noor (ressource optionnelle) |
| `images/noor-bougie-theme.png` | Visuel hero (version en ligne [GitHub Pages](https://k-b-mansour.github.io/noor-bougies/)) |
| `images/noor-invitation-sans-texte.png` | Visuel section À propos |
| `images/hero-bougies.jpg` | Ancienne photo d’ambiance (non utilisée par la page actuelle) |

Les autres PNG / JPG dans `images/` peuvent servir de variantes ou de sauvegarde.

## Tester en local

Ouvrez `index.html` dans votre navigateur (double-clic), ou avec un petit serveur local si besoin.

---

*Fait avec gratitude pour un cadeau en retour.*
