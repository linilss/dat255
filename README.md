# dat255
Repo for course DAT255 Software Engineering Project

---

För att ladda ner eller clone:a repot, 
kopiera följande länk: 


https://github.com/linilss/dat255.git

Öppna ett terminalfönster, skriv `ls` för att lista 
alla filer och mappar där du står. Navigera till en 
lämplig mapp genom att skriva `cd <mappnamn>`.

Förutsatt att git finns installerat på din dator 
skriver du in följande kommando i terminalen:

```
git clone https://github.com/linilss/dat255.git
```

För att hämta all info om repot, inkl alla existerande 
remote branches, kör: 

```
git branch -r | grep -v '\->' | while read remote; do git branch --track "${remote#origin/}" "$remote"; done
git fetch --all
git pull --all
```

För att se vilken branch du står i och status för den, kör:

```
git status
```

För att växla till en existerande branch `branchnamn`:
```
git checkout branchnamn
```

För att skapa en ny branch `branchnamn` och gå till den, kör:

```
git checkout -b branchnamn
```

För att pusha till branchen du står i vid namn `branchnamn`, kör:
```
git add . //lägger till alla ändrade filer till commit
git commit -m '<text som beskriver ändringar>'
git pull
git push origin branchnamn
```

För att pusha ändringar i en branch (`branchNamn`) till branchen ovanför (`parentBranch`):
```
git add .
git commit -m '<text som beskriver ändringar gjorda>'
git merge parentBranch
```
Om du inte får något merge conflict:
```
git checkout parentBranch
git merge branchNamn
git pull
git push
```
