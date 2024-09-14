# ARSW_EXPO_DOCKER

Simple program that aims to explain the functionality of Docker through a Java/React application.

### Prerequisites
Before install and run the project you will need:
1. **Java** (version 17)

2. **Maven**
    - Download Maven from [here](http://maven.apache.org/download.html)
    - Follow the installation instructions [here](http://maven.apache.org/download.html#Installation)

3. **Git**
    - Install Git by following the instructions [here](http://git-scm.com/book/en/v2/Getting-Started-Installing-Git)

4. **Docker**
    - Install Docker by following the instructions [here](https://docs.docker.com/get-docker/).


### Installing

1. **Clone the repository and navigate into the project directory**:
    ```sh
    git clone https://github.com/JuanDavidGarciaPulido/ARSW_EXPO_DOCKER.git

    cd docker-java-react-app

    cd backend
    ```

2. **Compile the project**:
   ```sh
   mvn clean install
   ```

3. **Go back to the main directory**
   ```sh
   cd ..
   ```

3. **Build and run the Docker containers**:
   ```sh
   docker-compose up -d
   ```

## Usage
**Access the web application**:
`http://localhost:3000`

