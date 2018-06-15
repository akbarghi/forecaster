# Forecaster
Forecaster is a simple weather forecast made from Java Swing and OpenWeatherMap API. The user could input certain city names and the app could show the detailed weather forecast data for certain days.

# Java Swing
A Java UI generated by java.swing class. It could display the data given from the user to specific UI classes needed. 

# OpenWeatherMap API
API is the acronym for Application Programming Interface, which is a software intermediary that allows two applications to talk to each other. Each time you use an app like Facebook, send an instant message, or check the weather on your phone, you’re using an API. 

When you use an application on your mobile phone, the application connects to the Internet and sends data to a server. The server then retrieves that data, interprets it, performs the necessary actions and sends it back to your phone. The application then interprets that data and presents you with the information you wanted in a readable way. This is what an API is - all of this happens via API.
--Mulesoft

OpenWeatherMap API facilitates developers so they could get for specific weather data to be processed by the server so they could give responses from the requests given. The responses usually are in JSON, XML, or many other formats.

Weather forecasts data that is available for developers are:
* Current day (free)
* 5 day per 3 hours collect (free)
* 16 day per day collect (premium)


# Package Structure
Changes may occur on process.
Current packages mainly focuses on:
* how to retrieve data from API (Class **data**)
* how to display JSON data given by the API (Class **display**)

````
lib
src
    Main
        data
            Retriever (object generator)         
        display
            MainPanel
````

# Kanban Board
Updates may occur

**to-do:**
* Retriever
* MainPanel
* (learning) JDepend
* (learning) testing JUnit

**ongoing:**
* (learning) JSON Format
* (learning) HttpUrlConnection

**done:**

