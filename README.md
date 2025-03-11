# Instructions and resources

## Research  Kotlin vs C#; differences and similarities. 
## Research OOP  in Kotlin 

### Tip App: https://github.com/talia0404/TipCalculator

## MeetMeWhere


### 04/03/2025

Research ViewBinding and implement ViewBinding in your code:

Medium_What is View Binding in android and how it works internally_URL: https://medium.com/@sandeepkella23/what-is-view-binding-in-android-and-how-it-works-internally-74c9ce0e5422 

### User Authentication (Local):

Develop a login screen with username and password fields.

Implement basic validation to ensure inputs are provided.


### Event Creation:

Design a screen where users input event title, description, date, time and a location. 

Include a button to save event details.

### 05/03/2025


1. Enable navigation in your app using Intents.

The user should be able to navigate from the login screen to the event creation screen.


Intent resources - https://www.geeksforgeeks.org/what-is-intent-in-android/


2. Research RoomDB VS Firebase in Android Studio.


RoomDBResource - https://developer.android.com/training/data-storage/room


## **Have this ready for 11 March - Tuesday:**


1. Create a register screen.

   The user should be able to enter a unique username (the username must not already exist in the database), a password and confirm their password.


3. If the fields are valid (non-empty fields and ensure the password and confirmation match) then these details should be saved in your database.

   Display appropriate error messages.

4. Retrieve the username from the database and add it to a TextView.

   This TextView should be the heading for the EvenCreation Activity Screen. Eg: Heading: "Welcome user3789! Create an event:"

 ##  11 March - Tuesday:**

1. User Entity, DAO and database:

Create UserEntity with a unique username constraint.

Define UserDao with methods to insert a user and query by username.

Update AppDatabase to include both UserEntity and your event entity.


2. Register Screen:


In RegisterActivity, validate input, check for unique username, insert user, and then pass the username to the event creation screen.

Event Creation Screen:

Retrieve the username from the Intent.

Update a TextView to show a personalised greeting.

   
### Fill out this form on group details: 

Only one person from each group must respond.

https://forms.office.com/Pages/ResponsePage.aspx?id=RI8M4Wn0j0S8DdeBKI_wG3g738v0IhlIukhq5khQN1RURFg2Wkc3SVVXTjRHSkxGQVpMVkpLTDA3SC4u 







