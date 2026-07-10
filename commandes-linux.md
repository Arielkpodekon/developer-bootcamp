# `commandes-linux.md`

## Guide Pratique des Commandes Linux de Base

Ce document rassemble les commandes fondamentales du terminal Linux avec des exemples concrets pour comprendre leur fonctionnement dans le cadre du Jour 3 du bootcamp.

---

### 1. `pwd` (Print Working Directory)
*   **Description :** Affiche le chemin complet du dossier dans lequel tu te trouves actuellement (le dossier de travail).
*   **Exemple :**
    ```bash
    pwd
    # Sortie type : /home/ariel/projets
    ```

### 2. `ls` (List)
*   **Description :** Liste le contenu (fichiers et dossiers) du répertoire courant.
*   **Exemple :**
    ```bash
    ls
    # Pour voir aussi les détails (droits, taille, date) :
    ls -l
    ```

### 3. `cd` (Change Directory)
*   **Description :** Permet de naviguer et de changer de dossier.
*   **Exemples :**
    ```bash
    cd Documents      # Entre dans le dossier "Documents"
    cd ..             # Retourne au dossier parent (en arrière)
    cd ~              # Retourne au dossier personnel (Home)
    ```

### 4. `mkdir` (Make Directory)
*   **Description :** Crée un nouveau dossier (répertoire).
*   **Exemple :**
    ```bash
    mkdir bootcamp-linux
    ```

### 5. `touch`
*   **Description :** Crée un fichier vide (ou met à jour la date de modification d'un fichier existant).
*   **Exemple :**
    ```bash
    touch notes.txt
    ```

### 6. `cp` (Copy)
*   **Description :** Copie un fichier ou un dossier d'un endroit à un autre.
*   **Exemples :**
    ```bash
    cp notes.txt copie-notes.txt
    # Pour copier un dossier entier et son contenu :
    cp -r bootcamp-linux/ sauvegarde-bootcamp/
    ```

### 7. `mv` (Move)
*   **Description :** Déplace un fichier/dossier, ou le renomme si la destination est dans le même dossier.
*   **Exemples :**
    ```bash
    mv notes.txt bootcamp-linux/   # Déplace le fichier dans le dossier
    mv notes.txt script.txt        # Renomme le fichier
    ```

### 8. `rm` (Remove)
*   **Description :** Supprime un fichier ou un dossier. **Attention, cette action est irréversible.**
*   **Exemples :**
    ```bash
    rm script.txt
    # Pour supprimer un dossier et tout son contenu :
    rm -rf bootcamp-linux/
    ```

### 9. `cat` (Concatenate)
*   **Description :** Affiche le contenu complet d'un fichier directement dans le terminal.
*   **Exemple :**
    ```bash
    cat commandes-linux.md
    ```

### 10. `clear`
*   **Description :** Nettoie l'écran du terminal pour y voir plus clair sans effacer l'historique de tes commandes.
*   **Exemple :**
    ```bash
    clear
    ```