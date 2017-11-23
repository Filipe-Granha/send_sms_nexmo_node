# SMS Node.js App, using Nexmo.com

SMS app, using Nexmo and Socket.io

Node based app to send sms
(first 2 euros or dollars are free, allowing to conduct some testing)

Download repository

Terminal:
1) npm init
2) npm install --save express ejs nexmo body-parser socket.io 
3) npm install nodemon -g
4) nodemon app

Browser: </br>
http://localhost:3000/

Before you can use the app, follow these steps:

1) create an account at nexmo.com (you'll need a mobile phone number. No credit card needed though)

2) use API credentials given when you sign up, and replace them in the app.js file:
"key" and "secret"


You can add more testing numbers here:
https://dashboard.nexmo.com/test-numbers
