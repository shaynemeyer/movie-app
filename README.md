# Movie-App
A TDD first approach to building an Angular 1.4.4 app using the [Open Movie Database API](http://omdbapi.com/).


## Visual Studio Code Setup
For this project I am using Visual Studio Code
To add intellisense for Angular and Jasmine. First ensure that you have [TSD - TypeScript Definition Manager](http://definitelytyped.org/tsd/) installed.

More on setting up intellisense in Visual Studio Code can be found [in an excellent post by John Papa](http://johnpapa.net/intellisense-witha-visual-studio-code/).

### install globally
``` 
npm install tsd -g
```

### add definitions
```
tsd query -r -o -a install angular jquery jasmine
```