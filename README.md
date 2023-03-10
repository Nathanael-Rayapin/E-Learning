# E-Learning

La plupart des personnes voulant être formées aujourd’hui préfèrent des formations à distance telles que le E-learning, pour ses nombreux avantages. Elles peuvent se former dans n’importe quel domaine et surtout depuis leur domicile, à condition d’avoir simplement un ordinateur, ou même un smartphone.

![alt Cover](./backend/public/readme/Cover.jpg)

L’objectif est de permettre aux plus grands nombres de participer à des apprentissages portant sur le Leadership et le Management.

## Technologies

![Javascript](https://img.shields.io/badge/JavaScript-323330?style=for-the-badge&logo=javascript&logoColor=F7DF1E)
![Node.js](https://img.shields.io/badge/Node.js-339933?style=for-the-badge&logo=nodedotjs&logoColor=white)
![Express.js](https://img.shields.io/badge/Express.js-000000?style=for-the-badge&logo=express&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-316192?style=for-the-badge&logo=postgresql&logoColor=white)
![Figma](https://img.shields.io/badge/Figma-F24E1E?style=for-the-badge&logo=figma&logoColor=white)
![Trello](https://img.shields.io/badge/Trello-0052CC?style=for-the-badge&logo=trello&logoColor=white)

## Pour commencer

1 - Commencer par Cloner/Forker le projet :
[Cloner un dépôt](https://docs.github.com/en/repositories/creating-and-managing-repositories/cloning-a-repository) /
[Forker un dépôt](https://docs.github.com/en/get-started/quickstart/fork-a-repo)

2 - Lorsque vous êtes sur le projet, installez toutes les dépendances en exécutant depuis le terminal :

```sh
npm install
```

3 - Créer une base de donnée via PostgreSQL et renseigner les informations de la BDD dans un fichier .env que vous créerez à la racine du projet (voir .env.example)

4 - Crée un fichier sqitch.conf à la racine du projet et paramétrer le en y insérant vos informations (voir sqitch.example.conf) :

5 - Déployer sqitch via la commande
```sh
npm resetDB
```

6 - Lancer le serveur via la commande :
```sh
npm run dev
```