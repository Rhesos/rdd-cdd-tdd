# cli-weather

![](http://www.noaa.gov/sites/default/files/styles/crop_394x394/public/thumbnails/image/FocusArea__Weather-02.jpg)

##What to do
Fork the project and clone it.
Run the following command in your weather directory to install all the modules needed.
You will need [Node.js](https://nodejs.org/en/) to run the application.
```node
npm install
```

##What it does
Run the following command in your weather repository. It will return the condition and the temperature of the specified city.
```node
cli.js [City] [Country]
```
This project uses :
- [Yahoo Weather API](https://developer.yahoo.com/weather/)
- [Meow](https://github.com/sindresorhus/meow)
- [Chalk](https://github.com/chalk/chalk)
