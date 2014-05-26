This is a simple PHP contact form you can use in your HTML website e.t.c

It contains three files 

a) contact.html
contains a simple form which you can edit and use the CSS of your choice.

b)form-processor.php

Contains the php code and Regex to check if a valid email is set and then sends the email

c) settings.php
contains variables that MUST be set before using this php files.
	$email_to = "your@email.com" ( your email address )
	$email_subject = "form submission"; ( email subject line)
	$thankyou = "thankyou.html"; (load another thank-you page)

	Updating the question on the form in contact.html == updating question answer below
	$antispam_answer = "35"; 

Edit the files and load them in your webserver.
