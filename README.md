# blarktina-Lita-EC2-Instance-Project
## This project documents the process of how I launced an EC2 instance to host the Apache web server for smartshop
### Keypair creation
#### I created a keypair for the EC2 instace, below is the keypair details 

![keypairimage](/keypair1.png)
![keypairimage2](/keypair.png)


### Security group creation
#### I create a security group for the EC2 instace, below is the details of the security group I created

![securityimage](/securitygroup1.png)
![securityimage2](/Securitygroup.png)

### The EC2 instace launced
#### while createing the EC2 instance I Named my EC2 intance, I made use of the VPC that was created for me.The EC2 is seated on Amazonlinux2AMI and the EC2 type is t2.micro. below are the details of the EC2 instance launced

![EC2image](/Ec2.png)
![EC2image1](/amazonlinux2.png)
![EC2image2](/instancetype.png)
![EC2image3](/Ec2launce.png)


### Apache Web Server Installation
#### I Run the following commands on the EC2 instance:

```bash
sudo yum update -y
sudo yum install httpd -y
sudo systemctl start httpd
sudo systemctl enable httpd
below is the details of the Apache webserver installation
```

![Ec2connect](/Ec2connect.png)
![Ec2connect2](/install2.png)
![Ec2connect3](/Installingapache.png)
![Ec2connect4](/Apache.png)








