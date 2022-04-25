## WEB STACK IMPLEMENTATION (LEMP STACK)
In this project you will implement a similar stack as in [project-one](https://github.com/uzukwujp/Darey.io-Internship/blob/main/project-one.md), but with an alternative Web Server – NGINX, which is also very popular and widely used by many websites in the Internet

### Step 0 – Preparing prerequisites
- You need an AWS account and Ubuntu server provisioned. You can follow step 0 of [project-one](https://github.com/uzukwujp/Darey.io-Internship/blob/main/project-one.md) to achieve that.

- However instead of connecting to the EC2 instance with **Putty** you can use Git Bash. Download and install git bash from this video: [GitBash](https://www.youtube.com/watch?v=qdwWe9COT9k)

- Launch Git Bash and run following command:

  `ssh -i <Your-private-key.pem> ubuntu@<EC2-Public-IP-address>`
  
- You should see something like the screenshot below on your console:

  ![image](https://user-images.githubusercontent.com/52359007/165129115-b9b7fd15-fbf2-45c0-86f5-18bebfc74893.png)
  
 
 
 
### Step 1 – Installing the Nginx Web Server
In [project-one](https://github.com/uzukwujp/Darey.io-Internship/blob/main/project-one.md) we used Apache as our webserver. An alternative is Nginx. Nginx is known for its ability to handle multiple open connections effectively. 

- To Update your Package Repository run the command below:

  `sudo apt update`
  
- To install Nginx run the command below:

  `sudo apt install nginx`

- To verify that nginx was successfully installed and is running as a service in Ubuntu, run:

  `sudo systemctl status nginx`
  
- You should the something like the screenshot below:

  
  
   
