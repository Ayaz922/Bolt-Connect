# Bolt-Connect

# Overview
It is always great to control a microcontroller from an android app .
So this project focuses on controlling BotIot (Microcontroller) from android app.
We have built an android app named Bolt-Connect which can control Bolt-Iot in very easy and efficient way.
  
## Implementation 
We can connect our Bolt-Cloud using Bolt Cloud Api .
so what i have done i used volley to make HTTP Request and Response.
for every event of Bolt it generates a HTTP url and make a HTTP request ,
BoltCloud api respond to the request and give it back to the Android app.
so in this way we can do anything with bolt with this Mobile App.
  
## Screenshots
<table>
    <tr>
     <td><img src="/Screenshots/Screenshot_2018-11-25-11-33-39-677_com.medeveloper.ayaz.boltconnect.png"></td>
     <td><img src="/Screenshots/Screenshot_2018-11-25-11-35-17-971_com.medeveloper.ayaz.boltconnect.png"></td>
     <td><img src="/Screenshots/Screenshot_2018-11-25-11-35-27-854_com.medeveloper.ayaz.boltconnect.png"></td>
    </tr>
     <tr> 
      <td><img src="/Screenshots/Screenshot_2018-11-25-11-35-40-874_com.medeveloper.ayaz.boltconnect.png"></td>
      <td><img src="/Screenshots/Screenshot_2018-11-25-11-35-48-401_com.medeveloper.ayaz.boltconnect.png"></td>
      <td><img src="/Screenshots/Screenshot_2018-11-25-11-35-52-164_com.medeveloper.ayaz.boltconnect.png"></td>
      </tr>
  </table>
  
## Development Setup

Before you begin, you should have already downloaded the Android Studio SDK and set it up correctly. You can find a guide on how to do this here: [Setting up Android Studio](http://developer.android.com/sdk/installing/index.html?pkg=studio)

### Setting up the Android Project

1. Download the *Bolt-connect* project source. You can do this either by forking and cloning the repository (recommended if you plan on pushing changes) or by downloading it as a ZIP file and extracting it.

2. Install the NDK in Android Studio.

3. Open Android Studio, you will see a **Welcome to Android** window. Under Quick Start, select *Import Project (Eclipse ADT, Gradle, etc.)*
4. Navigate to the directory where you saved the Bolt-connect-android project, select the root folder of the project (the folder named "Bolt-connect-android"), and hit OK. Android Studio should now begin building the project with Gradle.

5. Once this process is complete and Android Studio opens, check the Console for any build errors.

    - *Note:* If you receive a Gradle sync error titled, "failed to find ...", you should click on the link below the error message (if available) that says *Install missing platform(s) and sync project* and allow Android studio to fetch you what is missing.
    
6. Once all build errors have been resolved, you should be all set to build the app and test it.

7. To Build the app, go to *Build > Make Project* (or alternatively press the Make Project icon in the toolbar).

8. If the app was built successfully, you can test it by running it on either a real device or an emulated one by going to *Run > Run 'app'* or pressing the Run icon in the toolbar.

## How to use
First Install the App
Once you open the app you will get a screen like this
<br>
<img align="center" src="/Screenshot_2018-11-25-11-27-26-754_com.medeveloper.ayaz.boltconnect.png"/><br>
<p>Just type your Bolt Device Id and API key in the box and Hit submit.</p>
   
   
