**# PROJECT-4**

**MEAN STACK IMPLEMENTATION**

**Step 1: Install NodeJs**
![image](https://user-images.githubusercontent.com/113097621/208716551-4ad9135e-8669-4aaf-b436-963103884cda.png)
![image](https://user-images.githubusercontent.com/113097621/208716702-a26d469f-be6e-4de5-98ca-37e1850bc474.png)
![image](https://user-images.githubusercontent.com/113097621/208716825-b8745af7-63d1-4f6b-b882-e8b8d2a6a9d7.png)

**Step 2: Install MongoDB**
sudo apt-key adv --keyserver hkp://keyserver.ubuntu.com:80 --recv 0C49F3730359A14518585931BC711F9BA15703C6
![image](https://user-images.githubusercontent.com/113097621/208717362-7904fa46-3314-467c-b9b6-0612a9c198f7.png)

echo "deb [ arch=amd64 ] https://repo.mongodb.org/apt/ubuntu trusty/mongodb-org/3.4 multiverse" | sudo tee /etc/apt/sources.list.d/mongodb-org-3.4.list
![image](https://user-images.githubusercontent.com/113097621/208717500-615a5aca-9cf5-4710-993f-8eb350cfce12.png)

**Install MongoDB**
sudo apt install -y mongodb
![image](https://user-images.githubusercontent.com/113097621/208717868-6629b699-1bd5-48c5-819a-020277523a9b.png)


**Start The server**
sudo service mongodb start

**Verify that the service is up and running**
sudo systemctl status mongodb
![image](https://user-images.githubusercontent.com/113097621/208718434-54555a4b-7eb5-4099-8bf2-5c3cde18f1aa.png)


Install npm – Node package manager.
sudo apt install -y npm

**Start The server**
sudo service mongodb start
![image](https://user-images.githubusercontent.com/113097621/209156390-583994d3-772c-49dc-bbcc-b4799204a699.png)

**Create a folder named ‘Books’**
![image](https://user-images.githubusercontent.com/113097621/209156571-395e0f0a-5aed-4e5b-9d4f-095f6154714e.png)

**In the Books directory, Initialize npm project**
npm init
![image](https://user-images.githubusercontent.com/113097621/209157519-f6b3da95-527e-488d-803e-a08e72d81d5d.png)
![image](https://user-images.githubusercontent.com/113097621/209157816-91a3ef2d-c1e1-4e48-9b41-7ca152cf9e38.png)


**Add a file to it named server.js**
vi server.js
![image](https://user-images.githubusercontent.com/113097621/209158149-b2dafb70-bb6a-412a-bb7c-55e643a59cd7.png)


**Install Express and set up routes to the server**
![image](https://user-images.githubusercontent.com/113097621/209158436-9de53c35-70c4-499b-ad47-af29a732b8b0.png)

**In ‘Books’ folder, create a folder named apps**
![image](https://user-images.githubusercontent.com/113097621/209158708-7c654a2a-9939-410e-9289-a3e605acd50f.png)

**Create a file named routes.js**
vi routes.js


**In the ‘apps’ folder, create a folder named models**
mkdir models && cd models
![image](https://user-images.githubusercontent.com/113097621/209159383-0abba408-28fb-445a-867b-7ce9db94b167.png)

**Create a file named book.js**
vi book.js

**Step 4 – Access the routes with AngularJS**

**Create a folder named public**
![image](https://user-images.githubusercontent.com/113097621/209160011-94e8fe2b-ca48-4323-907d-c0978dd63def.png)

vi script.js


**Start the server by running this command:**
node server.js

**The server is now up and running, we can connect it via port 3300. You can launch a separate Putty or SSH console to test what curl command returns locally.**
![image](https://user-images.githubusercontent.com/113097621/209161048-ce2b721f-9e8f-40dd-8fff-09b8711a71cc.png)


