# Day 17 Answers: Docker Project for DevOps Engineers

### You people are doing just amazing in **#90daysofdevops**. Today's challenge is so special because you are going to do a DevOps project with Docker. Are you excited? 😍

# Dockerfile

Docker is a tool that makes it easy to run applications in containers. Containers are like small packages that hold everything an application needs to run. To create these containers, developers use something called a Dockerfile.

A Dockerfile is like a set of instructions for making a container. It tells Docker what base image to use, what commands to run, and what files to include. For example, if you were making a container for a website, the Dockerfile might tell Docker to use an official web server image, copy the files for your website into the container, and start the web server when the container starts.

For more about Dockerfile, visit [here](https://rushikesh-mashidkar.hashnode.dev/dockerfile-docker-compose-swarm-and-volumes).

## Tasks with Answers

**1. Create a Dockerfile for a simple web application (e.g. a Node.js or Python app)**
   - **1. Create a Simple Flask Application**
      - Create a new directory for your project and navigate into it:

      **Answer**

      ![image](https://github.com/RutvikMangukiya/90DaysOfDevOps/blob/day-17-solution/2024/day17/image/Task1mkdir.png)

      - Clone the repository inside this directory:

      **Answer**

      ![image](https://github.com/RutvikMangukiya/90DaysOfDevOps/blob/day-17-solution/2024/day17/image/T2-git-clone.png)


   - **2. Create a Dockerfile**
      - Create a file named `Dockerfile` in the same directory and add the following content:

      **Answer**

      ![image](https://github.com/RutvikMangukiya/90DaysOfDevOps/blob/day-17-solution/2024/day17/image/T3.1-vim-dockerfile.png)

      ![image](https://github.com/RutvikMangukiya/90DaysOfDevOps/blob/day-17-solution/2024/day17/image/T3-New-dockerfile.png)

**2. Build the image using the Dockerfile and run the container**
   - To build the Docker image, run the following command in the directory containing the Dockerfile:

      **Answer**

      ![image](https://github.com/RutvikMangukiya/90DaysOfDevOps/blob/day-17-solution/2024/day17/image/T4-docker-build.png)

   - Run the Container
      - To run the container, use the following command:

      **Answer**

      ![image](https://github.com/RutvikMangukiya/90DaysOfDevOps/blob/day-17-solution/2024/day17/image/T5-docker-run.png)

      - To list running containers, use the following command:

      ![image](https://github.com/RutvikMangukiya/90DaysOfDevOps/blob/day-17-solution/2024/day17/image/T6-docker-ps.png)

**3. Verify that the application is working as expected by accessing it in a web browser**
   - Open your web browser and navigate to `http://localhost:5000`. You should see the output page "Hello Docker!".

      **Answer**

      ![image](https://github.com/RutvikMangukiya/90DaysOfDevOps/blob/day-17-solution/2024/day17/image/T7-output.png)

**4. Push the image to a public or private repository (e.g. Docker Hub)**
   - To push the image to Docker Hub, you need to tag it with your Docker Hub username and repository name, then push it.
   - **1. Tag the Image**

      **Answer**

      ![image](https://github.com/RutvikMangukiya/90DaysOfDevOps/blob/day-17-solution/2024/day17/image/T8-docker-tag.png)

   - **2. Push the Image**

      **Answer**

      ![image](https://github.com/RutvikMangukiya/90DaysOfDevOps/blob/day-17-solution/2024/day17/image/T9-Dcoker-push.png)

   - **3. Check your profile at Docker Hub Webpage**

      **Answer**

      ![image](https://github.com/RutvikMangukiya/90DaysOfDevOps/blob/day-17-solution/2024/day17/image/T10-dockerhub.png)

      ![image](https://github.com/RutvikMangukiya/90DaysOfDevOps/blob/day-17-solution/2024/day17/image/T10-Dockerhub-2.png)



For a reference project, visit [here](https://youtu.be/Tevxhn6Odc8).

If you want to dive further, watch this [bootcamp](https://youtube.com/playlist?list=PLlfy9GnSVerRqYJgVYO0UiExj5byjrW8u).

You can share your learning with everyone over LinkedIn and tag us along. 😃

Happy Learning :)

[Code for Reference](https://raw.githubusercontent.com/Bhavin213/90DaysOfDevOps/master/2024/day17/code.txt)

[LinkedIn](https://www.linkedin.com/in/bhavin-savaliya/)
