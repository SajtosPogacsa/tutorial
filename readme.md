Git Segédlet

-VSC terminál nyitása, git bash    # Ha nincs ilyen, akkor git scm telepítése
-mkdir tutorial                    # Munkakönyvtár létrehozása (make directory)
-cd /tutorial                      # Beléptünk a mappába
-echo "git segédlet" >> readme.md  # Readme file létrehozása, "git segédlet" szöveggel
-ls                                # Mappa tartalmát listázzuk
-git init                          # Könyvtár inicializálása git mappává
-git config --global --list        # Globális beállítások listázása
-git status                        # Munkamenet jelenlegi állapotának lekérdezése
-git add readme.md                 # readme.md fájl stage-elése
-git commit -m "first commit"      # Stage-elt változások commit-elése "first commit" üzenettel
-git remote add origin [link]      # Összekapcsolás origin néven a címben lévő repoval
-git remote -v                     # Távoli repo ellenőrzése
-git push -u origin master         # Feltöltés, -u ha először töltünk föl
-git pull                          # Letöltés

-git remote remove origin          # Origin törlése