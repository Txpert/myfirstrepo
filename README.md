# myfirstrepo

**Schritt 1: Repository auf GitHub erstellen**

1. **Melde dich bei GitHub an.**

2. **Erstelle ein neues Repository:**

• Klicke oben rechts auf das “+” und wähle **“New repository”** aus.

• Gib dem Repository einen Namen, z. B. git-practice.

• Wähle die Option **“Add a README file”** aus.

• Klicke auf **“Create repository”**.

**Schritt 2: Repository  klonen**

1. **Repository-URL kopieren:**



2. **VSC im Terminal öffnen**

• Öffne Visual Studio Code. code .

**Schritt 3: Änderungen synchronisieren**

1. **Dateien hinzufügen:**

• Erstelle eine neue Datei in VSC, z. B. index.html, und füge einen einfachen HTML-Code hinzu:

<!DOCTYPE html>
<html>
<head>
    <title>GitHub Übung</title>
</head>
<body>
    <h1>Hallo GitHub!</h1>
</body>
</html>
. **Dateien tracken und committen:**

• Gehe im VSC zum **Source Control**-Tab (Git-Symbol in der linken Seitenleiste).

• Du siehst die neue Datei als “Untracked”.

• Klicke auf das +-Symbol neben der Datei, um sie zur Staging Area hinzuzufügen.

• Gib eine Commit-Nachricht ein, z. B. “Add index.html”, und klicke auf das Häkchen (✔) oder drücke Ctrl + Enter, um zu committen.

3. **Änderungen pushen:**

• Klicke auf **Sync Changes** (oben im VSC-Fenster) oder wähle im Command Palette Git: Push.

4. **Änderungen überprüfen:**

• Öffne das Repository auf GitHub, um sicherzustellen, dass die Datei index.html hochgeladen wurde.

**Schritt 4: Erklärung von .gitignore**


**Was ist .gitignore?**


Die .gitignore-Datei enthält eine Liste von Dateien oder Ordnern, die Git ignorieren soll. Sie wird verwendet, um sensible oder unnötige Daten, wie Passwörter, Logs oder temporäre Dateien, nicht ins Repository aufzunehmen.

  

**Beispiele für .gitignore-Einträge:**

1. **Sensible Dateien:**


2. **Log-Dateien:**

3. **Systemdateien:**

• *.DS_Store (MacOS)

• Thumbs.db (Windows)

4. **Node.js-Projekte:**

  

**Erstellen einer .gitignore:**

1. Erstelle in deinem Repository eine neue Datei mit dem Namen .gitignore.

2. Füge folgende Inhalte hinzu:

```
# Logs
*.log

# Betriebssystem-Dateien
*.DS_Store
Thumbs.db

# Ordner, die nicht ins Repo sollen
node_modules/
```


3. **Speichere die Datei und committe sie:**

• Tracke die .gitignore-Datei und committe sie mit einer passenden Nachricht, z. B.:

```
git commit -m "Add .gitignore file"
git push
```

**Schritt 5: Änderungen testen**

1. Erstelle eine Datei namens test.log in deinem Projekt.

2. Öffne den **Source Control**-Tab in VSC.

3. Überprüfe, ob test.log im **Git-Status** nicht angezeigt wird. Dies zeigt, dass .gitignore funktioniert.
