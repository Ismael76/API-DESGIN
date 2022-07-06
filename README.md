# API-DESGIN

### 1. Database: SQL

### 2. Schema

 ![image](https://user-images.githubusercontent.com/73557557/177518765-ebc813a8-891a-475e-840a-34c6f9bcf65c.png)

### 3. Requests

GET requests will be made to retrieve information about people, houses and addresses

POST request to store people, houses and addresses

### 4. Routes

## GET:

   /peoples/:age

   /peoples/?minAge=20&maxAge=65

   /peoples/:capacity

   /houses/?area="E7"&?minAge=20&maxAge=65

   /addresses/:postcode
 
 ## POST:
 
   /peoples
   
   /addresses
   
   
### 5. Handling Requests/Responses

GET requests are made therefore responses returned should be of status code 200 stating the request has been successful, else status code 404 would be shown.

POST requests would either return 404 if unsuccessful or 201 if successful.

The content types of these responses should be JSON.

The content types of the requests should also be JSON.
