# Dream Design Document Template
![Start Screen Mockup](/images/dd_start-screen.png)
![Display page Mockup](/images/dd_summary.png)

## Application Description
>This app is a mobile app and can be used by both touch and voice control. It uses the Yahoo Weather API and has additional features that the user might want after being informed about the weather description they were looking for. The program can be triggered by Siri or other voice recognition systems imbedded in user's device. Some of the example keywords or triggers would be 'Open Yahoo Weathers', 'Tell me today's Weather', 'How cold is it today', or 'Is San Diego hot?'.

>Then the app opens up on the device and it would look like the mockup image of the starting page(left). The layered circles in the center will vibrate or move as it answers user's question. If the user clicks the before button on the start page, he or she can make the app to repeat what it said before. Likewise, if the next button is pressed after one or more before button is pressed it informs the user about the information in forward-history. For the users using the voice control, they can just say repeat or sentences similar to that and the app would repeat itself. It will also display what it said in text on the bottom for user's who are not using sound or people with disabilities regarding hearing.

>When the app is given a specific question, such as a place or a date, it will tell the user maximum and minimum temperature of that day at that place. If the user does not specify location or date, the app will answer with default data, weather on user's current location for that day. The unit for temperature and wind will differ depending on the location that the user is in and the user can easily ask the app to change the units interchangeably.

>When the user clicks on the icon with four squares, which represents display, it will show the weathers for seven days in list starting from today's weather (right). It will briefly display the day, date, and the maximum temperature. The user can scroll down for the rest of the day if it does not fit on his or her screen (just like how the mockup only shows 5 days). When the user clicks on one of the days, it will move onto another screen that has more specific information about that day's weather including: wind, atmosphere, sunset, astronomy, longitude, and etc.

>The user also has access to additional information related to weather beyond temperature, such as latitude and longitude, sunset and sunrise time, and data on wind and atmosphere. Furthermore, the user can use the linked google map API to look at real time street-view and pictures of how the weather looks like outside for today. In addition to that, because the Yahoo API gives a brief text description of the weather, such as 'mostly cloudy' or 'sunny', when the users click the clothes icon the app can open up a browser searching images for 'warm outfits', 'summer fashion', and 'rainy weather looks'. This will allow the app to satisfy the users who wanted to know the weather to choose their outfit or wanted to know what the outside environment is like.


### Web Service(s) Used
>The web services used to support my application are the Yahoo Weather API and the Google Maps API. Yahoo Weather API gave me access to various information that forms the bases of my app. Such information may include: temperature in different units, wind data, atmosphere(humidity, visibility, and pressure), sunset and sunrise times, longitude and latitude and much more. More data that can be accessed through this API and how you can call it is described in the yahoo documentation which is linked below. Google Map API is a side function that allows the user to see pictures of the current weather for whichever location he or she searched. Details of Google Map API can be found in the link below as well.

* [Yahoo Weather API](https://developer.yahoo.com/weather/)
* [Yahoo Weather API Documentation](https://developer.yahoo.com/weather/documentation.html)
* [Google Map API](https://developers.google.com/maps/web-services/)

## Top-Level Design/Layout
> Provide an overview of your user interface. Annotated mockups work very well here, with accompanying text describing, at a high level, the various components of your design.

#Annotated mockup#
>The start page contains a circle that changes its size as it spits out verbalized texts so it looks like it is talking. It has five icons that can be tapped below: left arrow, four squares, map, shirt, and right arrow. The arrow keys can be used for going back or ahead a step just like how you can go back and forth when using a browser. This is so that the users don't have to repeat the same action to get the information they already got earlier. The four squares are usually used for gallery in many devices, and the icon itself seems remind the users of divided sections. This is the display button for application, where the user can see the summary of the current week's weather in a list. Clicking the map button displays real-time pictures and a street-view of the location at current day and time. The shirt icon takes the user to a browser on user's device, searching up outfits and showing images of it, depending on the weather.

> For the display page where it has a summary of the week's weather, the user can click on one of the sections or the days in the list to see more information. This new page will contain detailed data about the day the user clicked including wind, atmosphere, temperature by time, and etc. The user can scroll down to see more information here as well.

## Usage Scenarios
> A usage scenario is a mini-story that highlights how a user would accomplish a certain task in your dream design. Provide at least two. Make sure to provide the following information per scenario: (a) the task that the user will perform, (b) the relevant user interface elements for performing this task, and (c) a brief narrative on how the user would perform this task with those user interface elements. Mock up, animate, or annotate your scenarios liberally.

### Asking for an outfit for today's weather
> The user wakes up a little late in the morning and she does not have time to worry about what to wear today. She simply activates her device by saying 'Ok Siri' or 'Ok Yahoo Weather' and asks what she wants to know: 'what should I wear today?'. While doing this, she can multitask and make her breakfast or pack her bag. This saves time and makes her morning routine efficient. The benefits of this is that she can work on something else instead of looking things up herself and waiting for it to load. Moreover, she gets to know what outfit would be the most appropriate for today's weather, since the search results will be based on that day's weather in short text (ex. partly cloudy, sunny, possible rain). In addition, the interface for this is simple as it can be, to just ask the app for the information needed. If done by hand manually instead of using the voice control, one can click the shirt icon and it will give he or she recommended clothes for that day by default.

### Looking up today's sunset time
> The user is on a family trip at a foreign country and wants to spend time at the beach that afternoon. He does not know what the whether is like in that country, nor when the sunset is. He opens Yahoo Weather app, and clicks on the display button (four square icon). Because he is looking for a more specific data than just the temperature of the day, he clicks on the first box, or a section with today's day and date. It has the whole week's weather summary with current day's information on the very top, so it will be easy for the user to find the box or button for today. When the user clicks today's div, which is the first from the top, he can get detailed information about today. He sets his location to the beach he wants to visit by typing the name of it on the search bar and scrolls down for the sunset time. 

## Design Rationale
> State why your design is the way it is: relevant priorities, mental models, interaction design concepts, guidelines, principles, theories, etc. Cite relevant references as needed.

## Usability Metric Forecast
> If implemented then tested, what would be your design’s strong metrics? Weak metrics? Explain your choices.

## References
> Cite formally, as you would with any other research paper.
