# Server Chatroom

Lancer la commande yarn pour installer les dépendances nécessaires au fonctionnement du projet.
- install `yarn`

Lancer la commande yarn start pour lancer le projet. Le chat se lance sur le port 3200.
- start server `yarn start` : http://localhost:3001

Routes :
- `POST http://localhost:3001/login`

    => fournir un objet contenant email et password, par exemple 
    ```
    {
        email: 'walter.white@breakingbad.com',
        password: 'heisenberg'
    },
    {
        email: 'lebron.james@nba.com',
        password: 'number23'
    }
    ```

Identifiants :
- walter.white@breakingbad.com/heisenberg
- lebron.james@nba.com/number23



- `POST http://localhost:3001/forgot`
- `GET http://localhost:3001/theme/{email}`
