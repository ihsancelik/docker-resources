cat /etc/os-release
apt update
apt install curl -y
curl -sL https://deb.nodesource.com/setup_10.x | bash
apt install nodejs -y
cd opt/
mkdir node-app
cd node-app/
echo 'console.log("nodejsapp from ubuntu...");' > index.js 
node index.js