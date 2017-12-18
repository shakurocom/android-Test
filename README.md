# Test exam on iOS developer position 

## Requirements.
- iOS application fetches GitHub contributors list.
- API to fetch https://api.github.com/repos/videolan/vlc/contributors
- Returned data should be presented on 2 screens:
* Main screen should be shown when application is started. Here is mapping of UI elements to returned parameters:
  * "login" - title in each row
  * "id" - value under title
  * "avatar_url" - link to the image 
 <p align="center"> ![Main Screen](https://shakurocom.github.io/iOS-Test/MainUI.png)</p>
* Item details screen that is shown when you tap on any row - the same image and title as above.
<div style="text-align:center"><img src ="https://shakurocom.github.io/iOS-Test/DetailsUI.png" alt="Details Screen" /></div> 
* Animation between Main and Details screens. You can skip this item if its too time-consuming for you.
<p align="center"> ![Animation Between Screens](https://shakurocom.github.io/iOS-Test/Animation.gif)</p>
 

## What should to be done

Please create iOS application that will fetch GitHub contributors list and meet all requirements listed above. Application also should have pull to refresh functionality. Application should not block main thread and show progress while fetching data from the server.

## Comments

Please upload your code to github repository, there is no need in ZIP archives or smth, please send us link to you solution pubslihed on  https://github.com .

If you have any questions - please dont hesitate to ask contact who shared this test with you.
