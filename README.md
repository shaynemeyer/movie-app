# Movie-App
A TDD first approach to building an Angular 1.4.4 app using the [Open Movie Database API](http://omdbapi.com/).

## Running the app
You must have nodejs installed to run this app. If not, start at [nodejs.org](https://nodejs.org/en/).

### Install modules
``` 
npm install
```

### Run the app
```
node index.js
```

### Run the tests
``` 
npm test
```

## Visual Studio Code Setup
For this project I am using Visual Studio Code
To add intellisense for Angular and Jasmine. First ensure that you have [typings](https://github.com/typings/typings) installed.

More on setting up intellisense in Visual Studio Code can be found [in an excellent post by Tony Sneed](https://blog.tonysneed.com/2016/02/27/visual-studio-code-typescript-part-2/).

### install globally
``` 
npm install typings -g
```

### init typings
```
typings init
```

### add definitions
```
typings install jasmine --save-dev --ambient
```