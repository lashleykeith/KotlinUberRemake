# KotlinUberRemake
YouTube tutorial for an Uber app in Kotlin. 
I will show the problems people will encounter then I will show you the solution to get the app to work for each problem.

# First problem you would find.
## SplashScreenActivity.kt
progress_bar is not recongized it should be connected to the activity_splash_screen.xml
![SplashScreenActivity kt](https://user-images.githubusercontent.com/21030885/100082433-93cdc500-2e8b-11eb-8952-977bedc6c29a.png)

## activity_splash_screen.xml
this is the progress_bar and the id.
![activity_splash_screen xml](https://user-images.githubusercontent.com/21030885/100082520-af38d000-2e8b-11eb-826a-11db073d32eb.png)

## build.gradle
![build gradle1](https://user-images.githubusercontent.com/21030885/100084615-5454a800-2e8e-11eb-8ee7-4d4a4ccbb2a9.png)

![build gradle2](https://user-images.githubusercontent.com/21030885/100084646-5d457980-2e8e-11eb-87f8-66157542fb8c.png)

# First first solution you will need.
## build.gradle
Change the build.gradle.
![thirdfixphoto2](https://user-images.githubusercontent.com/21030885/100540779-d96f0100-3282-11eb-8ba1-dc68b30d9dd7.png)

## SplashScreenActivity.kt
Make sure you update the SplashScreenActivity.kt file
![thirdfixphoto1](https://user-images.githubusercontent.com/21030885/100540775-d4aa4d00-3282-11eb-80bc-b040b4ff6b81.png)

