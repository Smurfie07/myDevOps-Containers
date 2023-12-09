# myDevOps-Containers-Client
# Part 1 B
## Part 1: Application and Container Building
In this part, you will build two containers using Docker, one for the server and another for the client.

Client:
●	Choose an appropriate base image from the Official Images list.
●	Create a Dockerfile for the client container with the following specifications:
●	Use a volume named "clientvol" and mount it at "/clientdata" in the container.
●	Install necessary packages and dependencies required for your client application.
●	Write a client application in your preferred language that does the following:
●	Connects to the server and receives the file.
●	Saves the received file in the "/clientdata" directory.
●	Verifies the file's integrity by checking the received checksum.
●	Use Docker Compose to define and run the client container.

