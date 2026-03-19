# This Serves as a Guide to Provide Animated Breathing to Enemies (we want this for our games!)
## Special Thanks to: Github - [Kakudo](https://github.com/kakudo) for the add-on
## Special Thanks to Bluasen from Discord for indicating to work out the Prefab

It took me hours to make this work so I am creating this guide so that it would be easy for you and save time.  
This is for games created via RM Unite.  
Follow each step and you will be alright.  

Assumptions: You have RM Unite v1.3.0 and Unity Editor v.2022.3.62f3.  

Step 1: Download RDEnemyBreath add-on from [Kakudo's Github Repo](https://github.com/kakudo/rmu-addons).  
Step 2: Unzip the file. Go to the folder labeled: "RDEnemyBreath". From here you will see 2 C# scripts and a folder:  
- EnemyBreath.cs (this is a C# script)
- RDEnemyBreath.cs (another C# script)
- A folder labeled: "Resources"

Step 3: Navigate to the said location C: Drive / Users / Name of Device / Name of your sample Game / Assets / RPG Maker / Codebase / Add-ons  
Step 4: From here, you need to paste the "RDEnemyBreath" folder. The folder should only contain the C# Scripts. Recall that these are your EnemyBreath.cs and RDEnemyBreath.cs.  
Step 5: This time, cut the "Resources" folder from the add-on you downloaded earlier and paste it on: Name of your sample Game / Assets / Resources  
Step 6: Load RM Unite. Separate RPG Maker and Unity Editor windows by going to RPG Maker ---> Layout ---> RPG Maker + Unity Editor  
Step 7: In the Unity Window as shown below, locate the RDEnemyBreath folder and click on it. Usually under Assets / Resources / RDEnemyBreath 
![EnemyBreath](https://github.com/Dcroix/RM-Unity/blob/main/Guide%20for%20Animated%20Enemy%20Breath.png)
Step 8: In the window that opens, you will see the "RDEnemyBreath" (this is the prefab file), click on it.  
Step 9: On the right panel, by default it will say "mono script", click on that and instead load the EnemyBreath.cs and save.  
Step 10: Now go back to RM Unite window (don't be confused, this is the other window besides the Unity Window). On the upper left, just below the logo of RPG Maker UNITE, there are many icons. Choose the icon immediately to the right of the play button.  
Step 11: Click on the icon. Check on the add-on RDEnemyBreath. From here, you will now see the enemies to have a breathing animation! 😄
