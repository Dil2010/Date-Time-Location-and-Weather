
# Date-Time-Location-and-Weather

This is an app for getting data,time,and location.

#### PREREQUISITES:
- Install Node JS in your computer <a href='https://nodejs.org/en/'>HERE</a>

 
 <div style="display: inline_block"><br>
  <img align="center" alt="React Native" height="30" width="40" src="https://raw.githubusercontent.com/devicons/devicon/master/icons/react/react-original.svg">

</div>
<br>


## API Reference

#### Get all items

```http
  GET /api/items
```

| Parameter | Type     | Description                |
| :-------- | :------- | :------------------------- |
| `api_key` | `string` | **https://api.openweathermap.org/data/2.5/onecall?lat&lon&exclude=hourly,minutely&units=metric&appid**. Your API key |

#### Get item

```http
  GET /api/items/${id}
```

| Parameter | Type     | Description                       |
| :-------- | :------- | :-------------------------------- |
| `id`      | `string` | **https://api.openweathermap.org/data/2.5/onecall?lat=${latitude}&lon=${longitude}&exclude=hourly,minutely&units=metric&appid=${API_KEY}**. Id of item to fetch |




## Tech Stack

**Client:** React Native

**Server:** Not Appilicable


## Features

- On time,and On location weather-  
- Longitude and latitude
- Humidity, Pressure, Sunrise, and Sunset



## Installation

Install my-project with npm

```bash
  create-react-native-app Date-Time-Location-and-Weather
  cd React-Native
  npm install -g react-native-cli

```
    
## License

[MIT](https://choosealicense.com/licenses/mit/)


## Screenshots

![Date-Time-Location-and-Weather](/Datetimelocation.png)

![Date-Time-Location-and-Weather](/datetimelocationweather.jpg)