# Full Stack Open - Part 0

Exercises 0.4 0.5 & 0.6

## 0.4 New note
File to review: Create New Note Diagram.png

Steps:

    - Browser send a request with the new note
    - Browser send a request to get the notes page
    - Server send the HTML code to the browser
    - Browser send a request asking for the main.css file to the server
    - Server returns the main.css file to the browser
    - Browser send a request asking for the main.js file to the server
    - Server returns the main.js file to the browser
    - Browser send a request to obtain the data.json file which contains the latest information
    - Server send data.json file to the browser
    - Browser executes the event handler that renders notes to display

## 0.5 Single Page App
File to review: Single Page App New Note.png
Steps:

    - Browser send a request to get the spa page
    - Server send the HTML code to the browser
    - Browser send a request asking for the main.css file to the server
    - Server returns the main.css file to the browser
    - Browser send a request asking for the spa.js file to the server
    - Server returns the spa.js file to the browser
    - Browser send a request to obtain the data.json file which contains the latest information
    - Server send data.json file to the browser
    - Browser executes the event handler that renders notes to display


## 0.4 New Note - Single Page App
File to review: Single Page App Initial.png

Steps:

    - Browser send a POST request with the note created in the frontend side
    - Server returns with a message telling us that a note was created
    - Browser redraw the notes


