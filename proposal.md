## Project Description
This application offers the user the ability to search local organizations in need of donated items.

## Problem Statement
Many of us have items to donate, but sometimes it is difficult to allocate where they should and rather than give an organization something they do not need, this app aims to solve that problem by allowing them to specifically post what items they are in need of.

## Solution
By having the organization upload specific items to the Realm database, it allows the user to look for specific items that they have it at home. If a user has a surplus of blankets for instance, they are able to look and select institutions in the database and see if they are need of that specific item. By allowing the organizations to post what they need, it offers user more insight to a particular want as opposed to donating items just to get rid of them. My aim is help people out with specific needs.

## User Experience
The user experience is broken up into two different stories. First, as the institution, they are able to create a profile for their organization. From that point, they are then able to create items and have inserted into the database. The items are held in the databse in alphabetical order.
The experience as the layman allows them to access the app, and then go and select any of the available organizations. From that point, they will be able to see the seeded items that the the organization had inserted. The list will be scrollable for the user to look up and down to see if there is anything that they may have. In addition, the user will able to search for a particular item by typing into the search bar.

## Technology
The front end will be developed in Swift. Cocopods such as SwipeCellKit will be used to facilitate the ability of being able to swipe to delete an item once it as been completed. Chameleon cocopod will also be used to help and adjust the color layout of the app.
For the back end, I will be using Realm to seed and migrate the data that is inserted into the cells. The cocopods of Realm and RealmSwift will be used. The data will originally be persisted through coredata and a local plist and then sent off to Realm where it will be hosted.
