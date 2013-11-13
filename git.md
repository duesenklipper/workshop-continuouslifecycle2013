Git-Befehle aus dem Git-Workshop CL2013
=======================================

#### Git-Repo initialisieren:

    $ git init

#### Dateien hinzufügen:

    $ git add <filename>

#### Lokal committen:

    $ git commit -m "<message>"

#### Status:

    $ git status

#### Log anzeigen

    $ git log

#### Verlorene Commits und andere Aktionen wiederfinden
 
    $ git reflog

#### Diff anzeigen
- gegen Index

        $ git diff

- gegen letzten Commit

        $ git diff HEAD

- zwischen Index und HEAD

        $ git diff --staged

#### Änderungen rückgängig machen

        $ git checkout HEAD -- <filename>
        # analog zu svn revert <filename>

#### Branch anlegen
        $ git branch <branchname> [<start-point>]

#### Zu existierendem Branch wechseln
        $ git checkout <branchname>

#### Remote repo clonen
        $ git clone <repo-url>

#### Updates aus remote holen
        $ git fetch <remote-name>
        # z.B. git fetch origin
        # dann mergen mit git merge origin/branchname

