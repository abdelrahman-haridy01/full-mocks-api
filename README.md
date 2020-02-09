# Full mocks API's

Best way to get a full fake REST API.
Make a Full fake REST API, MakePOST, PUT, PATCH or DELETE requests, Fake Register and login based on role Api with jwt.

## How to use it?

Clone or download a repo. Then run `npm i` on project path after install all packages run `node server.js`.The app will automatically reload if you change any of the source files.
Use `http://localhost:8000/` for check Defualt API's by [getpostman](https://www.getpostman.com/). Also You can check defualt API's in [collaction_api.json](https://github.com/abdelrahman-haridy01/full-mocks-api/blob/master/ngAbhar.postman_collection.json) path.



## Custom API's

Edit `api.json` as your app requirments. Example
```json
{
    "users": [
        {
          "id": 1,
          "email": "admin@abharworks.com",
          "password": "123456",
          "role": "admin"
        },
        {
          "id": 2,
          "email": "user@abharworks.com",
          "password": "user",
          "role": "user"
        }
    ],
    "notes": [
        {
          "id": 1,
          "title": "What is Lorem Ipsum001",
          "description": "Lorem Ipsum is simply dummy text of the printing and typesetting industry. Lorem Ipsum has been the industry's standard dummy text ever since the 1500s -"
        },
        {
          "id": 2,
          "title": "What is Lorem Ipsum002",
          "description": "Lorem Ipsum is simply dummy text of the printing and typesetting industry. Lorem Ipsum has been the industry's standard dummy text ever since the 1500s - updated"
        }
    ]
}
```

## API's Example

```
POST   /auth/login      --> email, password
POST   /auth/register   --> name, email, password
GET    /notes/1
GET    /users/1/notes
POST   /notes
PUT    /notes/1
PATCH  /notes/1
DELETE /notes/1
```

## Further help


To get more help on the JWT go check out the [JWT](https://jwt.io/).
To get more help on json-server go check out the [json-server README](https://github.com/typicode/json-server/blob/master/README.md).

## Author

Abdelrahman Haridy - [AbharWorks](http://abharworks.com/)

