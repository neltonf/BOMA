#### BoscoMessagingApp ("BOMA") Messenger for Android
BOMA is an open-source app with real-time messaging. This repo contains the source code for Android
In a working/educational campus there are a number of people working various tasks,in order for them to function efficiently,
proper communication must be ensured.Targeting a certain message to  a certain group or team makes it much easier and less chaotic.
The App ensures targeted communication to a certain domain of people and also direct one to one communication.

<img src="https://github.com/neltonf/BOMA/blob/master/ScreenShot/Registration.jpg" width=180 />&nbsp;&nbsp;&nbsp;
<img src="https://github.com/neltonf/BOMA/blob/master/ScreenShot/Login.jpg" width=180 />&nbsp;&nbsp;&nbsp;
<img src="https://github.com/neltonf/BOMA/blob/master/ScreenShot/Contact.jpg" width=180 />&nbsp;&nbsp;&nbsp;
<img src="https://github.com/neltonf/BOMA/blob/master/ScreenShot/Message.jpg" width=180 />&nbsp;&nbsp;&nbsp;
<img src="https://github.com/neltonf/BOMA/blob/master/ScreenShot/Message2.jpg" width=180 />


## Downloading the Source Code

### Clone the Repository (Recommended)
If you have git installed, this is a recommended approach as you can quickly sync and stay up to date with the latest version. This is also a preferred way of downloading the code if you decide to contribute to the project. 

To download, open a terminal and issue following commands:

    $ mkdir Messenger
    $ cd Messenger
    $ git clone https://github.com/neltonf/BOMA.git

### Download the code as a zip file
You can also download the complete Android Messenger source code as a zip file. Although simple, the downsize of this approach is that you will have to download the complete source code everytime it is updated on the repository. 

## Configuration

**First** : Create a project at [Firebase](https://firebase.google.com/), please refer to [Add Firebase to your app](https://firebase.google.com/docs/android/setup#add_firebase_to_your_app)

**Second** : Download the Firebase config file

**Third** : Replace the 'google-services.json' file in 'BOMA/app/' with your Firebase config file

**Finally** : Now, you can run it by using your own Firebase storage.

### Stay Up-to-date
Whatever approach you take to download the code, it is important to stay up-to-date with the latest changes, new features, fixes etc. Ensure to **Star(*)** the project on GitHub to get notified whenever the source code is updated. 

## Build and Run

Before we dive into building and running a fully featured Messenger for Android, ensure that you've read the following.

 - Latest Android Studio Installed
 - An Android Device

Building the code is as simple as:

 1. Launch Android Studio
 2. Open the project from the folder where you have downloaded the code using menu `File -> Open`
 3. Build using menu `Build -> Rebuild Project`
 4. It may take a while to build the project for the first time. 
 5. Once the build is over, run on the device using menu `Run -> Run (app)`
 6. That's it, you should see the welcome screen like below.
 
 ## Key SDKs user in this project

- Glide SDK
- Material UI Module
- FireBase DB
- RecyclerVieW
