
# Github Actions

<em>Github Actions is a plataform to automate developers workflows, beyond CI/CD pipelines. With this,developers can focus on code instead of doing the same repetitive tasks. Whatever happens to the repository is considered an <b>event</b>. And then, automatic <b>actions</b> are executed in the repository.</em>

## Getting Started
##### build the project

    ./gradlew build

##### build Docker image called java-app. Execute from root

    docker build -t java-app .
    
##### push image to repo 

    docker tag java-app demo-app:java-1.0
    