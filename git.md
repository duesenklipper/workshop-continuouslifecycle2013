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

#### Zu Branch wechseln
        $ git checkout <branchname>

#### Mergen
        $ git checkout <zielbranch>
        $ git merge [--no-ff] <quellbranch>
        