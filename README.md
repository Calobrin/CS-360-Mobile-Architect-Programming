# CS-360-Mobile-Architect-Programming
The repository for my work in CS-360 at SNHU, this course had me working with Android studio to make a simple inventory management system.


# Briefly summarize the requirements and goals of the app you developed. What user needs was this app designed to address?
The option I chose for my project was a basic inventory management app that would allow users to add an item to a SQLite database. The item would have a name and a quantity to be able to keep track of various items. This database of items would be displayed in a "grid", but for my work it was the use of a scrollable recyclerview that contained each item in its own 'card' that had the name and quantity associated with each item.

The basic user needs were also to be able to edit the quantity of the items, and delete them if they so choose.
Other basic requirements needed for the app was a way to login to the app, this was completed but further use of binding the items in the database to specific users was not implemented.
As well as a way for the app to be able to send SMS notifications upon items in the inventory running low on quantity.

# What screens and features were necessary to support user needs and produce a user-centered UI for the app? How did your UI designs keep users in mind? Why were your designs successful?
To begin, the first screen needed was the login screen, which featured two text entries for a username and password to be submitted. From there two buttons existed either to register that user if the name was not already taken, and then a login button using the login credentials the user entered.

From there the user is brought to the main screen of the app which displays the inventory database recycler view. Some features on this page is a button to go to the screen for adding, editing, and deleting of items. All of these three tasks are done on the same screen using the same text box entries for the name and quantity of the item. Once successfuly added, edited, or deleted the user is brought back to the screen showing the inventory and the changes they have made.

Also from this ivnetory screen there is the feature to go to the SMS permissions page where the user is prompted if they wish to receive SMS notifications about the quantity of items in the inventory running low.

The UI designs were simple and straight forward and were designed in a way to be easy to understand and were labeled if not otherwise. Nothing is left to guess work so any user would be able to successfuly navigate the app with ease and preform the tasks they wanted to.

# How did you approach the process of coding your app? What techniques or strategies did you use? How could those be applied in the future?

The primary strategy of working on the coding aspect of this app was breaking it into smaller parts. I have a login compoent, I have an inventory component, and I have the SMS component. Each of these could be taken on individually and worked with to complete the task they needed to. I could focus on one part at a time until they were complete, or in a semi-working state before moving on to the next part. This made the overall project easier to tackle and I planned out my days in advance for how to work on the overall project.

# How did you test to ensure your code was functional? Why is this process important and what did it reveal?

As said above, I worked on each component until it was working or complete, with the login this was simple. Could I login to the inventory app by using credentials that didn't exist in the database? If not then clearly the login screen is working in that regard. I also tested to see if I could succsefully login with the users I created, and that worked as well.

I did a lot of testing with the inventory database system when it came to deletion, and for a while my delete function didn't work as intended and it took me more time to sort through and get it to a functioning state. But I didn't stop working at it and testing it each iteration of changes until I got it working in a consistent manner.

This ultimately led me to changing how my delete would work within the app and changing the overall design. What I tried to do didn't work so I had to take a different route, which became a lot easier to get working and testing to ensure that it did. If I never tested the problems with my delete function I would have stayed on the route I was on with a non functioning part of my app, but instead I changed it and got it to a fixed and working state.

# Considering the full app design and development process, from initial planning to finalization, where did you have to innovate to overcome a challenge?

As mentioned above, I had to completely rethink my approach to deleting inventory from the database, as the approach I originally designed weeks ago was something I could not get to work. I had to overcome this challenge by completely refactoring one of the screens in my app and adding more functionality to it than I originally planned. This screen was just for adding items to the database, but it also became the screen I used to edit and delete items from the database too.

# In what specific component from your mobile app were you particularly successful in demonstrating your knowledge, skills, and experience?

Continuing from above, I had modified one of the simplest screens on my app to becoming the centerpiece of my work. I had a simple screen with two text fields and a button, and used it to then handle the entire inventory management part of my app. Being able to change gears so late in development and refactor this screen from something simple to have so much more functionality I think shows what I was particularly sucessful in demonstrating my skils learned. I went from struggling with getting my delete funtion to work, to acing the delete function and coming up with an update function on the spot and in no time at all. All the struggles I went through slowly taught me all I needed to know to whip up the update function in mere moments.
