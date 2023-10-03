## Install and Run the project in local

`npm i`

`node index.js`

## Public EndPoints

signIn API - https://easy-generator-backend.vercel.app/user/login

cURL -> `curl --location --request POST 'https://easy-generator-backend.vercel.app/user/login' \
--header 'Content-Type: application/x-www-form-urlencoded' \
--data-urlencode 'email=shubham@gmail.com' \
--data-urlencode 'password=123456'`

signUp API - https://easy-generator-backend.vercel.app/user/createUser

cURL -> `curl --location --request POST 'https://easy-generator-backend.vercel.app/user/createUser' \
--header 'Content-Type: application/x-www-form-urlencoded' \
--data-urlencode 'email=shubham@gmail.com' \
--data-urlencode 'password=123456' \
--data-urlencode 'name=shubham'`
