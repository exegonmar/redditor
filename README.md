# redditor
A reddit app for udacity capstone project, the idea is that the user can browser for favorite new reddits. 

Reddit (http://reddit.com) is an entertainment and social networking site where community members can create posts and submit links in themed areas called "subreddits." The following exemplifies how you might address the task of creating a Reddit viewing app in the context of the Android Fundamentals project specifications.

###### Problem:

The user subscribes to a large number of subreddits, finds it hard to keep up with them, and has long stretches where some are neglected. He/she wants a way to get news/posts/threads from all of them equally.

###### Proposed Solution:

Design an app that allows a user to indicate a set of subreddits that they would like to follow and store. Your app should present them with a post from one of their selected subreddits. They can interact with the post (i.e. view image posts, play video posts, etc) or they can dismiss it to receive another. You should display comments (or a subset), thumbnails, and comment text and links. You should use intents to communicate with the Android apps, components, and services that you don’t want to or cannot implement. For instance, to view a link, you could use a WebView or you could send an Intent to the browser.

<<<<<<< HEAD
#### Installation

###### Reddit Api

In you gradle.property file put

###### Google Analytics

In you gradle.property

###### AdMob

In you gradle.property

### Screenshots
=======
### Installation

###### Reddit Api
In the **gradle.properties** files add the following vars with your ids **clientId** and **redirectUri**

###### Google Analytics
In the **gradle.properties** files add the following vars with your ids **gATrackingId**. Also add *google-services.json* in you *app/* direcotory
###### AdMob
In the **gradle.properties** files add the following vars with your ids **addMobAppId**

### Screenshots
![Log in with your account](imgs/log_in_you_account.png)
![Search for subs](imgs/search_for_subreddits.png)
![Share your fav links](imgs/share_your-fav_posts.png)
![Dig through commentaries](imgs/dig_thourhg_commentaries.png)
![Sub or unSub you favorite reddits](imgs/a_favorite_reddit.png)
>>>>>>> ee7bab1e27e5765b5e01739cbddc99bbdf6615e0
