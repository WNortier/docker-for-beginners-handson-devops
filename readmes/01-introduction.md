<a name="Back_To_Top"></a> Top

---

- ### [Introduction](#Introduction)
- ### [Docker Overview](#Docker_Overview)

---

## <a name="Introduction"></a>Introduction

In this course we first try to understand what containers are what docker is and why you might need it and what it can do for you.

![what-is-typescript](images/intro/01.png)

- We will see how to run a docker container

- How to Build Your Own Docker image.

- We will see networking in Docker and how to use Docker compose

- What Docker registry is and how to deploy your own private registry

> ### We then look at some of these concepts in depth and we try to understand how a docker really works under the hood.

- We look at Docker for Windows and Mac

- Finally, getting a basic introduction to container orchestration tools like Docker Swarm and Kubernetes.

---

- [Top](#Back_To_Top)

---

## <a name="Docker_Overview"></a>Docker Overview

Lets say we're developing this application stack

![what-is-typescript](images/intro/02.png)

### Problems when working without Docker

- We had a lot of issues developing this application stack with all these different components. First of all their compatibility with the underlying OS was an issue we had to ensure that all these different services were compatible with the version of OS we were planning to use. There have been times when certain version of these services were not compatible with the OS and we have had to go back and look at different OS that was compatible with all of these different services. Secondly we had to check the compatibility between these services and the libraries and dependencies on the OS.

- Secondly we had to check the compatibility between these services and the libraries and dependencies on the OS. We've had issues where one service requires one version of a dependent library whereas another service requires another version. The architecture of our application changed over time.

- We've had to upgrade to newer versions of these components or change the database etc. And every time something changed we had to go through the same process of checking compatibility between these various components and the underlying infrastructure.

- Every time we had a new developer on board we found it really difficult to set up a new environment. The new developers had to follow a large set of instructions and run hundreds of commands to finally set up their environment. We had to make sure they were using the right operating system the right versions of each of these components and each developer had to set all that up by himself.

---

> ### All of this made our life in developing building and shipping the application really difficult. So I needed something that could help us with the compatibility issue and something that will allow us to modify or change these components without affecting the other components and even modify the underlying operating systems as required.

---

### Solution: Docker

And that search landed me on Docker. With Docker I was able to run each component in a separate container with its own dependencies and its own libraries all on the same VM and the OS but within separate environments or containers we just had to build the docker configuration once and all our developers could now get started with a simple `Docker run` command irrespective of what the underlying operating system they run.

![what-is-typescript](images/intro/03.png)

---

#### So what are containers?

Containers are completely isolated environments. As in they can have their own processes or services their own network interfaces their own mounts just like virtual machines except they all share the same OS kernel.

![what-is-typescript](images/intro/04.png)

It's also important to note that containers are not new with Docker containers have existed for about 10 years now and some of the different types of containers are LXC, LXD, LXCFS etc.

Docker utilizes LXC containers setting up these container environments is hard as they are very low level and that is where Docker offers a high level tool with several powerful functionalities making it really easy for end users like us to understand how Docker works.

---

- [Top](#Back_To_Top)

---

- ### [Working with Props and Types for Props](#Working_with_Props_and_Types_for_Props)

## <a name="Working_with_Props_and_Types_for_Props"></a>Working with Props and Types for Props

---

- [Top](#Back_To_Top)

---

- ### [Getting User Input with "refs"](#Getting_User_Input_with_"refs")

## <a name="Getting*User_Input_with*"refs""></a>Getting User Input with "refs"

---

- [Top](#Back_To_Top)

---

- ### [Cross-Component Communication](#Cross-Component_Communication)

## <a name="Cross-Component_Communication"></a>Cross-Component Communication

---

- [Top](#Back_To_Top)

---

- ### [Working with State and Types](#Working_with_State_and_Types)

## <a name="Working_with_State_and_Types"></a>Working with State and Types

---

- [Top](#Back_To_Top)

---

- ### [Managing State better](#Managing_State_better)

## <a name="Managing_State_better"></a>Managing State better

---

- [Top](#Back_To_Top)

---

---

- ### [More Props & State Work](#More_Props_&_State_Work)

## <a name="More_Props_&_State_Work"></a>More Props & State Work

---

- [Top](#Back_To_Top)

---

- ### [Adding Styling](#Adding_Styling)

## <a name="Adding_Styling"></a>Adding Styling

---

- [Top](#Back_To_Top)

---

- ### [Types for other React Features (Redux or Routing)](<#Types_for_other_React_Features_(Redux_or_Routing)>)

## <a name="Types_for_other_React_Features_(Redux_or_Routing)"></a>Types for other React Features (Redux or Routing)

- ### [Top](#Back_To_Top)
