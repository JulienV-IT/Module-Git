# Le versionning


![versionning](https://julienv-it.github.io/Module-Git/img/versionning.png)


Avec le versionning utilisez les commandes pour manipuler votre code et le comparer d'une modificiation a l'autre tout en les hiearchisants et créer un historique de chaques modificiation depuis le départ


C'est trés utile pour revenir en arriere apres une erreur et ou éventuelellement  comparer deux codes fonctionnels


La modification est validée dans un premier temps du coté local avec un **commit**
puis est enregristrer sur github avec un **push**


le versionning permet également de mettre en évidence le **workflow** en place:

- nombre de modification
- rapidité de production
- nombre de collaboration  


**Les Commits**

Le Commit sont une sorte de message qui accompagne une modification et la valide dans la copie local de travail en générant un idenfiant unique

    git commit


**Pull**    

Avec le pull, on peut récupérer des modifications distantes

    git pull

_En général on spécifie la branche que l'on veux récupérer_

**Push**    

Le push, cette commande envoie les modifications sur le dépôt distantes

    git push 

_Ici comme le pull on spécifie la branche dans la plupart des cas, attention un push ne passe que si toutes les modifications sont validée_
