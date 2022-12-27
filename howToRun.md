# How to run this Flutter Project

## Prerequisite:
### 1. You must have Android Studio, Android SDK and Flutter set up in your system. 
### 2. You should have already created a Virtual Device using Android Studio's Virtual Device Manager.

For Running this project:
1. Clone the repository.
2. Open Visual Studio Code in that repository.
3. Install Extensions **Flutter** and **Dart** in Visual Studio Code.
4. Go to file `pubspec.yaml`. On the Top Right corner, click on the Download icon. This option downloads the packages (dependencies) related to the project.

  ![image](https://user-images.githubusercontent.com/85622937/198702872-cefcca4e-f13e-47de-aeb7-54352f00f896.png)

5. Check your bottom right corner and change the device to your Android Emulator (Virtual Device). 

![image](https://user-images.githubusercontent.com/85622937/198703312-af8ca910-91a7-472f-baa2-b974082e53db.png)

![image](https://user-images.githubusercontent.com/85622937/198703401-63ab69ca-9b41-456b-90f5-a91618f6c24c.png)

In my case, I will choose Pixel4.
This will show your virtual device on your screen. Make sure the virtual device is powered on.

6. Open the file `main.dart` which is located in `lib` directory. Then, go to **Run > Run Without Debugging**. The Shortcut to perform the same operation is **Ctrl+F5**.
7. In the Debug console, you must see a message like **Launching lib/main.dart on sdk gphone x86 in debug mode...**
8. Once you get a message like the screenshot below, your application would be running in your virtual device - 

![image](https://user-images.githubusercontent.com/85622937/198704920-4360c638-ced9-4d9b-bc08-5941762c4a35.png)


Here's a snap of how the app looks on my virtual device:

![image](https://user-images.githubusercontent.com/85622937/198705116-93f095c4-73fc-4a8f-bbbf-1dfaa4bdf554.png)

## Cheers!!!
