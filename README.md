# AWS-EC2-Labs
<h2>Lab 1</h2>
<img width="1434" alt="EC2 Lab 1-1" src="https://github.com/user-attachments/assets/dcd6d2f1-097f-4e69-a34d-6aea5e5b6d8d"></br>
1 - Creating a VPC to launch our EC2 instance
<img width="1434" alt="EC2 Lab 1-2" src="https://github.com/user-attachments/assets/8b1ce814-4a79-47a4-9acf-b3ad19b1cc0a"></br>
2 - Creating a public subnet to place in the VPC previously created to launch our EC2 instance
<img width="1434" alt="EC2 Lab 1-3" src="https://github.com/user-attachments/assets/830520b0-bd3f-4331-804b-469f2a735488"></br>
3 - Creating internet gateway and attaching to VPC so internet traffic can enter subnet
<img width="1434" alt="EC2 Lab 1-4" src="https://github.com/user-attachments/assets/14713100-3c3c-4c53-b14f-df9003172d8c"></br>
4- Configuring route table to make sure public internet traffic is being sent to the public subnet
<img width="1434" alt="EC2 Lab 1-5" src="https://github.com/user-attachments/assets/80f321e6-781a-41f9-ba59-9454271467bc"></br>
5 - Launching EC2 Instance in the VPC and the public subnet we established 
<img width="1434" alt="EC2 Lab 1-6" src="https://github.com/user-attachments/assets/67b79188-abd6-41cf-a229-ea1b6522c2bf"></br>
6- Successfully connecting to the EC2 instance
<h2>EC2 Instance Bootstrapping</h2>
<img width="1434" alt="ec21" src="https://github.com/user-attachments/assets/f5330ca1-45cb-42ad-bcce-2a1aa7b294b0"></br>
1 - After updating the web server with latest packages we installed apache
<img width="1434" alt="ec22" src="https://github.com/user-attachments/assets/7257532f-ff80-4790-bdd6-7303208e9e88"></br>
2 - Installing zip tool and then unzipping file that will give us access to AWS CLI tool
<img width="1434" alt="ec24" src="https://github.com/user-attachments/assets/1717063e-12cc-4942-b5d2-2579847a98d8"></br>
3 - Launching a second web server and using a bootstrap script pasted in below on the dashboard to do everything that we manually just did on the webserver-01 instance
<img width="1434" alt="ec25" src="https://github.com/user-attachments/assets/2c5fd25d-896e-40a4-8f0a-79e0cf64d267"></br>
4 - checking to ensure that apache was installed and properly running on the instance
