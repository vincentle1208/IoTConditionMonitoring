# IoTConditionMonitoring Installation Instruction

## WiFi connection
Following instructions on: ceit.uq.edu.au/wiki/index.php/connecting_to_Eduroam

## Manual installation

Following commands must be executed through Terminal on the Raspberry Pi 3 as a Pi User

### Install Node-RED development platform 
sudo apt-get update

sudo apt-get install nodered

sudo apt-get install npm

sudo npm install -g npm@2.x

hash -r

### Update nodejs to the latest version for extra feature nodes

update-nodejs-and-nodered

### Install phpLiteAdmin database on the Raspberry Pi 3
Following instructions on https://randomnertutorials.com/how-to-install-phpliteadmin-database-in-a-raspberry-pi

sudo apt-get install php7.0-sqlite3

### Install Amazon Web Service package for Python codes execution
pip install AWSIoTPythonSDK


