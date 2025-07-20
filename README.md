 # Ensure required packages are installed
Install react, react-dom, react-scripts, axios
Use `RUN npm install react react-dom react-scripts axios`

# You can build frontend and backend separately by using docker build command. Also you can also use docker-compose command to buuild and run both rontend and backend with the databbase together. 
# Note: We use postgress database 

# To build frontend, kindly use
`docker build . -t vacantion-frontend:latest ` 
You must run this command where the Dockerfile is located

# To push this to docker hub, we need to tag our image
`docker build . -t wiskky/vacantion-frontend:latest`
You can check your image by running `docker images`

![]()

Note wiskky is my docker hub username, change it to your own docker hub username.
Then run `docker push wiskky/vacantion-frontend:latest`
