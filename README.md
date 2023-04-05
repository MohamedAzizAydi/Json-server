# Create Server By Using Express.js & Json Server

## Deploy `Json-Server` to `Glitch`

> Instructions how to deploy the full fake REST API [json-server](https://github.com/typicode/json-server) to various free hosting sites. Should only be used in development purpose but can act as a simpler database for smaller applications.

- [**Create your database**](#create-your-database)
- [Deploy to **Glitch**](#deploy-to-glitch)
### Create your database

1. Clone this repository to your computer

2 . Change the contents of `db.json` to **your own content** according to the [`json-server example`](https://github.com/typicode/json-server#example) and then `commit` your changes to git locally.

_this example will create `/users` route , each resource will have `id`, `firstName` and `lastName`. `id` will auto increment!_

```json
{
  "users": [
    {
      "firstName": "mohamed aziz",
      "lastName": "aydi",
      "address": "xxx",
      "city": "xxx",
      "country": "tunisia",
      "phone": "01212843661",
      "email": "aydiaziz90@gmail.com",
      "password": "123456",
      "question": "What is your favorite soccer team",
      "answerTheQuestion": "xxxx",
      "photo": "blob:http://localhost:3000/05ad9d7f-48d1-4972-977e-e86e9c25c342",
      "id": 1
    }
  ]
}
```
3. Upload This Folder after your updated into new Repo

---

### Deploy to Glitch

Not tested 100%. Same as with Heroku, will sleep after a while.

1. Register for [Glitch](https://glitch.com/) or go to [Glitch/edit](https://glitch.com/)
2. Click **New Project**
3. Click **Import from GitHub**
4. Paste `https://github.com/MohamedAzizAydi/Json-server.git` into the URL-input and click OK.
5. Wait for it to setup
6. Press **Share**-button to get your URL to live site. It should be something for example like: `https://ar-server-auth.glitch.me/`. And your DB will be at `https://ar-server-auth.glitch.me/users`

----

#### Author Links

👋 Hello, I'm Mohamed Aziz Aydi - uI & Front End Developer


🚀 Follow Me:


- [LinkedIn](https://www.linkedin.com/in/mohamed-aziz-aydi/)
- [Facebook](https://fb.com/mohamed aziz aydi)

---
