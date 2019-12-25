# 12 Days Of Code

Merry Christmas! I hope you're enjoying your two week break. Hopefully, 
you're finding a way to keep your programming skills sharp while you're away 
from Codeup.

Not sure what to work on? The 12 Days of Code will give you a daily challenge
 covering different topics we've learned so far! If you start this on 
 Christmas Day, you'll finish the review the day before you get back to class. 
 
 It's up to you which projects and repos these exercises will live in. After 
 all, it's just for practice.
 
 Happy Coding :) 
 
 ### December 25th
 
 - Today, build a simple Christmas themed HTML page using your preferred 
 framework for layout and styling. Or, use custom CSS if that's your thing.
 
    - Have a banner that says "Merry Christmas"
    - Make a list of your favorite Christmas songs
    - Include a Christmas photo in there too!
 
 ### December 26th
 
 - We're going to build on our Christmas page a little bit.
    
    - Make your list of songs clickable so that they send you to a video of 
    it on Youtube.
    - Create an input box underneath your song list. 
    - Add a submit button for this input box.
 
 ### December 27th
 
 - Adding a bit more interactivity.
  
    - Using either vanilla JS or jQuery, allow a user to add a song to your 
    list. 
    - **Bonus**: you can add another input box for the song URL on Youtube if 
    you want the new addition to be clickable.
    - **Bonus**: add the Konami Code for a secret feature! Maybe an image? A 
    video? A song? It's up to you.
 
 ### December 28th
 - Let's start on a little bit of Java review! You'll be working on the 
 Adlister shortly after the break so it's important for us to have a solid 
 foundation.
 
    - Create a new Java package called Christmas.
    - Create a new Java class called Santa.
    - Create your main method. Using Console IO, allow him to ask the user what 
    they 
    want for Christmas.
    - Store the response in a String variable.
    - **Bonus**: Continue to ask if the user enters an empty String
     
 ### December 29th
 
 - Santa's got a lot of work to do before next year...
 
    - Create a new Java class called Reindeer. This should be in the same 
    package as your Santa class.
    - This should have a protected String property of 'name.'
    - Add a constructor that sets this name property when a new Reindeer is 
    created. Display a message that tells you the name of the new Reindeer 
    that has been created.
    - Test your new class in the main method of the Santa class by creating 
    instances of Santa's reindeer.
 

 ### December 30th
 - Santa has 9 reindeer. 10 if you count Olive, the other reindeer...
 
    - Going back into your Santa class, create a public static Array property 
    that 
    stores 
    9 (or 10) instances of Reindeer objects.
    - go back into your main method and give each Reindeer instance a 
    position in the Array you just created. 
    
 ### December 31st
 
 - What if we want to hire more Reindeer in the future and add them to our 
 Array?
    - In your Santa class,
    create a pubilc static addReindeer method that would allow us to add to 
    our Array.
        - Remember that Arrays in Java have a set length, so this method will
         actually need to create a copy with a different lenght.
         - Need a hint? Go back to our ArraysExercises from Java II. 
 
 ### January 1st
 
 - Remember when Santa asked us what we wanted for Christmas?
 
    - In your Santa Class, create an ArrayList of Strings called 'wishlist'
    - Each time Santa asks what you want for Christmas, add the user response 
    into the 
    ArrayList. Keep 
    adding presents!
    - Go into the main method to check if your wishlist has been stored in 
    the ArrayList.
    - **Bonus**: Create a HashMap instead that stores the name of the person 
    and the item they requested.
 
 
 ### January 2nd
 
 - I feel like Santa's job would be a lot easier if he had a SQL database to 
 work with.
 
    - Create a new user 'santaclaus' that has all privileges on all databases
     and tables.
     
    - Create a new database called 'christmas_db'
 
 ### January 3rd
 
 - You better watch out, you better not cry...
 
    - In the christmas_db, create a table called 'people' with these properties:
        - first_name
        - last_name
        - age
        - birthday
        - nice (either true or false)
        - wishlist
        
    - **Bonus**: Create this table by running a sql migration file.
 
 ### January 4th
 
 - There are a lot of people we need to keep track of and deliver to by next 
 Christmas.
 
    - Create a seeder script for your people table.  
 
 ### January 5th
 
 - However, you only get a gift from Santa if you've been nice all year. 
 
    - Using a DELETE statement, remove people who have not been nice this 
    year. (Value of the nice column is 'false') 
    
    
    
 
 ### Happy Holidays!!!
 