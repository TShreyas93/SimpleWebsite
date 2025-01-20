![image](https://github.com/user-attachments/assets/ea0d951e-6282-4586-adf3-10886f9e7d26)


### **About this project:**
1. A code created using below with help of ChatGPT
    i.  API: Jakarta Servlet-based application.
   ii.  Runtime: Jetty-hosted Jakarta Servlet application.
   iii. Overall ecosystem: Jakarta EE application.

2. This code is saved in repository.
3. Maven will package this jar file in Github runner when we manually trigger the Github workflow.
4. It contains a github action that has workflow dispath configured along with Github Secrets containing the EC2 secrets like hostname, secret key and Users that is needed to connect to EC2 instance to scp the build jar file.
5. The workflow will then run this package in EC2 and it is configured to run on port 8080.
6. Accessing the EC2 DNS URL along with port 8080 from the browser will give the RESULT shown in image confirming the whole project was successful.

  ### **PENDING ACTIONS:**

   1. Check further on how to create a static DNS name for EC2 instance either via Elastic IP assigning { NOT RECOMMENDED } or by assigning ALBs.
