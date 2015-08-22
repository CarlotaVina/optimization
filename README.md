## Carlota Vina Website Performance Optimization portfolio project

Project's goal is to optimize speed of this web site
I did several steps:
Step 1 : Improve PageSpeed Insights score for index.html
Step 2 :  Improve number de frames per second. Right fps is 60
Step 3: Time resize pizzas is 5 ms

Github repository  url is https://github.com/CarlotaVina/optimization.git
Download github repository.
Project folder is  C:\carlota\udacity\project4v1\	

#####Part 1 : Check  PageSpeed Insights score for index.html

First you have to install Python in your machine. It's also necessary to install ngrok
PageSpeed Insights is  here https://developers.google.com/speed/pagespeed/insights/

If you are in Windows open a command prompt. Change to project folder

cd C:\carlota\udacity\project4v1\
You download ngrok into your project folder and unzip it there.

Start the server

python -m http.server 8080

Open other command prompt and change to project folder. Execute

C:\carlota\udacity\project4\frontend-nanodegree-mobile-portfolio>ngrok http  8080

It appears a http url . You open PageSpeed Insights and in the text box write the above http URL.
Here you can see the score for mobile and laptop

#####Part 2 : Check  Frames per second

In the folder C:\carlota\udacity\project4v1\views open pizzas.html with Google Chrome. You open Dev Tools and  you go to TimeLine. Click the record button
(red button) and reload the page. Click another time record button to finish recording. In the screen, TimeLine appears. Number frames is 60.
Now, click record button and scroll the page, end recording. Number frames is 60.

#####Part 3 : Time resize pizzas 

Now, you scroll the page until to see a bar below Text Our Pizzas, before the images's pizzas. You click the record button and you move the bar to select the 
pizzas size. You end the record. You go to console log, there is a message with the resize pizzas time.



