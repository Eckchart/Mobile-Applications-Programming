# Garden Manager

## Description
This mobile application is dedicated to those who want to keep track of and manage the plants in their garden.

The user will be able to add a new plant, edit its specific details, remove it if it is no longer healthy enough to continue growing and get all its details.

There will be a main screen where the user will see all the plants in their garden, and then, by the press of a button, a secondary screen for each individual plant displaying its specific details.

In this secondary screen, the user will have the possibility to edit the details of or delete the selected plant.

## Domain Details
The fields for the `Plant` entity:
- `id`: automatically assigned to each plant;
- `name`: the name of the plant;
- `species`: the species of the plant;
- `planting_date`: the date on which the plant was planted;
- `care_instructions`: instructions for how to keep the plant healthy all the time.

## CRUD Operations
- `create`: add a new plant to the garden;
- `read`: view the details of each plant currently in the garden;
- `update`: edit the details of a plant in the garden;
- `delete`: remove a plant from the garden.

## Persistence Details
The operations `create`, `update`, `delete` will be persisted on the local database and on the server.

## Offline Handling
When the device is offline:
- on `create`: the input will be saved locally and will be synced with the server when back online;
- on `read`: the local data will be displayed, with a note that the server is down;
- on `update`: a message will be shown that the operation is unavailable;
- on `delete`: a message will be shown that the operation is unavailable.

## App Mockup
#### Main Screen
![image](https://github.com/Eckchart/Mobile-Applications-Programming/blob/main/App%20Design/Main%20Screen.png)

#### Edit Screen
![image](https://github.com/Eckchart/Mobile-Applications-Programming/blob/main/App%20Design/Secondary%20Screen.png)
