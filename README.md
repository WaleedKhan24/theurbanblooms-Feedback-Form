<p align= "center">
  <h1 align= "center">The Urban Blooms Feedback Form</h1>
</p>
<a href="https://theurbanbloomsfeedback.herokuapp.com/"><p align="center">See it Here!</p></a>

This Feedback Form is an easy way for the company to collect customers' experiences and opinions about their product and/or service. Feedback form used Python on the back-end with a publish to Heroku as an online webpage and used HTML and CSS on the front-end for UI/UX.

## What is the feedback form?
The feedback form is being used to collect customers' experiences and opinions about their product and/or service.
![Imgur](https://i.imgur.com/QCapDzu.png)

Users can select their Representative
![Imgur](https://i.imgur.com/Hh92X8m.png)

## Users are not allowed to submit the form multiple times for the same order
![Imgur](https://i.imgur.com/vxsWfVA.png)


## How was the feedback form created?

To create a fully stacked feedback form for The Urban Blooms, I used Python, Flask, SQL Alchemy, PostgreSQL, gUnicorn, emailtrap.io, HTML, CSS and Heroku. 

First, I created the database using PostgreSQL and SQL Alchemy. This allowed me to store the data from the feedback form in an organized manner. 

Next, I used Python and Flask to create the backend of the application. This included creating routes for the form submission and retrieving data from the database. 

I used Emailtrap to send an email to the business every time someone submitted feedback. This allowed me to keep track of all the feedback that was being submitted and ensure that it was being addressed in a timely manner.

Emailtrap also allowed me to customize the emails that were sent out, so I could include relevant information such as the customer's name, their feedback, and any other pertinent details. This made it easier for the business to respond quickly and efficiently to customer feedback.

Then I used HTML and CSS to create the frontend of the application. This included creating a form with input fields for users to submit their feedback. 

After that, I used gUnicorn to deploy my application on Heroku. This allowed me to make my application available online so users could access it from anywhere in the world. 

Finally, I tested my application to make sure it was working properly and that all of the data was being stored correctly in the database. Once everything was working as expected, I made my application live on Heroku so users could start submitting their feedback!
