# Task2

1. Create the macine with apache installed and ssh that from your local terminal also create the pem file and use that on your terraform .

2. Create vpc for your local machine ip ports open for access . Attach that with your machine . Extract the plan file and store once approval is given them apply those changes.


--> Here is a machine with apache installed in it , the tag user data is where we write our script to install apache
![Screenshot (376)](https://user-images.githubusercontent.com/89116808/231092258-5cdc0524-94f8-45ec-b80f-eaec2ebc1fe7.png)


--> Now when we use command "terraform plan >out.json" then it will create a file with all the information about plan state in form of json
![Screenshot (378)](https://user-images.githubusercontent.com/89116808/231094576-c46871ee-5926-4657-aab9-5e9651022297.png)

--> Also we have created a pem file and downloaded outside our directory so that it wont be available publicly
![Screenshot (377)](https://user-images.githubusercontent.com/89116808/231095136-33b4ef6b-6652-4e75-8eac-74526c76486c.png)


--> We have created NACL so that our machine is only accessible to only our ip.
![Screenshot (67)](https://user-images.githubusercontent.com/89116808/231097199-f7933c46-72b4-423a-8c5c-2ca5ab3430c0.png)


