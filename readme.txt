# The application consists of the Rest API backend project and a reactJs frontend project.
# The backend project is built with Java SpringBoot RestControllers
# A docker image of the backend project is kept in docker hub kevin812/coin-app:latest
# Both front and backend projects are in the github repository - https://github.com/ko812/coin-app.git & https://github.com/ko812/coin-react.git
# Both are public repositories
# Below are the steps to run the backend project and frontend projects.

# WHAT ARE REQUIRED?
# 1. git installed on your machine and added to the PATH environment variable. If not, visit the github links above to download the codes as zip.
# 2. To run the docker image of the backend project, docker desktop (version 27.0.3+) needs to be installed on your machine.
# 3. If docker is not on your machine, maven (version 3.8.6+) should be installed, so that the backend project can be built from the source code.
# 4. To run the frontend project, npm (version 10.8+) and node.js (version 20.8+) are required

# Backend Project Setup (Java SpringBoot Rest API)
# 1. To run and start the backend project, simply run command: docker run -p 8080:8080 kevin812/coin-app:latest
# Alternative,
# 1. Using git, run command: git clone https://github.com/ko812/coin-app.git Otherwise, download source code from https://github.com/ko812/coin-app, then unzip code.
# 2. cd coin-app 
#    This goes to the coin-app directory from the git clone. See that the Dockerfile (Challenge 2) is located here.
# 3. Run command: mvn clean install
#	 This will clear anything in the target folder and then build the jar file in the target folder.
# 4. cd target
#    This goes to the target folder.
# 5. See that the jar file, minimum-coin-1.0.0.jar, is built. Run command: java -jar minimum-coin-1.0.0.jar 
#	 This will run and start the backend project

# Frontend Project Setup (ReactJS)
# 1. Using git, run command: git clone https://github.com/ko812/coin-react.git Otherwise, download source code from https://github.com/ko812/coin-react, then unzip code.
# 2. cd coin-react
# 	 This goes to the coin-react directory from the git clone
# 3. Run command: npm install
#	 This downloads dependencies of the project into the folder node_modules
# 4. Run command: npm start
#	 This starts the reactjs project. Open a browser and enter: localhost:3000 to start the minimum coin app.

# The project is ready.
