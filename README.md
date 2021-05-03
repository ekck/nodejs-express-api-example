Dev dependancies:
- Express: npm install express 

Run script
- npm run start

API methods
| method | url |
|-----|------|
|get |/tshirt|
|post |/tshirt/:id|

Api workflow 
- preferably [Postman](https://www.postman.com/) (explorable options available like [Insomnia](https://insomnia.rest/))
- Create JSON POST request  to http://localhost:8080/tshirt/10
        {
            "logo": "💎"
        } 

- Create GET request to  http://localhost:8080/tshirt 