# Cloud Formation Stacks

Create an empty Githib Repo and within the Repo, create a directory named CF-Templates
Clone this repo into your local directory
Inside your CF template folder Create a CF stack (Infra.yaml) that will create the following resources and deploy it from console:

# Execution steps
* VPC
* Private subnet
* Public subnet
* Route tables (public, private)
* Internet Gateway
* Security Groups
* Ingress rules for the SG groups


Once you can Deploy  successfully, modify the same stack to deploy in a substack fashion. (Nested Stack). You will have a main stack that deploys substacks for each of the resources.



![VPC-designer](https://user-images.githubusercontent.com/9987534/148680087-91d6f5a9-1b0b-43bb-a545-6fa3b5446351.png)
