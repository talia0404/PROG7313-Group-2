# Instructions and resources

**Google Doc - https://docs.google.com/document/d/1e5WptAYcOL2N-XEUSCgOtsnYn_YtUUnwb6RnSyjWwZE/edit?usp=sharing**

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


 ##  11 March - Tuesday:

1. User Entity, DAO and database:

Create UserEntity with a unique username constraint.

Define UserDao with methods to insert a user and query by username.

Update AppDatabase to include both UserEntity and your event entity.


2. Register Screen:


In RegisterActivity, validate input, check for unique username, insert user, and then pass the username to the event creation screen.

Event Creation Screen:

Retrieve the username from the Intent.

Update a TextView to show a personalised greeting.


##  12 March - Wednesday

**Once you're done with writing to and reading from the database:**


3. Event Management Screen:

Create a list screen that displays all saved events using RecyclerView.

Allow users to update or delete events.

Resources: 

Medium, Recycler View for beginners in Android - https://medium.com/@myofficework000/recycler-view-for-beginners-in-android-b54b1f445e38

Create dynamic lists with RecyclerView - https://developer.android.com/develop/ui/views/layout/recyclerview


## 18 March

1. Implement Firebase Authentication in the MeetMeWhere app

Integrate Firebase Authentication into your MeetMeWhere app so that user registration and login are handled securely via Firebase rather than locally. 
Update your navigation so that after a successful login, the user is taken to the Event Management screen. 

- Set up Firebase (Create a Firebase project via the Firebase Console).

- Update Registration Flow.

  Modify your registration screen to use an email field.

- Update Login Flow.

Update your login screen to use an email field for authentication.

- Testing.

  Ensure that registration, login, and navigation between screens work.

2. Ensure that users can navigate between screens in the app using a navigation bar.

Refactor the MeetMeWhere app to use a Bottom Navigation Bar to switch between each screen.

Requirements:

- Use the Android Navigation Component to manage navigation between fragments.
- Create fragments for your screens
- Include a BottomNavigationView in your Activity layout that allows the user to switch between fragments.

## 19 March 

RecyclerView  Activity

You have been hired as an Android Developer for a local e-commerce startup that wants to build a simple app for showcasing their latest product catalog. 
They need a dynamic list where users can see product images, descriptions, and remove items from their cart before making a purchase.

Your task is to implement a RecyclerView that displays a list of products, where each product includes:
- A product image
- A product description
- A Remove button to delete items from the list

The startup wants this feature to be fast, responsive, and user-friendly, so you must implement an efficient RecyclerView with proper data handling.

### **Then implement RecyclerViews into the MeetMeWhereApp:**

3. Event Management Screen:

Create a list screen that displays all saved events using RecyclerView.

Allow users to update or delete events.

### **If you're done with RecyclerView**

Activity: Integrating Firebase Authentication in an Android App

You're developing a simple Login App for a local book club. Members should be able to sign up and log in using their email and password. 

Objectives:

- Integrating Firebase Authentication into an Android project.
- Implement email and password authentication.
- Handle user sign-up and login.
- Display appropriate success and error messages.

<br>
<br>
<br>

   
### Fill out this form on group details: 

Only one person from each group must respond.

https://forms.office.com/Pages/ResponsePage.aspx?id=RI8M4Wn0j0S8DdeBKI_wG3g738v0IhlIukhq5khQN1RURFg2Wkc3SVVXTjRHSkxGQVpMVkpLTDA3SC4u 







