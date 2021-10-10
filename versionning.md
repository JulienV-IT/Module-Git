# Le versionning


![versionning](https://julienv-it.github.io/Module-Git/img/versionning.png)


Avec le versionning utilisez les commandes pour manipuler votre code et le comparer d'une modification a l'autre tout en les hiérarchisant et créer un historique de chaque modification depuis le départ


C'est très utile pour revenir en arrière après une erreur et ou éventuellement  comparer deux codes fonctionnels


La modification est validée dans un premier temps du côté local avec un **commit**
puis est enregistré sur GitHub avec un **push**


le versionning permet également de mettre en évidence le **workflow** en place :

- nombre de modifications
- rapidité de production
- nombre de collaborations  


**Les Commits**

Le Commit est une sorte de message qui accompagne une modification et la valide dans la copie locale de travail en générant un identifiant unique

    git commit


**Pull**    

Avec le pull, on peut récupérer des modifications distantes

    git pull

_En général on spécifie la branche que l'on veut récupérer_

**Push**    

Le push, cette commande envoie les modifications sur le dépôt distantes

    git push 

_Ici comme le pull on spécifie la branche dans la plupart des cas, attention un push ne passe que si toutes les modifications sont validée_
