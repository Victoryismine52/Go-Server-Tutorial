# GoLang Server Tutorial
The following is an example of a very simple go microservice used to demonstrate how golang can be used to create a simple webservice. 

For the purpose of this exercise we will be creating a server using **golang** to listen and serve requests on port 8080. This will then be wrapped in a Docker container exposed to port 80 (standard localhost) on your machine. 

During the course of this exercise we will do the following.  

* start by walking you through the setup of a go server and the methodology behind the structure of said server.  
* We will then take said server and wrap it in a **docker container** and run it from the docker image on your host machine.  
* Next we will add in the **Golang** application portions to allow for a user to add themselves to a list of members
* We will then add a Database backend to persist the user list between server start and stop. For the purpose of this exercise we will be using **MongoDB** but you can substitute it with any persistant store.
* Finally we will look at replacing the front end using **Vuejs**

If all of this is new to you then don't worry we'll walk you through each step and the reason behind it. Conversely if your familiar with all of this you can chose to skip to the bottom of this documentation were we talk about running the dockerfile and simply pull the master branch and run the dockerfile. **NEED TO ADD LINK TO BOTTOM CONTENT ABOUT EXECUTING THE DOCKER FILE**

Let's start by talking a bit about how the code is structured in **github (insert hyperlink)**. Github is used for version control and in our case to showcase the different stages of the project. You'll notice in our github repository we have multiple branches each of them showcases a different stage of the application so if your are ever stuck on a piece of this tutorial you can pull the associated branch for comparison and guidance.

# We'll start by looking at the Golang server branch

This branch is where we setup our go servers and all of the request calls for the associated application. This is a great place to start because we've removed all of the application code replacing it with simple console messages allowing you to test and verify the server architecture without feeling lost by the application code
	
	Server tutorial - (add server tutorial)
	
# Next let's look at the docker branch
Docker is a really interesting tool that will help you a lot with your testing and deployment. Though not the same as virtual machines (I learned this the hard way) they act very similar and can be thought of as a sister concept. 

**Add Docker explenation**
	
	docker tutorial - (add docker tutorial)
	
# Next let's look at the Golang app branch
This branch is where we add the application code that returns http files that allow users to add themselves to a members list and then see all associated members of the group. The first thing that you should notice is that all of the server code from the last branch is still here and we are just adding application code. This allows us to have a nice starting point for any additional golang applications you wish to build in the future. 
	
	Golang app tutorial - (add golang tutorial)

# Next let's look at the Mongo branch
Mongo explenation 

	Mongo app tutorial - (add Mongodb tutorial)
	
# Finally we will take a look at the Vue Branch
Vue explenation
	
	Vue tutorial - (add Vue tutorial)
	
