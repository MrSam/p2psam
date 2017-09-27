# p2psam
NodeJS p2p chat network


# Getting started
npm install

# Creating a mesh 
node main.js client1 localhost:3000 localhost:3001
node main.js client2 localhost:3001 localhost:3000 localhost:3002
node main.js client3 localhost:3002 localhost:3001
