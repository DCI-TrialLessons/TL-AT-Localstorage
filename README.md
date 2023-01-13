# Localstorage

Your task is to create a fake login system using LocalStorage! When the page opens, check if a username is saved to localstorage. If a username is not found in storage, show a "Login" form containing a username input and login button. When this form is submitted, save the username and a counter variable starting from 1 into localstorage.

If a username is already stored, show `Welcome back {username}, this is visit number {couter}]!` and a "Logout" button. Every time the page is loaded and a username is already logged in, inrement the counter. When the "Logout" is clicked, show a message with "Thank you, come again!".

Show all messages in the DOM, do not use `alert()`.
