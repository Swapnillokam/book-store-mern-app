# build-full-stack-book-store-mern-app
![full-stack-book-store-mern-project](/frontend/src/assets/github-cover.png)

## How to run this project:

### For Frontend 
Follow the below steps to run the project: 
- Firstly clone or unzip the project folder.
* Go to the frontend directory by using the following command ``` cd frontend ```.
* * create a **.env.local** file in the backend root directory as the same level where the **package.json** is located and keep the following environment variables there:
```
>>> Stepup firebase app and configure the environment

VITE_API_KEY="AIzaSyA8zN3BU1FSnn7TLFCyQBWs9eKNtATGGdY"
VITE_AUTH_DOMAIN="book-store-mern-app-71515.firebaseapp.com"
VITE_PROJECT_ID="book-store-mern-app-71515",
VITE_STORAGE_BUCKET="book-store-mern-app-71515.firebasestorage.app",
VITE_MESSAGING_SENDERID="478356420648",
VITE_APP_ID="1:478356420648:web:a2248876b7e923d649dd1d"
```
+ Then run `` npm install `` commend to install node dependencies.
- Finally, to run the project, use ``npm run dev`` command.


### For Backend
Follow the below steps to run the project: 
- Firstly clone or unzip the project folder.
* Go to the backend directory by using the following command ``` cd backend```.
+ Then run `` npm install `` commend to install node dependencies.
* create a **.env** file in the backend root directory as the same level where the **package.json** is located and keep the following environment variables there: 
```
DB_URL = "mongodb+srv://swapnillokam29:eyLr8fg5gFHU3TQs@cluster0.875klfn.mongodb.net/book-store?retryWrites=true&w=majority&appName=Cluster0"
JWT_SECRET_KEY='773596029000a6fb2f8ddc49bb680b78e6b4bf69171b4f762f8b5350a85ec23afcfc4122306609bc5d3963d764c2c1bbe48cb4bced6b465c7261abe1bc0abbca'

Note: Please setup mongodb and change the MongoDB url and set your jwt secret key above.
```

- Finally, to run the project, use ``npm run start:dev`` command.
