# basf_swd_test
This repository is meant for BASF candidate tests


<img src="./statics/basf.png?raw=true" alt="logo" width="200px"/>

# I+D Developer Test

## Motivation - PWA

__PWA__ stands for Progressive Web App. This is an app built from the web technologies we all know,
like HTML, CSS, and JavaScript, but with a feel and functionality that rivals an actual native app. 
Thanks to a couple of smart additions, you can turn almost any website into a progressive web app. 
This means that you can build a PWA rather quickly, in regard to a native app that’s pretty difficult to develop. 
Plus, you can offer all the features of native apps, like push notifications, offline support, and much more.

PWAs are gaining popularity. Many big sites are PWAs, like [Starbucks](Starbucks.com), 
[Pinterest](Pinterest.com), [Washingtonpost](Washingtonpost.com) and [Uber](Uber.com) 
are actually installable on your home screen and offer a comparable experience to their native apps.

[Keep reading](https://yoast.com/what-is-a-progressive-web-app-pwa/)


## Objective

Develop a small PWA. You'll have to implement the Frontend and Backend, both based on any other technology or framework that you __haven't__ used on your daily work.
It is of great interest to develop two main PWAs' features: PUSH notifications and offline mode.


## Solution

### PUSH notifications:

The solution requires two views, Frontoffice & Backoffice.
When the user accesses the FrontOffice, the site would request permission to show notifications. 
Once accepted it informs the backend about the subscription.
On the Backoffice side, the Admin (an arbitrary user), would be able to list the subscribed users.
After that, he/she can notify with a push message to a selected user.

### Offline mode:
The PWA have to continue working when the network connection goes out.
In this point three elements should be set and developed: 
- __Assets:__ every static resource has to be cached in local storage, in order to keep the look and feel.
- __Server Data:__ the PWA must cache data received form the sever, a simple endpoint is needed to get dummy data.
- __Async sync:__ the PWA should store any new resource created while in the offline mode, waiting for the connection to synchronize with the server (this is a plus).

To achieve this, It's recommended to use the Frontoffice view and make a shopping list app:
- the user could use a nickname to send data
- the new user will start with an empty list
- the user could query his list to the server
- the user could add new items to his list.

This is a suggestion, but you are free to develop any app to complete the Offline Mode, (creativity is a plus).

## Expected delivery
You can deploy the solution in any cloud provider using a free user account (this is recommended) or send the application and clear instructions on how to install (including prerequisites) and run locally the application in a personal computer.
Clear look&feel will be positively valuated, clean code is mandatory.
Finally, it is required to push your code to github in the following public project: [https://github.com/faller222/basf_test](https://github.com/faller222/basf_test)
 
 
If you have any doubt regarding the exercise, please email to [pablo.fraga@basf.com](mailto:pablo.fraga@basf.com) or [german.faller@basf.com](mailto:german.faller@basf.com) 
