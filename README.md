# Events

Given a user wants to keep track on a future event
When the user clicks an affordance to enter a new event in the application
Then a form should be presented to the user in which the following properties of the event can be provided

Name of event
Date of event
Location of event
Given a user has entered in all details of an event
When the user performs a gesture to save the event
Then the event should be displayed in the application in the Events component

Given a user has entered in 1, or more, events
When the event component is updated
Then the next event on the agenda should have bold text
And it should be slightly larger in size
And it should have a non-white, and non-offensive background color

Given a user wants to change the details of an event
When the user performs a gesture to edit an event
Then the user should be presented with a form that has the event details pre-filled into the fields
And there should be an affordance to save the new details

## Getting Started

git clone
git checkout mr-creating-events 

### Prerequisites

What things you need to install the software and how to install them

cd into src/lib and then run grunt


## Running the tests

Project should create, delete and edit


## Authors

* **Mary Remo** 
