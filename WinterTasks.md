# Android App Development Winter Tasks

## Learning Resources
- [Official Documentation](https://developer.android.com/docs)
- [The New Boston PlayList](https://www.youtube.com/watch?v=QAbQgLGKd3Y&list=PL6gx4Cwl9DGBsvRxJJOzG4r4k_zLKrnxl)
- [Help with installing Android Studio](https://www.geeksforgeeks.org/guide-to-install-and-set-up-android-studio/)

## Resources for flutter
- [Getting Started](https://github.com/bitsacm/Slack-Stock-DAG/blob/master/flutter_app_dev.md)

#### Some Specific Topics you will need to learn
-  [Constraint Layout](https://www.journaldev.com/13590/android-constraintlayout)
- [Activities](https://www.tutorialspoint.com/android/android_acitivities.htm)  and [Fragments](https://www.tutorialspoint.com/android/android_fragments.htm)
- [Bottom Navigation Bar](https://material.io/develop/android/components/bottom-navigation-view/)
- [Recycler View](https://www.youtube.com/watch?v=USbTcGx1mD0&list=PLk7v1Z2rk4hjHrGKo9GqOtLs1e2bglHHA)
- [Firebase](https://firebase.google.com/docs)
- [Sending Emails](https://medium.com/@cketti/android-sending-email-using-intents-3da63662c58f)
- [Glide](https://guides.codepath.com/android/Displaying-Images-with-the-Glide-Library) - For displaying images stored online

## <ins>Task 1</ins>
You have to make a **simple coffee ordering app** in which you can enter your name, select various toppings, and enter the quantity. 
There will be **three buttons**, one to reset the screen, one to display the order summary, and one to email this order summary to someone.
Special care must be taken to ensure that the **UI is responsive**, i.e it works well for all screen sizes.
You can see a **demo of the app** here :- https://www.youtube.com/watch?v=Kp15wk2X1p8 

## <ins>Task 2</ins>
In this, you will have to make a **Multi-screen app**.
You will be creating an app similar to the **YouTube mobile app**.
You have to only clone the **Look and feel** of the app, only for the **5 screens** that can be accessed using the bottom navigation bar.
**You don't have to make it functional**

## <ins>Task 3</ins>
**Firebase** is a service provided by Google that helps in building apps **without a dedicated back-end**.
For this task, you will be connecting you app with Firebase, and use services such as **User Authentication** and **Firestore**.
Your app will contain a **Login Screen** that will ask users for username and password.
Upon logging in, they will be able to see **their profile**, that will consist of their name, email and their hobbies. Make sure to add a **logout button** as well.
A user can **create an account**, by pressing a sign-up button on the login page. While signing up, the user will have to enter all the information required for his profile.

## <ins>Task 4</ind>
In this task, you will be **extending the previous app**, to **include a profile image** associated with the user account.
For storing the image, you can use **Firebase Storage**. 
Also, on the page where you are displaying the account details, you would have to give an option to **edit their existing information as well**.