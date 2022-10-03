 # Part 1
 ## Creating a VPC
 ![Screenshot 2022-10-02 205857](https://user-images.githubusercontent.com/70238785/193485291-c3f3235a-24b7-4b94-9dad-66f9353e5c7e.png)
here we have a created a virtual network that resembles a traditional network that we can add subnets to.
## Creating a subnet
![image](https://user-images.githubusercontent.com/70238785/193486216-6318640a-e315-4f92-8db1-0d51521832e3.png)
here we added subnets which is a range of ip addresses we can deply AWS resources from
## Creating an internet gateway
![image](https://user-images.githubusercontent.com/70238785/193488542-b86c16b7-8926-4214-94af-96ee86851093.png)
here we created a gateway which allows our VPC to connect to another network
## Creating a route table
![image](https://user-images.githubusercontent.com/70238785/193491913-1f95e615-12d9-401c-a4a5-eebf2009b380.png)
here we created a route table which determines where network traffic from the subnet and gateway we created is directed
## Creating a security group 
![image](https://user-images.githubusercontent.com/70238785/193492853-5ca1ef25-791f-48f1-992e-da134d9d779c.png)
here we created a security group which allows My IP, Wright state, and a running instance IP to SSH into the cloud
