# 🚀 Guide de mise en ligne — Après les mots

## Ce que tu vas faire (vue d'ensemble)

1. Créer un compte GitHub (5 min)
2. Mettre le dossier du site sur GitHub (5 min)
3. Connecter GitHub à Netlify (3 min)
4. Activer l'interface d'administration (2 min)
5. → Ton site est en ligne et tu peux tout modifier !

---

## ÉTAPE 1 — Créer un compte GitHub

GitHub est l'endroit où ton site est stocké. C'est gratuit.

1. Va sur **github.com**
2. Clique **Sign up**
3. Entre ton email, crée un mot de passe, choisis un pseudo (ex: `apreslesmots`)
4. Vérifie ton email et connecte-toi

---

## ÉTAPE 2 — Créer un dépôt et uploader le dossier

1. Une fois connectée sur GitHub, clique le bouton vert **New** (ou **+ > New repository**)
2. Nom du dépôt : `apres-les-mots-site`
3. Laisse tout par défaut, clique **Create repository**
4. Sur la page qui s'ouvre, clique **uploading an existing file**
5. **Glisse-dépose TOUT le contenu du dossier** `apres-les-mots` (pas le dossier lui-même, son contenu)
6. En bas, écris un message ex : "Premier upload" et clique **Commit changes**

✅ Ton site est maintenant sur GitHub !

---

## ÉTAPE 3 — Connecter à Netlify

1. Va sur **netlify.com**
2. Clique **Sign up** → choisis **Sign up with GitHub** (pratique !)
3. Une fois connectée, clique **Add new site > Import an existing project**
4. Clique **GitHub**, autorise l'accès
5. Cherche et sélectionne ton dépôt `apres-les-mots-site`
6. Laisse tout par défaut, clique **Deploy site**

⏳ Attends 1-2 minutes. Netlify te donne une URL du type `random-name.netlify.app`

✅ Ton site est en ligne !

> **Optionnel :** Pour changer l'URL, va dans **Site settings > Domain management** et clique **Options > Edit site name** pour mettre quelque chose comme `apres-les-mots.netlify.app`

---

## ÉTAPE 4 — Activer l'interface d'administration

C'est l'étape la plus importante pour pouvoir modifier le site toi-même.

### 4a — Activer l'Identity service

1. Dans Netlify, va dans **Site settings**
2. Dans le menu gauche, clique **Identity**
3. Clique **Enable Identity**

### 4b — Activer Git Gateway

1. Toujours dans **Identity**, fais défiler jusqu'à **Services**
2. Clique **Enable Git Gateway**

### 4c — T'inviter comme administratrice

1. Toujours dans **Identity**, clique **Invite users**
2. Entre **ton adresse email**
3. Tu vas recevoir un email d'invitation → clique le lien et crée ton mot de passe

### 4d — Tester l'accès

1. Va sur `ton-site.netlify.app/admin`
2. Connecte-toi avec ton email et le mot de passe que tu viens de créer
3. 🎉 Tu as accès à l'interface d'administration !

---

## COMMENT UTILISER L'INTERFACE D'ADMIN

### Écrire ou modifier un article

1. Va sur `ton-site.netlify.app/admin`
2. Clique **📝 Articles du blog**
3. Clique **New Articles du blog** pour un nouvel article
4. Remplis : Titre, Date, Catégorie, Émoji, Extrait, Contenu
5. Clique **Publish** (en haut à droite)
6. ⏳ Attends 1-2 minutes → l'article apparaît sur ton site !

### Modifier le logo

1. Dans l'admin, clique **⚙️ Paramètres du site > 🏠 Général**
2. Clique sur le champ **Logo principal**
3. Clique **Choose an image** ou glisse ton nouveau logo
4. Clique **Save** puis **Publish**

### Modifier les textes du site

1. Dans l'admin, va dans la section correspondante :
   - **💜 Valeurs** pour la section "Qui sommes-nous"
   - **🎯 Champs d'action** pour les 3 actions
   - **📊 Chiffres clés** pour les statistiques
   - **👥 Équipe** pour les membres
   - **🏠 Général** pour le nom, email, slogan
2. Modifie ce que tu veux
3. Clique **Save** puis **Publish**

### Changer un emoji

Les emojis se changent dans le champ texte correspondant — copie-colle simplement le nouvel emoji depuis n'importe quel site (ex: emojipedia.org) ou depuis le clavier emoji de ton téléphone.

### Ajouter une photo d'équipe

1. Dans **👥 Équipe**, trouve le membre concerné
2. Clique sur le champ **Photo**
3. Upload ton image (format carré recommandé, minimum 300×300px)
4. Sauvegarde et publie

---

## EN CAS DE PROBLÈME

**Le site ne se met pas à jour ?**
→ Attends 2-3 minutes, Netlify redéploie automatiquement à chaque modification.

**Je ne peux pas me connecter à /admin ?**
→ Vérifie que tu as bien activé Identity ET Git Gateway (Étape 4).
→ Vérifie que tu as cliqué le lien dans l'email d'invitation.

**L'URL de mon site ?**
→ Elle est dans le tableau de bord Netlify, en haut de la page de ton site.

---

## RÉSUMÉ EN 3 LIGNES

- **Modifier du texte / articles** → `ton-site.netlify.app/admin`
- **Voir le site public** → `ton-site.netlify.app`
- **Mettre en ligne des modifications** → tout se fait depuis l'admin, automatiquement

---

*Guide créé pour Après les mots — Association*
