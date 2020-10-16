
## Chapter 4 - Building a Social Website

In this part,I have completed the following topics:

* Creating functionality for the user to log in, log out, reset the password
* Extending the user model with a custom profile model

Below is the list of my experiences -

* This is important to add ''account.apps.AccountConfig added to settings.py in the INSTALLED_APP list. I got an error, and took me some time to figure out that.
* Django provides powerful prebuilt views to handle login, logout, password change views (password reset). 
* I didn't set up an SMTP server, hence I couldn't follow all the steps for reset password using email.
* User registration page became easy due to Django provided views.



## Chapter 5 - Sharing Content on Your Website

In this part, I have completed the following topics:

* Sharing the content from other sites on your website.
* It leverages the AJAX feature along with JQuery. I never used AJAX before, but it didn't look hard while following this in the exercise. This is one of the features that I will use in my project.

Below is the list of my experiences -

* While importing certifi, I got an error. While trying multiple times, I realized that the syntax was wrong. It should be pip install --upgrade certifi. I was trying  certify.


## Chapter 6 - Tracking User Actions

In this part, I have completed the following topics:

* Building a follow system and create a user activity stream.
* Create an intermediary model for the relationship 
* I didn't follow the book's Redis sections as this wasn't available on my computer.
