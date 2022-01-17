# Story Tracker Project
*This web app is a simple story tracker for authors to use to create compelling narratives by linking events together and tracking character status. The focus of the app is to allow the user to keep up with continuity.*
On a technical note - this project will also be used to compare the developer experience between different frontend technologies as the integrate with the .net framework. (Current plan is C# and React frontend).

## Project Overview
* For personal use only.
* Users can create their own stories.
* Stories consists of Events and Characters.
	* Stories have a time unit, this is relevant to measuring out time distance between events
	* Story description
	* Story title
* Users can create multiple stories
* Users can create events
* Users can create characters
* Users can create locations
	* locations have name and description.
* Events Organized by time units of the story (years, days, months, etc).
	* Events can have related images meant to depict the tone of the event
	* Events have descriptions
	* Events have Related Characters
* Characters have names, descriptions and abilities
	* Can see character relationships with other characters
	* Can see which events a character is involved in.
	* Can see the status of the character (Dead, alive, incapcitated, etc)

## Project Structure
### Backend
The backend of this project will be done with the .Net framework creating an API for accessing and manipulating data in regards to created characters and recorded events in the narrative.

### .Net Frontend
The directory the contains C# code and organization of a C# frontend.

### React Frontend
The directory containing related JS react code and set up for the react frontend.

## Project Updates
* January 16th, 2022 - Project Start