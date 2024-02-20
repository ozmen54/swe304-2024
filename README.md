# SWE 304 SOFTWARE DEVELOPMENT PROCESSES (DEVOPS)


## Projects:

<table>
  <header>
    <th>No</th>
    <th>Project Title</th>
    <th>Tasks</th>
    <th>Due Date</th>
    <th>Other</th>
  </header>
  <body>
    <tr>
      <td>1</td>
      <td><b>Publishing a web app on a cloud.</b></td>
      <td> 
        <b>a)</b> Show that you can build a Java app in jar format on your local computer using Maven. <br> 
        <b>b)</b> Upload that jar file using SFTP to AWS cloud (on EC2 instance). <br> 
        <b>c)</b> Set up web server (Nginx, and DB server (MySQL) on the cloud. <br> 
        <b>d)</b> Show that local client (browser on your computer) can access the app GUIs and the app runs on AWS as expected. 
      </td>
      <td>7 March 2024</td>
      <td></td>
    </tr>
    <tr>
      <td>2</td>
      <td><b>Virtualization with Docker-Compose.</b></td>
      <td>
        <b>a)</b> Build the app in jar on your local computer using Gradle.<br> 
        <b>b)</b> Put your app and required components, such as DB, into Docker containers. <br>
        <b>c)</b> Push the container to Docker hub.<br>
        <b>d)</b> Fetch and run your application with its components on AWS cloud.
      </td>
      <td>To be announced</td>
      <td></td>
    </tr>
    <tr>
      <td>3</td>
      <td><b>Declarative publish pipeline using Jenkins.</b></td>
      <td>
        <b>a)</b> Build the app in jar on your local computer using Gradle.<br>
        <b>b)</b> Create a declerative pipeline on Jenkins server that do the following tasks: <br>
          - Build the jar file on GitHub. <br>
          - Push the jar file to Dockerhub <br>
        <b>c)</b> Pull the image from DockerHub to AWS cloud. <br>
        <b>d)</b> Show that your application runs as expected.
      </td>
      <td>To be announced</td>
      <td></td>
    </tr>
  </body>
</table>


## General rules for project grading:
* Groups are allowed 10 minutes to present their work.
* Groups are called to present their work based on a random number announced in the class. 
* One person can be a speaker or members can present stages separately in one session.
* All group members are expected on the board while presenting. Absent members will be penalized according to excuse.
* Group members help each other to hook their computer to the projector quickly.
* Members (and groups) who are not contributed at all, and do not show up at presentation will get 0 (zero) grade.


1. Cloud publishing: Running jar file on AWS Cloud
2. Virtualization: Publishing application on AWS using Docker-Compose
3. Continuous deployment: Deploy pipeline using Jenkins
