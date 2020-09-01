# ProfileApp

This a very simple “My Profile Builder” application that enables a person to enter and edit their information.This assignment is composed of three activities namely:  
1.My Profile (main activity)  
2.Select Avatar  
3.Display Profile  
Part 1 (My Profile Activity): This activity contains, two EditTexts, oneImageView, and one Save button. Please implement the following functionalities:  
1. When the app loads, use a default image for the ImageView when no avatar is selected.  
2. You should be able to put first name and last name in the corresponding EditTexts.Use hints to display the hints, ‘First Name’ and ‘Last Name’.  
3. You should be able to select an avatar using another activity named, “Select Avatar”.If you click on the ImageView, it should open the Select Avatar activity using
startActivityForResult() method.
4. Once, an avatar is selected, you need to get that through onActivityResult() method, and decide the gender of the person based on the avatar selected.
5. Clicking on the Save Button should start Display My Profile activity.

Part 2 (Select Avatar Activity):  
1. Upon clicking on the avatar ImageView in the My Profile activity, it should start Select Avatar activity for result.
2. There should be two ImageViews: (i)Male avatar ImageView, (ii)Female avatar ImageView.  
3. Clicking on on of the ImageViews should finish this activity and set the result for selected avatar.  

Part 3 (Display My Profile Activity, 15 points):  

1. This activity contains an ImageView, two TextViews, and a Button.
2. It will display the avatar, and the name as it is shown in Figure 1(d and f).
3. Name should be created concatenating the first and the last names.
4. Clicking on the Edit button should finish the this activity.
