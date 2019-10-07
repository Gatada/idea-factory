# Description
Idea Factory was born out of necessity, and the frustration of the lack of plugins that did exactly what I wanted it to do. This plugin allows users to submit new ideas from the front-end, and vote on them. Currently it allows a user to vote once per idea, then locks them out. It's also currently limited to logged in users, for now.

![Image](https://s3.amazonaws.com/f.cl.ly/items/001M1a0O3I1l1o0n0S2U/Image%202014-12-09%20at%205.22.10%20PM.png)

[Demo](http://wpideafactory.com/ideas/)

## Setup Multiple Idea Factories
This fork supports multiple idea factories. It does this by letting you associate each idea factory with an existing Wordpress category. To setup multiple idea factories do as follows:

1. Create unique Wordpress categories for each idea factory instance.
2. Create a Wordpress page for each instance using the embedded idea factory code, and replace XX with the name of a category: `[idea_factory hide_submit="off" hide_votes="off" hide_voting="off" idea_category="XX"]`
3. Repeat step 2 for each idea factory you need.

I have not tried using multiple categories for a single form, so you are better off sticking to a single category for each idea factory.

---

### Features  
* AJAX powered front-end submission and voting
* Works for both logged-in and logged-out users
* 1 vote allowed per user per idea
* Emails the admin of a new submission
* Automatic setup or use anywhere with a shortcode
* Optionally set a threshold where each idea will be given a status based on total votes and emails the admin
* Extensible with hooks and actions on events
* More ideas loaded with AJAX on front-end
* Mobile friendly

---

### Installation  
##### Uploading in WordPress Dashboard    

1. Navigate to 'Add New' in the plugins dashboard  
2. Navigate to the 'Upload' area  
3. Select `idea-factoryzip` from your computer  
4. Click 'Install Now'  
5. Activate the plugin in the Plugin dashboard  

##### Using FTP  

1. Download `idea-factory.zip`  
2. Extract the `idea-factory` directory to your computer  
3. Upload the `idea-factory` directory to the `/wp-content/plugins/` directory  
4. Activate the plugin in the Plugin dashboard    

---

##### Documentation
Refer to the Wiki here in the repo for documentation on hooks, filters, and actions available.  
