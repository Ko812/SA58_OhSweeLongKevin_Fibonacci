# The application consists of a Rest API backend project and a reactJs frontend project.
# The backend project is built with Java SpringBoot RestControllers
# A docker image of the backend project is kept in docker hub kevin812/coin-app:latest
# Both front and backend projects are in the github repository - https://github.com/ko812/SA58_OhSweeLongKevin_Fibonacci.git
# Both are public repositories
# Below are the steps to run the backend project and frontend projects on a local machine.

# CLI TOOLS INVOLVED
# 1. git CLI
# 2. Docker Desktop and Docker CLI (version 27.0.3+)
# 3. Maven (version 3.8.6+)
# 4. npm (version 10.8+) 
# 5. node.js (version 20.8+)

# Backend Project Setup (Java SpringBoot Rest API)
# 1. To run and start the backend project, run command: docker run -p 8080:8080 kevin812/coin-app:latest
# Alternative,
# 1. Using git, run command: git clone https://github.com/ko812/SA58_OhSweeLongKevin_Fibonacci.git. Alternatively, download source code as zip.
# 2. cd backend\coin-app 
# 3. Run command: mvn clean install
# 4. cd target
# 5. See that the jar file, minimum-coin-1.0.0.jar, is built. Run command: java -jar minimum-coin-1.0.0.jar 

# Frontend Project Setup (ReactJS)
# 1. Using git, run command: git clone https://github.com/ko812/coin-react.git Otherwise, download source code from https://github.com/ko812/coin-react, then unzip code.
# 2. cd frontend\coin-react
# 3. Run command: npm install
# 4. Run command: npm start

