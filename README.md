# Automated-Booking (Mainly for badminton court)
***

## Table of Contents
***
1. [General Info](#general-info)
2. [Built with](#built-with)
3. [Installation](#installation)
4. [Reminders](#reminders)

### General Info
***
This is the code to book the court for University of Southampton Jubilee Sport hall (mainly badminton court).
The purpose of doing this project is because Jubilee sport halls system is sucks. They require ppl to book the court at 12:00am in the mid-night and mtfk i need to sleep at that time. Thus, why not just create an automated booking script to do it for me. 
The code can be used in Windows and Linux OS System.

### Built With
***
* [![Javascript][Javascript]][Javascript-url]

### Installation
***
You can either download it in [Windows](#windows) or [Linux](#linux)

#### Windows:
***
1. Download puppeter (https://pptr.dev/) and nodejs (https://nodejs.org/en/download/).
2. Download the autobook.js and autobook.bat from the git.
3. Open the autobook.js file with editor and change your name and password.
4. Read the autobook.js file and edit the file according your preference. (all functionality are set, add // to disable the function or delete the // to activate the function)
5. Open the autobook.bat file with editor and change the path (after cd) to your file absolute path.
6. Open Task Schedular.<ol type="a">
    <li> Create basic task (set name, desciption) and click next</li>
    <li> Start daily and set the date(your date) and time at 11:58pm or 23:58 (because the badminton court will update on 12:00) and click next</li>
    <li> Select start a program and choose the autobook.bat file</li></ol>
7. You are all set! Try and run the task you scheduled and make sure it's all fine.

#### Linux:
***
1. Download puppeter and nodejs.
2. Download the autobook_Linux.js and autobook.bat from the git.
3. For the autobook_Linux.js there is only booking for badminton court. (You can try to reference autobook.js code to book other activities)
4. Open the autobook.js file with editor and change your name and password.
5. Read the autobook.js file and edit the file according your preference.
    (all functionality are set, add // to disable the function or delete the // to activate the function)
6. Open the autobook.bat file with editor and change the path (after cd) to your file absolute path.
7. Use Cron to schedule the task. (it is very easy to do, google yourself)
8. You are all set! Try and run the task you scheduled and make sure it's all fine.

### Reminders:
***
1. Jubilee Sport hall badminton court will book your court for the next week. (e.g. this monday will book next monday court) 

<!-- MARKDOWN LINKS & IMAGES -->
<!-- https://www.markdownguide.org/basic-syntax/#reference-style-links -->
[Javascript]: https://img.shields.io/badge/javascript-323330?style=for-the-badge&logo=javascript&logoColor=F0DB4F
[Javascript-url]: https://www.javascript.com/
