# CS55_FinalProject
Final Project for CS55-Security and Privacy
---- 
For our CS55 Final Project, we secured data in transit using PKI. To do this, we used the following approach:

1. Create a VPC
2. Create public and private subnets
3. Create a routetable
4. Create an internet gateway
5. Connect your subnets to the VPC, routetable, and internet gateway, such that the public subnet can be accessed from the internet, and the private subnet can be accessed through the public subnet
6. Create a server ec2 instance and 2 client instances
7. Connect the server to the public subnet, and the clients to the private one
8. Create a security group for the server and one for the clients, and attach them to their respective instances
9. SSH into the server and create a root CA, as well certificates and keys for the server and clients. Sign certificates.
10. Test pinging and curl to ensure secure transfer of information using HTTPS

To find a detailed guide on how to implement this project, click [here](https://github.com/ishanvprasad/CS55_FinalProject/wiki/Project-Implementation)
