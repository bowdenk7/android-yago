# Yago Android Mobile App
This application is developed on Phonegap/Cordova.
#Phonegap Installation

# 1.Download and Install Java.
  -Download and install the recent release of the Java SDK.
  -Open the console and run java.It should run without problems.
  -Open the environment variables.
  -Add the Java SDK installatio path to the PATH variable.e.g c:/><your_java_installtion_path>/bin.
 #2.Download Apache ANT
  -Needed by Android and Cordova to build projets.
  -Downoad and install Apache ANT from  http://mirror.tcpdiag.net/apache//ant/binaries/apache-ant-1.9.4-bin.zip.
  -Add Path to the /bin folder to the end of the PATH variable.
#3.Download the Android SDK.
  -Download and install the latest Android SDK from http://developer.android.com/sdk/index.html#Other.
  -Open environment variables and add both the full path of adt-bundle/sdk/platform-tools/ and adt-bundle/sdk/tools/ to the end    of path variable.
  -Open the console and run android.It should provide a list of targets to install.
  -Open the SDK manager and install version 19-22.
 #4.Download and Install Node Js.
   -Download and install the latest version of nodejs.
   -Add the full path to the /bin folder to PATH variable.e.g C:\Program Files\nodejs\bin
   -Test by running node on the console.
  #5.Install Cordova.
    -Open the console window and run
       c:/> npm install -g cordova
  #6.Install Phonegap
     -On the same window run
        c:\>npm install -g phonegap
#Usage
  1.Creating working project
    -Open the console window and run
      c:/>phonegap create my-application.
      Nb:Creates the application projects on the selected location with the requisite project folders. 
    -To navigate to the app run
       c:/>cd my-application
  2.Build the application
    -Open the console and run
       c:/>cordova build android
        
  
   
