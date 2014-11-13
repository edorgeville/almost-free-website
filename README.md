# Almost free website  

## Comment avoir votre tout petit site en ligne pour ~15$/an  

N.B. Remplacer tous les endroits où est inscrit ```dogeville.me``` par votre nom de domaine.

### Création des comptes

- Créer un compte Github : [https://github.com/join](https://github.com/join)
- Créer un compte Cloudflare : [https://www.cloudflare.com/sign-up](https://www.cloudflare.com/sign-up)
- Acheter ou transférer votre nom de domaine chez [iwantmyname](http://iwantmyname.com) (ou tout autre registrar)

### Setup du site

#### Sur Github :  
- Créer un repository nommé suivant la structure suivante : ```th3m4ri0.github.io``` (remplacer ```th3m4ri0``` par votre pseudo)
- Ajouter le contenu de votre site au repository :
![5](images/5.png)
- Ajouter un fichier nommé CNAME avec le contenu suivant :
```dogeville.me``` (ou votre nom de domaine)   
![6](images/6.png)

#### Sur Cloudflare :  
- Ajouter l'adresse de votre nom de domaine :
![1](images/1.png)
- Laisser le scan s'effectuer :
![2](images/2.png)  
![3](images/3.png)
- Puis entrez la ligne suivante dans les DNS records :
![7](images/7.png)
![8](images/8.png)
(remplacez ```th3m4ri0``` par votre pseudo github)
- Sauvegardez les entrées.
- Copiez les deux lignes en haut à droite de la page :
![9](images/9.png)

#### Sur iwantmyname (ou votre fournisseur de nom de domaine)
- Rendez-vous sur la page d'information de votre domaine (généralement dans [http://iwantmyname.com/dashboard/domains/](http://iwantmyname.com/dashboard/domains/)) et cliquez sur Update nameservers :
![10](images/10.png)
- Puis collez les lignes copiées 2 étapes plus haut :
![11](images/11.png)
- Sauvegardez
- Ouvrez votre navigateur à l'adresse de votre domaine ! Vous devriez voir votre site apparaitre.