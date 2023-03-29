# Weather-App

A weather app is an application that provides information about the current weather conditions, forecasts, and other related information for a specific location or multiple locations. This information is usually obtained from weather data providers and can include data such as temperature, humidity, wind speed and direction, air pressure, and precipitation. Users can use weather apps to plan their activities, dress appropriately, and make informed decisions about travel and other outdoor activities.

## Instructions to run the game

* Open the Github repository where the game code is hosted.

* Click on the green "Code" button and then select "Download ZIP" to download the code as a ZIP file.

* Extract the ZIP file to a folder on your computer.

* Open a command prompt or terminal window and navigate to the folder where you extracted the code.

* Type ```python weather.py``` and press Enter to start the game.

* Follow the prompts to play the game.

Functionality of the code

* Import the required libraries - ```BeautifulSoup``` and ```requests```.
* Define a user agent to be used in the header of the requests module to make it look like it's coming from a browser and not a bot.
* Define a function called ```'weather'``` which takes in the city name as an argument.
* The city name is then replaced with a ```'+'``` sign wherever there is a space to be used in the search query.
* Send a get request to the Google search page using the city name in the search query and the headers specified earlier.
* Parse the HTML response using BeautifulSoup and extract the location, time, weather information and temperature using their respective HTML element ids.
* Print the extracted information on the console in a readable format.
* Ask the user to enter the city name for which the weather information needs to be retrieved.
* Append the word 'weather' to the city name to be used in the search query.
* Call the ```'weather'``` function with the city name passed as the argument.
