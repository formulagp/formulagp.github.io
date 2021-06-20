---
title: Jay's ePortfolio
---

# Code Review
### Reviewing previous projects and discovering ways to enhance them
[![IMAGE ALT TEXT HERE](https://img.youtube.com/vi/vrjaMnJcEUM/0.jpg)](https://www.youtube.com/watch?v=vrjaMnJcEUM&t=1 "Code Review")

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;The video above is a code review, performed by me on three seperate projects that were completed throughout my courses at Southern New Hampshire University. This initial review was designed to find any flaws in these previous assignments and use the different skills that I have acquired throughout my time at SNHU to enhance each project. The results of this code review have led to updated versions of each project, which are linked and described below.


# Pi Weather Station
### Software Design and Engineering

![piWeatherGif](assets/images/piWeather.gif)

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;The Pi Weather Station project is a weather monitoring program created with a Raspberry Pi 4 computer, the Python programming language, and a GrovePi hardware kit purchased from Dexter Industries. It's purpose is to continuously collect temperature and humidity data from a sensor and output all the gathered information to a JSON file once the program is stopped. The purpose of the JSON file is for data manipulation, which the user can use to create charts, trends, reports, or any other means of displaying the data. There are LED's connected as well that show the user exactly what the current weather conditions are based on what colors are illuminated at the time. The Pi Weather Station will even shutdown at night, once the attached light sensor no longer detects sunlight and meets a pre-determined threshold limit.

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;As an opportunity to showcase my skills and abilities in software design and engineering, the Pi Weather Program has since been enhanced and upgraded to version [1.1.0]. With this update comes two new features that have been added in the form of new Python functions. These functions give the machine a startup and shutdown sequence, so now when the Pi Weather Station is booted up a startup sequence runs which displays a welcome message to the user and flashes the green LED two times, indicating it is in startup mode. When the program is shut-down, the shut-down sequence runs and blinks the red LED twice while displaying a shut-down message. The LCD screen was also included in this update, which now will display a startup and shutdown message to the user while running the function. To consider this project complete, variables were renamed to better reflect their purpose in the code, such as the variable 'blue' getting changed to 'tempOutputPort' or the variable 'grLed' getting changed to 'greenLED'. These software design changes may seem small, but will aid in future debugging and updates.

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; The original scenario for this assignment was to continuously build upon features in each sprint for a stakeholder who's requirements would constantly change. As a developer, it was my job to produce a product that the client was happy with, which would eventually become the Pi Weather Station. Adding the new features to the program was fairly straight forward, but required a thorough understanding of how Python defines functions, performs loops, and interacts with the GrovePi hardware. That is why this particular project was chosen to enhance and use for my comprehension of software design. The code performs every task desgined as intended, such as gathering data from the correct port and outputting it to the JSON file or lighting the correct LED for the correct amount of time. The enhancements added in v[1.1.0] attest to this comprehension and leads to a stronger weather station program. Coding best practices were used and I believe it shows through the completeness of this project.

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Below is a link to the GitHub repository that contains the newly enhanced program along with the original for comparison. 

[Pi Weather Station Repository](https://github.com/formulagp/Pi-Weather-Station)

# Upgraded Vector Sorting
### Algorithm Design / Structure

![UpgradedVectorSortGif](assets/images/enhancedVectorSort.gif)

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;The second project presented here is a program that was specifically created to show how some of the more commonly used algorithms in the computer science industry are created and used. This program is written in C++ and begins by presenting the user with a menu of options including load bids, display bids, perform selection sort on bids, perform upgraded selection sort on bids, perform quicksort on bids, or exit the program. In the original program, v[1.0.0], the only algorithms available for use were the selection sort and the quick sort function. In v[1.1.0], the upgraded selection sort function was added. When any one is chosen, the algorithm will run on the loaded data and sort each element by name. The program will then display the time it took to successfully sort the data after running, given in clock ticks and seconds. This allows the user to actually see how the algorithms compare in performance to accomplish the same task. To verify the sorts were completed successfully, the user then has the ability to choose display bids again and see that the elements are now in a sorted order.

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;This project was chosen to display my comprehension of algorithm design and structures, as it's sole purpose is strictly to run created algorithms on a set a data that is given. This also 

[Upgraded Selection Sort](https://github.com/formulagp/Upgraded-Selection-Sort)

# MongoDB Database

![MongoDBGif](assets/images/MongoDB.gif)

Finally, the MongoDB Database project shown above presents an excellent opportunity to display my skills working with databases. This particular project utilizes the NoSQL database program MongoDB along with the Python programming language to perform CRUD operations on provided databases, creating a powerful stack program. The program allows the user to select and connect to one of two databases, which can be imported into MongoDB from the repository link below. Once connected, a second menu allows the user to either create, read, update, or delete data in the current database of their choice. Once finished, the user may disconnect and exit the database, where they are allowed to select another database to connect to. Again, the user is able to perform CRUD operations or disconnect from the database. Once finished, the user may select the exit option to properly shutdown the prgoram. To try the program yourself, please take a look at the project repository linked below!

[MongoDB Database](https://github.com/formulagp/MongoDB-Database)

[About me](about.md)
