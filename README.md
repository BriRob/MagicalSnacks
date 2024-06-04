# MagicalSnacks W10 D2 EOD

## Just imagine eating the most delicious snacks you'll ever dream of...
1. add .env file and port property to use in app.js
    - need something to parse incoming data entries..
    - need general GET route for home
    - popcorn routes
        - get all popcorn
        - make new popcorn post
        - get one popcorn by id
    - candy routes
        - get all candy
        - make new candy post
        - get one candy by id

2. add general error handling middleware for not-found routes and all other errors

3. add routers for popcorn and candy

4. add validation middleware:
    - new popcorn and candy submissions
        - validate that name and description exist
    - searching for snacks that do not exist
