=== bbPress Moderation ===
Contributors: iandstanley, ianhaycox
Donate link: http://CodeIncubator.co.uk/donate.html
Tags: bbPress, moderation, approve, moderate, approval, spam, bbpress moderation
Requires at least: 3.3
Tested up to: 3.6
Stable tag: 1.8.3

Add the ability to moderate and approve new topics and replies in the bbPress V2.0 plugin

== Description ==

To help reduce spam in bbPress forums, this plugin will change the status of new topics and
replies to 'pending'. Any pending topics/replies will be shown as 'Awaiting Moderation' until
the administrator approves publishes them.

**Features**

* Blog administrator can be notified of new topics and replies requiring moderation.
* Anonymous postings can always be marked for moderation.
* Registered users can post without moderation after the first topic/reply is approved.
* A bubble counter is shown on the Topics and Replies menu to indicate the number of posts awaiting moderation.
* Pending topics/replies are styled to give the submitting user a 'hint' that the new topic/reply is pending

**Languages**

* English
* French
* German | Thanks - daveshine (David Decker)
* Turkish | Thanks Mustafa Çoban
* Spanish | Thanks Yo
* Russian | Thanks Dinar Qurbanov
* The .pot file is shipped for other translations - [send them in email iandstanley at gmail dot com]

If you do download this plugin please come back and rate it. For any rating less than 5 stars
I would love to hear your feedback to help improve the plugin. Usability issues, bugs, enhancements
and any other comments welcome to make this plugin better. [Contact](http://ianhaycox.com/contact)

**More**

See my [other plugins](http://codeincubator.co.uk)

== Installation ==

To install the plugin complete the following steps

1. Unzip the zip-file and upload the content to your Wordpress Plugin directory. Usually `/wp-content/plugins`
2. Activate the plugin via the Admin plugin page.

== Usage ==

Once activated the bbPressModeration plugin will, depending on the settings, prevent the publishing
of topics and replies until approved by the site administrator. 

Registered users who have previously had a topic/reply approved do not need to go through the moderation
process for subsequent posts.

If a topic/reply is marked for moderation then it is shown in the bbPress Topic or Reply menu as Pending.
To approve the post, edit and click Publish.

Plugin has a settings page that changes the default behaviour e.g. to hide pending posts 

== Screenshots ==

1. Settings page
2. Pending topic awaiting moderation

== Upgrade Notice ==

Initial version

== Changelog ==

= 1.8.5 =
* bbPress 2.5.3 compatibility
* Added support for Russian- Thanks Dinar Qurbanov

= 1.8.4 = 
* Standardize certain parts of code according to WordPress coding standards, e.g. Yoda conditions

= 1.8.3 =
* Anonymous Moderation now split into two settings (topics and replies can be managed separately)
* Due to new settings page please check the settings you have are correct for your purposes. Set and Save to update them if they are wrong.

= 1.8.2 = 
* Fixed SPAM from appearing (Pending status even if it's spam) 

= 1.8.1 = 
* Altered some internal debugging code

= 1.8 =
* Fix for DB prefix taking into account those wp sites that use a database prefix -- thanks to mgropel
* Hide pending posts from Forum (still visible from admin screen) - turn off display in plugin options page
* Tested on WordPress v3.6

= 1.7 - 15th May 2013 =
* Added Turkish language - Thanks Mustafa Çoban
* Added Spanish language - Thanks Yo
		
= 1.6 - 18th Apr 2013 =
* Fix bug for changes in bbPress 2.3 - http://bbpress.trac.wordpress.org/ticket/2207
* Added Macedonian language files.

= 1.5 - 11th Dec 2012 =
* Fix bug - http://wordpress.org/support/topic/email-notifications-for-subscribed-topics-not-working

= 1.4 - 6th Nov 2012 =
* Add ability to mark topics/replies as spam - Thanks Ipstenu (Mika Epstein)
* Add username/anonymous to admin notification message
* Attempt to make new moderated topic/reply more visible to user when pending moderation

= 1.3 - 11th Oct 2012 =
* Bug fix for BuddyPress activity stream - http://bbpress.trac.wordpress.org/ticket/1915
* Return correct site URL for email notification

= 1.2 - 18th Feb 2012 =
* Don't moderate users with moderate capability
* Add topic/reply content to notification email
* Users with moderate capability can view pending content

= 1.1 - 12th Jan 2012 =
* Move languages to /languages folder
* Added German translation - Thanks - daveshine (David Decker)
* Bug fix to prevent 404 pages after submitting new pending topic 
		
= 1.0 - 9th Jan 2012 =
* Initial Version

== Frequently Asked Questions ==
= Can I change the way moderation works ? =

Yes, see the plugin settings page.

= How do I approve a topic or reply ? =

Visit the bbPress Topics or Replies menu and edit each pending post then click Publish. 

To approve multiple topics or replies you can use the bulk actions option. Click the pending link,
select all topics or replies then Bulk Actions->Edit and change the status to Publish