# Dream Design Document Template
Copy this file to a new one called _dream-design.md_. Populate the sections as indicated. Illustrate your ideas as needed, with diagrams, screen mockups, etc. Don’t forget to cite references—this is still a piece of formal writing.

## Application Description
> A description of the application for which you have created the design, focusing on any particular usability issues that you’d like to address. There is no restriction on the platform of the application; you can make it whatever you want it to be.

This app is a mobile app and can be used by both touch and voice control. It uses the Yahoo Weather API and has additional features that the user might want after being informed the weather description they were looking for. The program can be triggered by Siri or other voice recognition systems imbedded in user's device. Some of the example keywords or triggers would be 'Open Yahoo Weathers', 'Tell me today's Weather', 'How cold is it today', or 'Is San Diego hot?'.

Then the app opens up on the device and it would look like the mockup image of the starting page(left). The layered circles in the center will vibrate or move as it answers user's question. If the user clicks the before button on the start page, he or she can make the app to repeat what it said before. Likewise, if the next button is pressed after one or more before button is pressed it informs the user about the information in forward-history. For the users using the voice control, they can just say repeat or sentences similar to that and the app would repeat itself. It will also display what it said in text on the bottom for user's who are not using sound or people with disabilities regarding hearing.

When the app is given a specific question, such as a place or a date, it will tell the user maximum and minimum temperature of that day at that place. If the user does not specify location or date, the app will answer with default data, weather on user's current location for that day. The unit for temperature and wind will differ depending on the location that the user is in and the user can easily ask the app to change the units interchangeably.

When the user clicks on the icon with four squares, which represents display, it will show the weathers for seven days in list starting from today's weather (right). It will briefly display the day, date, and the maximum temperature. The user can scroll down for the rest of the day if it does not fit on his or her screen (just like how the mockup only shows 5 days). When the user clicks on one of the days, it will move onto another screen that has more specific information about that day's weather including: wind, atmosphere, sunset, astronomy, longitude, and etc.

The user also has access to additional information related to weather beyond temperature, such as latitude and longitude, sunset and sunrise time, and data on wind and atmosphere. Furthermore, the user can use the linked google map API to look at real time street-view and pictures of how the weather looks like outside for today. In addition to that, because the Yahoo API gives a brief text description of the weather, such as 'mostly cloudy' or 'sunny', when the users click the clothes icon the app can open up a browser searching images for 'warm outfits', 'summer fashion', and 'rainy weather looks'. This will allow the app to satisfy the users who wanted to know the weather to choose their outfit or wanted to know what the outside environment is like.


### Web Service(s) Used
> Briefly list and describe the web service(s) that will support the functionality of your application. Don’t assume that the reader knows about the service(s) beforehand. Describe the functionality you intend to use, and list the API calls that will support your dream design. Feel free to provide web links to relevant online documentation.

The web services used to support my application are the Yahoo Weather API and the Google Maps API. Yahoo Weather API gave me access to various information that forms the bases of my app. Such information may include: temperature in different units, wind data, atmosphere(humidity, visibility, and pressure), sunset and sunrise times, longitude and latitude and much more. More data that can be accessed through this API and how you can call it is described in the yahoo documentation which is linked below. Google Map API is a side function that allows the user to see pictures of the current weather for whichever location he or she searched. Details about Google Map API can be found in the link below as well.

https://developer.yahoo.com/weather/
https://developer.yahoo.com/weather/documentation.html
https://developers.google.com/maps/web-services/

## Top-Level Design/Layout
> Provide an overview of your user interface. Annotated mockups work very well here, with accompanying text describing, at a high level, the various components of your design.

## Usage Scenarios
> A usage scenario is a mini-story that highlights how a user would accomplish a certain task in your dream design. Provide at least two. Make sure to provide the following information per scenario: (a) the task that the user will perform, (b) the relevant user interface elements for performing this task, and (c) a brief narrative on how the user would perform this task with those user interface elements. Mock up, animate, or annotate your scenarios liberally.

### Usage Scenario 1
> Replace the title with an actual description of the scenario, e.g., “Adding a Song to a Playlist.”

### Usage Scenario 2
> Ditto with the title.

## Design Rationale
> State why your design is the way it is: relevant priorities, mental models, interaction design concepts, guidelines, principles, theories, etc. Cite relevant references as needed.

## Usability Metric Forecast
> If implemented then tested, what would be your design’s strong metrics? Weak metrics? Explain your choices.

## References
> Cite formally, as you would with any other research paper.
