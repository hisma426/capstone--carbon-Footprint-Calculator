# capstone--carbon-Footprint-Calculator
Capstone project: Carbon footprint calculator website

This is a website that I created to bring awareness to the amount of carbon emissions emitted from everyday tasks.

It consists of a:
- Welcome page that shows you different environmental facts about the word
such as how:
   - Industrialized meat production is the greatest cause of deforestation in the world.
   - Farmers in Brazil are purposefully burning down forests in order to build farms.
   - Cows eat 16 pounds of vegetation in order to produce 1 pound of flesh.
   - The energy consumed to produce one hamburger could drive a car for 20 miles.
   - 87% of agricultural land in the U.S is for raising animals.
   - More than 80% of the corn we grow and 95% of oats are fed to livestock.
   - You then have a button saying: go to calculate which takes you to the login/ registration page
   - etc..
- If you don't have an account you would click the text link saying register where you would register your 
   - Name
   - Email
   - Password
   - And confirm password
- This is then saved in the user table in the database which consists of 
   - CREATE TABLE users (id INTEGER PRIMARY KEY AUTOINCREMENT,
   	 username TEXT UNIQUE NOT NULL,
   	 password TEXT NOT NULL

- Now you go to a page that says you can login now
  - Once your login information is in the database and you type it in correctly it will be authenticated using javascript and the database will  connect to the html page displayed through php so that everything works seamlessly
- You now are in your account where input how much of everything you have done
   - How many miles did you drive? 
      - miles
    - How long was your hot shower? 
       - minutes
   - How many hours did you have the lights on? 
      - hours
   - In how many rooms had the lights on? 
      - rooms
   - How many portions of the following foods did you eat?
      - Beef
      - Turkey
      - Chicken
      - Pork
      - Lamb
      - Tuna
      - Cheese
- Press the Calculate button after all fields have been filled and you will be given how much carbon emissions came from your actions
      This amount of carbon emissions will then be logged in the history log so you can track your progress to less carbon emissions 
      The log shows your time stamp from your carbon emissions log so you know when each emission was done/ created
     This history log has a database table as well to store the data
The data that is stored is  the total carbon footprint of all actions combined and then separately how much of those emissions where food.
Now, what have I not gotten to work:
The login page with authentication and a database.
I really struggled with creating a database in general so i couldn’t get it to work
The registration couldn’t save a username and password to a database meaning an account couldn’t be created meaning nothing could be authenticated to go to the personal account carbon footprint tracker
As I said before I could not get an understanding of how to make a database work so the history log for carbon emissions isn’t in a database. When you make a log all in the same session ie when you have the browser open the logs go into the history log with the timestamp but once you refresh or exit everything isn;t saved so you cannot track your progress


What to do when you open my project in github
Start with the welcome html page 
Then click the go to calculations button
The login and register page won't work as it it won’t let you into your account since there is no database with data to authenticate and let you in so just go into the folder and click on the  calculate.html page
There  you can calculate your carbon foot print
