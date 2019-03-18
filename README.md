## Let's Eat
Let's Eat is a food ordering application that allows users to order food for pick up from a single restaurant. Hungry clients of this fictitious restaurant can visit its website, select one or more dishes and place an order for pick-up. They will receive a notification when their order is ready. When an order is placed the restaurant receives the order via SMS. The restaurant can then specify how long it will take to fulfill it. Once they provide this information, the website updates for the client and also notifies them via SMS.A modern telecom API service also know as Twilio is used to implement SMS communication from the website to the client and restaurant. This app was inspired by Ritual.

This project was built in collaboration with @tkoriginal @anisa114

## Getting Started
1. Install all dependencies (using the npm install command )
2. An env file will be required to get the program running, below are the configurations:  
    ```DB_HOST=localhost
    DB_USER=labber
    DB_PASS=labber
    DB_NAME=midterm
    DB_SSL=true
    DB_PORT=5432
    TWILIO_ACCOUNT_SID= got from twilio
    TWILIO_AUTH_TOKEN= got from twilio
    MY_PHONE_NUMBER= got from twilio 
3. Run the development web server using the node 'npm run local' command

## Final Product 

!["Homepage"]Homepage(https://github.com/ShahjamalMalik/Lets-Eat/blob/master/public/images/Homepage.png)
!["Menu Page"]Menu(https://github.com/ShahjamalMalik/Lets-Eat/blob/master/public/images/Menu%20Page%20Part%202.png)
!["Menu Page"]Menu(https://github.com/ShahjamalMalik/Lets-Eat/blob/master/public/images/giphy.gif)
!["Ordering"]Ordering Process(https://github.com/ShahjamalMalik/Lets-Eat/blob/master/public/images/Ordering.gif)
!["View Order"]View Order(https://github.com/ShahjamalMalik/Lets-Eat/blob/master/public/images/View%20the%20order.png)
!["Owner Side"]Owner Side(https://github.com/ShahjamalMalik/Lets-Eat/blob/master/public/images/Owner-Side.gif)

## Stack and Dependencies
1. ES6 for server-side (Node) code
2. ES5 for front-end code
3. Node
4. Express
5. Cookie-Session
6. Javascript
7. AJAX 
8. Bootstrap 3
9. HTML5
10. CSS3
11. jQuery
12. SASS 
13. PostgreSQL
14. Knex
