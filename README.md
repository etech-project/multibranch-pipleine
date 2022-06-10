# Multibranch-pipleine

### Project9:

1.  Configure a shared library in github to use to build jenkins shared library jobs
    
    Pending investigation 
<br />
    
2.  Configure a jenkins shared library on your single pipeline jenkinsfile you had
    
    Pending investigation 
<br />
3.  why do you need shared library?

    Shared library is where by we can configure one shared library in our repository and point all the Jenkins job for Jenkins to upload the Jenkins file into the pipeline. 
<br />
4.  what is your experience with jenkins multipipeline CI/CD jobs?

    My experience in jenkins multipipeline CI/CD jobs is multibranch pipeline job type lets you define a job where from a single git repository Jenkins will detect multiple branches and create nested jobs when it finds a Jenkinsfile - With a multibranch configurations , jenkins scan a single repository and when ever it finds a Jenkinsfile
    it will automatically runs a job for you.
    
<br />
5.  What is the diference between source code and buildscript(pom.xml)?

Source code is the text file that contains the program in some programming language intended for consumption by humans. However, buildsript(pom.xml) is the program in addition to the configuration items.

6.  What will you do if you get build failure in your jenkins pipeline?

    First, go to the console output, I check the log -- look at failed error. Also, I check that the feature branch or development branch does not have a conditional statement to prevent it from building. or if the blue ocean is installed in my jenkins, I will check the failed build error from my blue ocean console.
<br />
7.  How does your jenkins server uses to communicate with github? (hints: be specific)

    Jenkins server communicates with github through api calls.

    Step 1: Open your dashboard. Click on the Manage Jenkins button on your Jenkins dashboard:
    Step 2: Find plugins option. Click on Manage Plugins:
    Step 3: In the Plugins Page,
    Step 4: Once the plugins have been installed,
<br />
8.  what is qualitygate in sonarqube analysis?

    We use qualitygate to set conditions that a build should meet to be executed.
<br />
9. how do you authenticate to github as a devops engineer?

    Using access token
<br />
10. how do you troubleshoot a slow running application?

    1. Run the “top” command to see CPU usage, swap and zombie processes. Kill zombie processes

    2. Clear the cache 

    3. Delete log files
<br />
11. What architecture will you propose to be use to increase the performance of an application

    Jenkins master and slave - distribute the workload to different servers that still do communicate to each other.
<br />
12. What file do you use to configure non native services in linux?

    The native services are installed using a package manager. 
    
    But the non-native services are defined by the operator in the /etc/systemd/system directory. example will be creating a file and then define the service name inside the file, such as: [service name]

<br />
13. What informations will use configure for your applications to communicate with its database?

    Service Account - user and credentials

<br />
<br />

14. Wat is the difference between a Port and a Pod in k8s?
   Port exposes the Kubernetes service on the specified port within the cluster. Other pods within the cluster can communicate with this server on the specified port. Whereas, a pod is the smallest execution unit in Kubernetes. A pod encapsulates one or more applications. Pods are ephemeral by nature, if a pod (or the node it executes on) fails, Kubernetes can automatically create a new replica of that pod to continue operations.
<br />
15. How is integration test differrent from Mutation test?

Integration testing is the phase in software testing in which individual software modules are combined and tested as a group. Whereas, Mutation testing is used to design new software tests and evaluate the quality of existing software tests.
