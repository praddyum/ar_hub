STEPS  FOR USING  EASY AR SDK (playing a video on image target )  :-


( Version-4.0)
STEP 1:
Go to  https://www.easyar.com/  .

STEP 2:
If you already have an account SIGN IN (https://www.easyar.com/view/login.html)
otherwise create an account by clicking on the “Sign up” button 
(or else visit  https://www.easyar.com/view/signUp.html) .

STEP 3: 
Click on the “Develop Center“ option .
	   
Now click on “I need a new Sense License key” and then choose your EasyAR version (3.0 or 4.0) in the “Type” section.
   
   1.Select “EasyAR Sense 4.0 Personal “ 

   2.Enter an App Name according to your choice 

   3.Enter ‘com.your_name.your_app_name’  same in both  Bundle ID  and  
     Package Name

   4.Choose China in”SpatialMa Region:” option.

   5. Enter a “SpatialMap Database Name”.
   
   6. Few restrictions are there:

   7. Click on “confirm”.



STEPS  FOR USING  EASY AR SDK (playing a video on image target )  :-

STEP 4:
Head back to the Home page on easyar.com and download “EasyAR Sense Unity Plugin Samples” (EasyARSenseUnityPlugin_4.0.0-final_Samples_2020-01-16.zip) (basic version).

STEP 5: 
Now back in Unity drag that SDK in assets and import everything.

STEP 6:
From your Easy AR account copy your license key and your Bundle ID (you can get your License key and ID by clicking on your database name in the “Sense Authorization” section) (you can even modify the ID if such a need arises.)

Now in Unity in ASSETS go to EasyAR>Resources>EasyAR>Settings and paste the license key in the inspector panel and in Build Settings after switching your platform to Android /IOS paste your exact Bundle ID in Player Settings>Company Name and in Package Name (Identification Section) (android) /Bundle identifier (ios).

STEP 7: 
In UNITY:
Import the “EasyAR Sense Unity Plugin Samples” into unity.
Here there are Sample scenes to run EasyAR Sense Unity Plugin.
You can take a sample from Assets>Samples>Scenes>Object Sensing and move it in your scenes folder.

Now delete the cube (from ImageTarget-namecard in hierarchy), drag and drop the required video in Assets and the required image target in Assets>StreamingAssets.

Click on ImageTarget-namecard (hierarchy panel), copy and paste the name of your image target (you can rename it in StreamingAssets folder) in Target Name option in “Image Target Controller'' component and copy the name of your image along with its extension in Image Path (eg. a.jpg) option.

Drag and drop your video (from Assets) on quad (inside ImageTarget-namecard) (hierarchy panel).

	  


( Version 3)
STEPS  FOR USING  EASY AR SDK (playing a video on image target )  :-

STEP 1:
Go to https://www.easyar.com/.

STEP 2: 
If you already have an account SIGN IN (https://www.easyar.com/view/login.html) otherwise create an account by clicking on the “Sign up” button 
(or else visit https://www.easyar.com/view/signUp.html) .

STEP 3:  
Now click on “SDK Authorization” and then on “ADD SDK License Key”.
   
       1.Select “EasyAR SDK Basic “ 
   
       2.Enter an App Name according to your choice 
   
       3.Enter ‘com.your_name.your_app_name’  same in both  Bundle ID  and  
         Package Name,
  
       click confirm.

STEP 4: 
Go back to the Home page and in the downloads section scroll down to Unity part and download the Unity package (basic version)(right side of page ).




STEP 5: 
Now back in Unity drag that SDK in assets and import everything.

STEP 6: 
In your Easy AR account and copy your license key also copy your Bundle ID.
Now in Unity in ASSETS go to EasyAR>Common>Resources>EasyAR and paste the license key in the inspector panel and in Build Settings after switching your platform to Android /IOS paste your exact Bundle ID in Player Settings>Company Name and in Package Name (Identification Section) (android) /Bundle identifier (ios).

STEP 7: 
In UNITY:
You can take a sample scene from Assets>Samples>Scenes and move it in your scenes folder. (copy “HelloAR_ImageTarget” scene for image target).

Now delete the cube (from image target), drag and drop the required video in Assets and the required image target in Assets>StreamingAssets.

Click on ImageTarget (hierarchy panel), copy the name of your image (you can rename it in StreamingAssets folder) in Target Name option in “Image Target Controller” component and copy the name of your image along with its extension in Image Path option.

Drag and drop your video (from Assets) on ImageTarget (hierarchy panel).

	  



