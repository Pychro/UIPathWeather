# Weather Update
This was my first project using UIPath in which I created an application that takes input from the user to check the weather of a specific location. This is powered by https://www.wunderground.com where then a user can select if they want the update sent to an email.

## Table of contents
* [Technologies](#technologies)
* [Project Difficulties](#project-Difficulties)

## Technologies

* C#
* UIPath
* Wunderground

## Project Difficulties
The first problem encountered was UIPath would not recognize my browser application, OperaGX, this was resolved by using Google Chrome

The next problem encountered was after arriving on the webpage how to select the first entry in the search results, this was resolved by using a regular selector instead of a fuzzy selector that read the specific name of the entry.

The third problem encountered was when I tried to save the image directly as a file, with this I'm not sure why it didn't work but was resolved by processing it first as an image object then saving it as a file to be accessed.

The final problem encountered was sending the email, with Google it resulted in saying it didn't have authorization, with Outlook I believe it can be fixed by using an updated version of Outlook.
