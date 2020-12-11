## Comment écrire un commit sur plusieurs lignes:

Au lieu d'écrire le traditionel `git commit -m "contenu"` où le `git commit -am "contenu"` on écris: `git commit` ce qui va nous diriger vers un éditeur du texte (Dans mon cas c'est Gnu Nano, si vous etes sur linux ca sera probablement le meme. Mais il en existe plusieurs notament le Vim.)

- <img src="assets/img/5.png">

    - On écris le titre du commit sur la premiere ligne
    - Le contenu sur la seconde
    - Et la raison sur la troisième
    
    <img src="assets/img/6.png">

On enregistre le message avec un `CTRL+o` tapez enter pour confirmer le nom du fichier a écrire puis un `CTRL+x` pour sortir (les commandes Nano peuvent différer de celles de Vim. En fonction de votre éditeur vous devez cherchez celles qui correspondent). On vois les changement qui ont été fais.

<img src="assets/img/7.png">

Un coup de `git logg` pour checker:

<img src="assets/img/8.png">

Et un petit check sur les commits du repo pour voir comment ca se présente:

<img src="assets/img/9.png">

<img src="https://c.tenor.com/NWqisN5ga_MAAAAC/voila-iron-man.gif">

↪ [Previous](SenondPage.md)
↪ [Next](FourthPage.md)

