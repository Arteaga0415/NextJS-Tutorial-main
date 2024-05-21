## Next.js App for flexmate aplication

# To get started

* Create a vercel postgres DB
* Copy the .env.local secrets to the .env file
* Use open ssl to create a AUTH_SECRET to protect cookies and asign a AUTH_URL to the correct URl (ex: AUTH_URL=http://localhost:3000/api/auth)
* Use the command below to create the auth secret
``` openssl rand -base64 32 ```

