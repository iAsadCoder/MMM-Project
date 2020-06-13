# MMM Project '

This the readme for the MMMProject 

Complete project of the  based on the specification provided.

Few thing which does not meet the creteria  are :

  i) Did not used routing and all the server side code is in app.js
  ii) All the view files are in the view folder  
  Note: Did not focused on much on HTML & CSS.
  iii) All the view files are in .pug extension as the traiditional .html extension was not responding 
  properly with .html
   Also most of the javascript functions were not working including getElementById  and some jQuery functions which made the project difficult
   Also had issues with tridition html and CSS script as the files were on .pug there fore all the script and css are in the view file.
  
  iv) Each middleware is made with some modifications.
  Unfortunitely all the functions could not be executed without 'single query' as the database tables were not 
   organizaed the way i expected! I had to improvise.

   
  # 1) Login ApI:
  -After sucessful query retrives all  the data from employees table and checks with the username and password with one the user 
  has entered. If the it does not mtch shows the error message other wise logs in and and session is generated
  
  - Once the session is genrated it checks the session and then  runs another query is redirected an then is directed to  home page
	containing all the users orders and details # please ignore the web design  i havent really worked on that!
	
# 2) GetItem
  On nav bar click on items and the function of getItems would reun which will bring all the item details in single query

# 3) GetShops
 On  nav bar click on the Shops which will trigger the getShos and will being all the details of the shop in single query 
  
# 4)BookOrder 
 On the this page order can be booked. 


The database structure was little odd that is that is why i was not able to solve the problem with single query. 
Example
 - items table has stock detail which was quite odd considering the project . As itmes  is a generic table which will be usecd 
by all the stores. 
Also some tables should had direct relationship between them.

# Things i cam to learn
 1) Middlewares
 2) Nodemon 
 3) Different node js and express packages
 4) Triditionl javacacript does not work!
 5) Triditional .html format is not recommanded!
 6) Request and Response
 7) nvm node version manager
 9) Get() and Post()  functions!

# This my first time on node js and express . I believe that i can do much better job in future! Thank you! 
   
  
