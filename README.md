# Tourism of India website:

## Problem Statement:

Tourism without proper guideline can put the life of tourist in danger. So, a guide is required for guiding tourist during their journey. Internet and GPS solve this problem by providing free applications that provide all required information to tourist. Technology and software used in the tourism industry of India are playing a vital role in the tourism and hospitality industry of India.

## Features:

* Our website is divided into 4 segments - North, South, East, West.
* It displays information of restaurants after giving the city id(from another API) using an API.
* It displays the current weather and location of the cities mentioned above.
* It displays macros of the food we enter.
* It displays the Airline data after we enter its iata code.
* It shows the map of a particular location.

## Technologies used:

* HTML5
* CSS3
* JavaScript
* AJAX

## APIS End Points:

* API to fetch Airline data => https://iata-and-icao-codes.p.rapidapi.com/airline?iata_code=IX
* API to fetch weather => http://api.openweathermap.org/data/2.5/weather?q=chandigarh&APPID=20a9cfdc85952bc622119bf76f5be8a6 
* API to fetch restaurant data => https://developers.zomato.com/api/v2.1/search?entity_id=12&entity_type=city&count=5&radius=1000
* API to display a city id => https://developers.zomato.com/api/v2.1/cities?q=chandigarh
* API to display macros of a food => https://food-calorie-data-search.p.rapidapi.com/api/search?keyword=apple
