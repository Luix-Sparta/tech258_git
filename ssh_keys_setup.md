## Using SSH to Access a Repository on GitHub

1. **Locate and Enter SSH Folder**

   ![img_1.png](images/img_1.png)

2. **Generate SSH Key**: If you haven't already, generate an SSH key pair on your local machine. You can do this by running the following command in your terminal:
   
   ![img_2.png](images/img_2.png)

   This will show the following option where you can name your file

   ![img_3.png](images/img_3.png)

3. **Start SSH Agent and Add SSH Key**: Once you have created the key, the next step is to start the SSH agent and add your SSH private key to it by running the following commands:
   
   ![img_4.png](images/img_4.png)
   
   ![img_5.png](images/img_5.png)

4. **Copy SSH Public Key**: Now copy the SSH Public Key by displaying your SSH public key with the following command:

   ![img_6.png](images/img_6.png)

5. **Add SSH Key to GitHub**: Go to your GitHub repository settings, click "Deploy keys," and then click "Add deploy key." Input the settings and then click "Add key."

## SSH Diagram

![img_7.png](images/img_7.png)