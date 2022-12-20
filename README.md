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
