# my-super-websiteProcess :
wilder@wilder-ThinkPad-T440p:~$ git clone https://github.com/nelly-chieng/my-super-website.git
Clonage dans 'my-super-website'...
remote: Enumerating objects: 6, done.
remote: Counting objects: 100% (6/6), done.
remote: Compressing objects: 100% (4/4), done.
remote: Total 6 (delta 0), reused 0 (delta 0), pack-reused 0
Dépaquetage des objets: 100% (6/6), 1.30 Kio | 331.00 Kio/s, fait.
wilder@wilder-ThinkPad-T440p:~$ git status
fatal: ni ceci ni aucun de ses répertoires parents n'est un dépôt git : .git
wilder@wilder-ThinkPad-T440p:~$ cd my-super-website/
wilder@wilder-ThinkPad-T440p:~/my-super-website$ git status
Sur la branche master
Votre branche est à jour avec 'origin/master'.

Modifications qui ne seront pas validées :
  (utilisez "git add <fichier>..." pour mettre à jour ce qui sera validé)
  (utilisez "git restore <fichier>..." pour annuler les modifications dans le répertoire de travail)
	modifié :         index.html

aucune modification n'a été ajoutée à la validation (utilisez "git add" ou "git commit -a")
wilder@wilder-ThinkPad-T440p:~/my-super-website$ git add index.html
wilder@wilder-ThinkPad-T440p:~/my-super-website$ git status
Sur la branche master
Votre branche est à jour avec 'origin/master'.

Modifications qui seront validées :
  (utilisez "git restore --staged <fichier>..." pour désindexer)
	modifié :         index.html

wilder@wilder-ThinkPad-T440p:~/my-super-website$ git push origin master
Username for 'https://github.com': nelly-chieng
Password for 'https://nelly-chieng@github.com': 
Everything up-to-date
wilder@wilder-ThinkPad-T440p:~/my-super-website$ git commit -m "Title change and H1 added"
[master 5289312] Title change and H1 added
 1 file changed, 14 insertions(+), 1 deletion(-)
wilder@wilder-ThinkPad-T440p:~/my-super-website$ git remote -v
origin	https://github.com/nelly-chieng/my-super-website.git (fetch)
origin	https://github.com/nelly-chieng/my-super-website.git (push)
wilder@wilder-ThinkPad-T440p:~/my-super-website$ git status
Sur la branche master
Votre branche est en avance sur 'origin/master' de 1 commit.
  (utilisez "git push" pour publier vos commits locaux)

rien à valider, la copie de travail est propre
wilder@wilder-ThinkPad-T440p:~/my-super-website$ git push origin master
Username for 'https://github.com': nelly-chieng           
Password for 'https://nelly-chieng@github.com': 
Énumération des objets: 5, fait.
Décompte des objets: 100% (5/5), fait.
Compression par delta en utilisant jusqu'à 4 fils d'exécution
Compression des objets: 100% (3/3), fait.
Écriture des objets: 100% (3/3), 457 octets | 457.00 Kio/s, fait.
Total 3 (delta 0), réutilisés 0 (delta 0)
To https://github.com/nelly-chieng/my-super-website.git
   1be2645..5289312  master -> master
