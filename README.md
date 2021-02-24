# Example of creation of dockerfile for Node js application

#First step

`npm install` to create package-lock.json file on the command line

#Second step

$docker build -t node-web-app .

#Third Step
$docker run -p 49160:8080 -d node-web-app

#Check if all good
$curl -i localhost:49160

