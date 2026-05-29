# Noor — site vitrine (GitHub Pages)

Site statique simple pour présenter **Noor, bougies décoratives**. Hébergement gratuit possible avec **GitHub Pages**.

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

### 4. Personnaliser le contact

Ouvrez `index.html` et modifiez le lien du bouton « Contact à personnaliser » :

- E-mail : `href="mailto:son-email@exemple.com"`
- Instagram : `href="https://instagram.com/son_compte"`

## Fichiers importants

| Fichier | Rôle |
|--------|------|
| `index.html` | Contenu et textes du site |
| `css/style.css` | Couleurs, polices, mise en page |
| `images/logo-noor.jpg` | Logo / étiquette Noor |
| `images/hero-bougies.jpg` | Grande photo d’ambiance |

Les fichiers `Média (1).jpg` et `Média (2).jpg` à la racine peuvent être conservés comme sauvegarde ; le site utilise les copies dans `images/`.

## Tester en local

Ouvrez `index.html` dans votre navigateur (double-clic), ou avec un petit serveur local si besoin.

---

*Fait avec gratitude pour un cadeau en retour.*
