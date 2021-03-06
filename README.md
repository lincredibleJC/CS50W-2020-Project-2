# Project 2

Web Programming with Python and JavaScript

## Contents

- `/static` this directory contains images and js files
    - `channel.js` contains client side logic for channel pages
- `/templates` contains the views
    - `layout.html` base layout all other layouts extend from
    - `login.html` contains the user login form
    - `index.html` shows users all available channels and allows creation of new channels
    - `channel.html` contains and shows the chat messages and the field to send messages
- `application.py` contains all the routing and logic to run this app
- `helpers.py` allows redirection to login page whenever user is not logged in

## Requirements

- [x] Display Name
    - [x] When a user visits your web application for the first time, they should be prompted to type in a display name that will eventually be associated with every message the user sends.
    - [x] If a user closes the page and returns to your app later, the display name should still be remembered.

- [x] Channel Creation
    - [x] Any user should be able to create a new channel, so long as its name doesn’t conflict with the name of an existing channel.

- [x] Channel List
    - [x] Users should be able to see a list of all current channels, and selecting one should allow the user to view the channel. We leave it to you to decide how to display such a list.

- [x] Messages View
    - [x] Once a channel is selected, the user should see any messages that have already been sent in that channel, up to a maximum of 100 messages.
    - [x] Your app should only store the 100 most recent messages per channel in server-side memory.

- [x] Sending Messages
    - [x] Once in a channel, users should be able to send text messages to others the channel.
    - [x] When a user sends a message, their display name and the timestamp of the message should be associated with the message.
    - [x] All users in the channel should then see the new message (with display name and timestamp) appear on their channel page.
    - [x] Sending and receiving messages should NOT require reloading the page.

- [x] Remembering the Channel
    - [x] If a user is on a channel page, closes the web browser window, and goes back to your web application, your application should remember what channel the user was on previously and take the user back to that channel.

- [x] Personal Touch: Add at least one additional feature to your chat application of your choosing! Feel free to be creative, but if you’re looking for ideas, possibilities include: supporting deleting one’s own messages, supporting use attachments (file uploads) as messages, or supporting private messaging between two users.
    - [x] Show the user's messages with a blue background and other user's messages with a red background.

- [x] In README.md, include a short writeup describing your project, what’s contained in each file, and (optionally) any other additional information the staff should know about your project. Also, include a description of your personal touch and what you chose to add to the project.

- [x] If you’ve added any Python packages that need to be installed in order to run your web application, be sure to add them to requirements.txt!
