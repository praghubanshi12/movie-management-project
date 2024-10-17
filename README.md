# movie-management-project
Simple CRUD application for movie management using PHP and React JS

## For running the backend
Go to server folder, and run the following command :
* php -S localhost:8000

## For running the frontend
Go to client folder, and run these 2 command sequentially :
* npm run build
* npm run start

## API documentation

* **API Link** : http://localhost:8000/movies.php?page=1&limit=15
  * **Description** :
    * This is a GET Request
    * for pagination of movies data, "limit" parameter sets the limit of records to be sent from the api, and "page" defines the page number
    * default values for query parameters for page & limit are 1 & 15 respectively
