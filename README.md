##### build the project

    ./gradlew build

##### build Docker image called java-app. Execute from root

    docker build -t java-app .

##### push image to repo

    docker tag java-app demo-app:java-1.0

I expect that the GHA workflow should start running because I am pushing to master
