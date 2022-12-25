
# OLX CLONE

### Local Set Up
Make a folder.
In the terminal , run the following command.
```
git clone https://github.com/ImAnshuJoshi/olx-clone.git
```
Now go to the root directory of the backend folder or run the following command.
```
cd ./olx-clone/backend
```
Install the dependencies
```
npm Install
```
Make a .env file in the root of backend folder.
```
MONGO=
PORT=
JWT=
CLOUD_NAME=
API_KEY=
API_SECRET=
CLOUDINARY_URL=
```
Now, Run the server
```
npm start
```
The server is now up and running......

Now open new terminal window in the root directory.
Jump to the frontend folder created or run the following command.
```
cd ./olx-clone/frontend
```
Now clone the frontend branch.
```
git clone -b frontend https://github.com/ImAnshuJoshi/olx-clone.git
```
Go to the frontend folder that needs to be interacted.
```
cd ./frontend/olx-clone
```
Install the dependencies
```
npm i
```
Now change the .env.local file to the port that is specified in the PORT in .env of backend.

At last , start the environment.
```
npm run start:local
```

Now the website is ready to use!!!