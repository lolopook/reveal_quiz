# Git quiz

---

#### Qu'est-ce que Git ?

- Un langage de programmation
- Un système de contrôle de version
- Un logiciel de retouche d'image
- Un navigateur web

---

**Réponse :**

Un système de contrôle de version

```bash
git --version
```

Git est un système de contrôle de version décentralisé et open source, largement utilisé pour la gestion des modifications dans les projets de développement logiciel.

---

#### Quelle est la commande pour initialiser un dépôt Git local ?

- `git start`
- `git init`
- `git new`
- `git create`

---

**Réponse :**

```bash
   $ git init
```

La commande `git init` est utilisée pour initialiser un nouveau dépôt Git local dans le répertoire actuel.

---

#### Quelle commande permet de cloner un dépôt distant ?

- `git fetch`
- `git pull`
- `git clone`
- `git remote`

---

**Réponse :**

`git clone`

```bash
git clone [URL]
```

La commande `git clone` est utilisée pour créer une copie locale d'un dépôt distant sur votre machine.

---

#### Quelle commande permet d'ajouter des fichiers ?

- `git stage`
- `git add`
- `git commit`
- `git push`

---

**Réponse :**

`git add`

```bash
git add [file] # ajoute un seul fichier

git add . # tous les fichiers se trouvant dans le dossier

```

La commande `git add` est utilisée pour ajouter des fichiers à la zone de transit (staging area) en vue de les committer.

---

#### Quelle commande permet de valider les modifications (commit) ?

- `git save`
- `git send`
- `git commit`
- `git update`

---

**Réponse :**

`git commit`

```bash
git commit -m "Message de commit"
```

La commande `git commit` est utilisée pour valider les modifications apportées aux fichiers avec un message descriptif.

---

#### Quelle commande permet d'envoyer les commits locaux vers un dépôt distant ?

- `git send`
- `git upload`
- `git push`
- `git publish`

---

**Réponse :**

`git push`

```bash
git push
```

Est utilisée pour envoyer les commits locaux vers un dépôt distant spécifié.

---

#### Quelle commande permet de récupérer les dernières modifications d'un dépôt distant ?

- `git fetch`
- `git download`
- `git pull`
- `git update`

---

**Réponse :**

`git pull`

```bash
git pull
```

La commande `git pull` est utilisée pour récupérer les dernières modifications d'un dépôt distant et les fusionner avec votre branche locale actuelle.

---

#### Quelle commande permet de créer une nouvelle branche ?

- `git newbranch`
- `git create`
- `git branch`
- `git make`

---

**Réponse :**

`git branch`

```bash
git branch new_branch_name
```

La commande `git branch` est utilisée pour créer une nouvelle branche dans votre dépôt local.

---

#### Quelle commande permet de basculer entre les branches ?

- `git switch`
- `git change`
- `git checkout`
- `git move`

---

**Réponse :**

`git checkout`

```bash
git checkout branch_name
```

La commande git checkout est utilisée pour basculer entre les branches dans votre dépôt local.
