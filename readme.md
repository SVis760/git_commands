# Git & GitHub

### Git setup: Download Git.
## Windows
1. Ga naar de Git for [Windows website](https://gitforwindows.org/).
2. Download het installatieprogramma en voer het uit.
3. Volg de installatiewizard en accepteer de standaardinstellingen, tenzij je specifieke wijzigingen wilt aanbrengen.

## MacOS
Open de Terminal-app.
Installeer Git met behulp van [Homebrew](https://brew.sh/):

```sh
brew install git
```

## Linux

```sh
sudo apt-get install git
```

### Git config
1. Open Git Bash door te zoeken naar "Git Bash" in het startmenu.
```sh
git config --global user.name "jouw_gebruikersnaam"
```
2. Stel je gebruikersnaam in met het volgende commando (vervang jouw_gebruikersnaam door je eigen naam):
```sh
git config --global user.email "jouw_email@example.com"
```

### Maak een GitHub account aan.




Ga naar je working directory:
```sh
git pwd    # Ga naar working directory
git cd <directory> # navigeren naar gewenste directory
git mkdir <directory name>     # Maak nieuwe folder aan via commandline of via filemanager
git init    # om een git repo te starten
git status    # om de status van de map te bekijken.
```

Maak een nieuwe file aan in de nieuwe map + opslaan (normaal zoals je zou doen)
en terug naar je git working directory.
```
git add <file>
# of
git add .
git commit -m "Eerste commit"
```
- [ ] Ga naar GitHub en maak een nieuwe repository.
- [ ] Volg de instructies op GitHub om je repository te koppelen aan je lokale repository. Dit omvat het toevoegen van een externe URL met het commando git remote add origin <repository_url>.
- [ ] Duw je lokale wijzigingen naar GitHub met het volgende commando:

```
git remote add origin <repository_url>
git push -u origin master    # --set-upstream (or its shorthand -u)

```


## Pycharm
### Setting up Git in Pycharm
```{bash}
click on VCS > Enable Version Control Integration
Select Git > OK
```
 
 adding Github server
```{Pycharm GUI}
Git > GitHub > Share Project on GitHub
"Share Project on GitHub"
add your GitHub account details to PyCharm yet click on Add Account.
click on Share.
```
 
 
 Pulling down remote changes from GitHub into your local copy of a project in Pycharm
```{pycharm GUI}
Git > Pull
"Pull to Master" 
Click "Pull" button.
view log > Git > Show Git Log
```

## VScode

```

```
