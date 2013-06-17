=== Plugin Name ===
Contributors: planetint
Tags: Twitter, Stream, Tweets, Twitter OAuth
Requires at least: 3.0.1
Tested up to: 3.5.1
Stable tag: trunk
License: GPLv2 or later
License URI: http://www.gnu.org/licenses/gpl-2.0.html

Really simple Twitter Tweets - Tweets Display plugin for your site using new OAuth api v1.1

== Description ==

A really simple twitter tweets display widget.

**Why?**

Because Twitter changed their API again. Removing version 1.0 of the API altogether and by forcing version 1.1 of the API and use of the OAuth authentication requirement.

This means Twitter users who want to display their Tweets on their website (or within an application) have to create a Twitter Application to get access to the required Keys and Tokens Twitter provides for Authentication.

The process is pretty simple really, so just follow the installation and you'll be setup in a jiffy.

== Installation ==

Installation as simple as 1,2,3 or maybe 4 because of Twitter :)

1. Upload `simple-twitter-tweets` to the `/wp-content/plugins/` directory
2. Activate the plugin through the 'Plugins' menu in WordPress
3. Add the Widget to your page (e.g. Sidebar) and update the required details
4. Note: You will need to create a Twitter Application - See below

= Creating a Twitter Application =

The Twitter Widget will never ask for your password, as it gets all your required data from the Open Authentication keys and phrases you will get by creating your application at Twitter. It also means that if you change your password, you won’t need to update any of the details of your Widget.

To find these details, go to https://dev.twitter.com/ and sign in.

Once you have logged in successfully, hover over your name in the top right corner, and click "My Applications," then "Create a New Application."

Enter a unique name (anything you want), a description (again this is just for you), and your site's URL. You can leave the Callback URL empty as it is not used for this implementation.

Yay, success - OK! You will be taken to a new screen, there's one more step then you can copy all the details into correct fields of the Widget and be on your way.

OK, click the "Create my Access Token" button. This is a shortcut to authenticate your own account with your application (so you never need use your password).

Good. Now click the Details Tab as all the information you need is presented hereso you can just copy the required information into the exact corresponding inputs fields of the Widget.

= The Widget Options =

Fill in your details, copy and past the Twitter Application details (as described below).

* You can select the Title of the Widget as you like.
* Enter your Twitter username (without the @) just the name.
* How many Tweets to display
* The time in minutes between updates (per the API requirement) this should be 5 but if the API changes you can alter it here.
* Consumer Key: Under the *OAuth settings* heading
* Consumer Secret: Under the *OAuth settings* heading
* Access Token: Under the *Your access token* heading
* Access Token Secret: Under the *Your access token* heading
* Choose if you want the @replies included or not
* Click Save

Enjoy!

== Frequently Asked Questions ==

= Where can I get help =

If you're really stuck check out the [support portal](http://planetinteractive.freshdesk.com/support/login "Support by Planet Interactive")
  

== Screenshots ==

See here [Simple Twitter Tweets](http://www.planet-interactive.co.uk/simple-twitter-tweets "by Planet Interactive")

== Changelog ==

= 1.0 =
* Initial release

== Upgrade Notice ==

= 1.0 =
This is the initial release using the new Twitter OAuth requirement to pull Tweets