Chromeos_url_app_maker
======================

Creates chrome apps that launch urls for ChromeOS

Step 1: Hold Ctrl+Shift+t to open up a crosh shell  
Step 2: Type shell to open up a shell  
Step 3: Navigate to your downloads directory with "cd ~/Downloads"  
Step 4: Type "bash make_app app_name app_icon app_url" where app_name is the name you want for your app, app_icon is an icon for the app lcoated in your ~/Downloads, and app_url is the url you want the app to create (make sure it includes http:// , https://, etc)  
Ex: bash facebook facebook.png https://www.facebook.com  
  
(Note: A directory will be created with the app name you've chosen. This will be the app. Ensure that a directory with this name is not already created. If this happens, just navigate to that directory, and move your app icon picture back to the downloads folder.)  
  
Step 5: Open up Chrome  
Step 6: Navigate to your extensions(one way is to enter chrome://extensions/ in the address bar)  
Step 7a: Check the Developer Mode box if not already done  
Step 7b: Choose "Load unpacked extensions" and choose the newly created app folder  
You've now created and loaded your chrome app!
