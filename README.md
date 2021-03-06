# Pika-Clic

Projet de "Pika-Clicker" (CookieClicker-like) maison, qui consiste en un mini-jeu dont le but est de faire un scoring le plus rapidement possible. Le projet s'insère dans le cadre d'une mise en situation de travail en groupe sur un premier objet faisant appel aux technologies web.  
Initiation au developpement en equipe (JS/HTML/CSS) et application de la methodologie SCRUM (dans la mesure du possible).  

# Printscreen : 
![printscreen](/images/prt.png)

# Enonce du projet : 

>Repo BeCode :
>https://github.com/becodeorg/BXL-Lovelace-3.9/tree/master/projects/cookie-clicker

# Membres de la team + pseudo GitHub
- Emilie Bialais : @ebialais
- François Massart : @frmassar
- Jussi Ccoyllo : @JussiCcoyllo
- Corneliu Gaina : @corneliushka
- Julien Ripet : @julienripet

# Timing :

- *Mercredi 6 février* : initialisation du projet, organisation et plannification du travail en groupe.  
- *Jeudi 7 février* : création fichier sass, création structure html, création des premières fonctions : clic, multiclic, fonction bonus Multiplicateur, appels de fonctions, objet pokemon.  
- *Vendredi 8 février* : création de la fonction bonus Booster et bonus Autoclic.  

- *Lundi 11 février* : Abandon des branches nominatives et basculement 100% sur branche "développementMain" = 200% de gain de temps. Correction des bugs des fonctions. Journée principalement consacrée au style : arrière plan pikachu qui pique les yeux, pokeballs bonus et divers indicateurs d'achat et prix.  
- *Mardi 12 février* : commencement du responsive design et diverses améliorations CSS, création fonction "quote" (notifications narratives).  
- *Mercredi 13 février* : peaufinage du projet, corrections bugs, changement bannière et expérience utilisateur (UX).  

# Organisation & Outils

- ProductBacklog : cf. Projects dans **GitHub** / cf. panneau post-it's.  
- Communication : groupe **Ryver** et en présentiel.  
- Issue/Tasks: cf. Issue dans **GitHub** 

- (non utilisé) Schema (**Google draw**): https://docs.google.com/drawings/d/1CoZtnDKK6YqhLOcDaewb_jQaiDhKXC8Qw-J5G5h0r2o/edit?usp=sharing   
- (non utilisé) BreakdownVelocity (avancee projet sur **Google Sheet**) : https://docs.google.com/spreadsheets/d/1qDtbrMbKwJFSQUbTcCKCJgLlsOYBSmTDijXoKjz7QBk/edit?usp=sharing  

# Difficultés et avancements lors du projet en groupe 

- Utilisation de Github à plusieurs, creation d'une branche developpementMain et une branche nominative pour chacun. Cela creait beaucoup de conflits lors du merging. Une tentative avortee consistait d'utiliser le Visual Studio Share Live (extension permettant de collaborer en temps reel sur un meme fichier). La solution se presentait alors : avoir un workflow de type Git Flow, avec une branche hotfix, release, developement et features (et ne pas utiliser les branches nominatives), comme l'avait présenté l'ancien Lovelace Pedro Seromenho lors de son seminaire sur Git Flow. Par manque de temps et besoin d'avancer sur le projet, on a continué tous sur la branche developpementMain (push/pull et resolution de conflits en duo) : la collaboration était plus fluide dès lors.

- Nous avons utilisé SASS et travaillé principalement sur un fichier .scss pour le style, la structure d'indentation et la logique suivait celle du fichier HTML. La page du "Pika-Clic" a été rendue aussi responsive que possible, y compris sur smartphone de toutes les tailles.

- Le travail s'est fait sur un seul fichier .js, avec une separation distincte entre l'objet, les différentes fonctions utilisées et les appels de fonctions. 


# Histoire du jeu

Nous avons combine les sujets tels que le clonage, la rebellion et l'energie renouvelable pour presenter une sorte de dystopie Pokemon.  
En effet, dans le jeu, le joueur va cloner des Pikachu dans son laboratoire afin d'avoir de l'energie gratuite pour acheter des pikacoin et les miner sur le marche.  
Mais se rendant compte de son pouvoir, le joueur va vendre au gouvernements ses Pikachus afin d'agrandir son laboratoire, et par consequent, generer davantage de Pikachus. Car evidemment le joueur a envie de connaitre la fin du jeu, et cela, a traver 15 niveaux de score a difficulte croissante, et une narration d'actualite, par une petite phrase sous le score.  
Car le nombre de Pikachus augmentant exponentiellement, ils ont un impact de plus en plus grand sur le monde et puis l'univers tout entier.   
