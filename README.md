
# Github Actions

<em>Github Actions is a plataform to automate developers workflows, beyond CI/CD pipelines. With this,developers can focus on code instead of doing the same repetitive tasks. Whatever happens to the repository is considered an <b>event</b>. And then, automatic <b>actions</b> are executed in the repository. <b>Workflow</b> is the combination of events and actions. It has an easy integration with many different tools.</em>

## Getting Started
##### build the project

    ./gradlew build

##### build Docker image called java-app. Execute from root

    docker build -t java-app .
    
##### push image to repo 

    docker tag java-app demo-app:java-1.0
    
## Syntax
 <li>name (optional)</li>
 <li>on - events that triggers the workflow.</li>
 <li>jobs - executed by the triggers to accomplish the all necessary steps and you can name it.</li>
 <li>steps - activities that compose the jobs to run commands, setup tasks or run an action.</li>
 <li>uses - selects an action.</li>
 <li>run - runs a cmd.</li>