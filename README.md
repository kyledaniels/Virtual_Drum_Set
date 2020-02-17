# Virtual_Drum_Set

![image](https://user-images.githubusercontent.com/40472408/74692550-aeb13180-51b5-11ea-949a-905b5c74d6e9.png)


## :computer: Developer


*  :man_teacher:Kyle Daniels


⭐️ Star Me on GitHub — it helps!

[Virtual Drum Set](https://kyledaniels.github.io/Virtual_Drum_Set/). is an app that answers the question.What do you do if you want to play the drums, but you do not have a drum set? There is nothing easier! The virtual drum set allows users to play drums anywhere using your device.




## Table of Contents

- [Functionality](#Functionality)
    - [Authentication using GitHub OAuth 2.0 with NodeJS](#typo3-extension-repository)
    
      - The user will login to the app with thier Github login. GitHub OAuth is a simple oauth API for node.js . This API allows users to authenticate against OAUTH providers, and thus act as OAuth consumers. It also has support for OAuth Echo, which is used for communicating with 3rd party media providers such as TwitPic and yFrog. Also provides rudimentary OAuth2 support, tested against facebook, github, foursquare, google and Janrain. 
      
     - [Play Game](#typo3-extension-repository)
     
       - The user will select an Avatar then be directed to the game page to question one. Throughout the game the user will have the option to use a 50/50 hint twice and must answer fifteen questions within three minutes. If the user select the 50/50 option two of the answer choices will be removed give the user a fifty percent chance to seledt the correct answer. 
       
    - [ Game Summary](#typo3-extension-repository)
    
      - Once the user completes the game they will be directed to a Game Summary. The Game Summary will consist of the users score, number of correct answers, number of wrong answers, number of hints used and remarks stating if they are Software Engineer Ready. The game Summary is then pushed to the MongoDB database.
    
    
    
- [Packages](#Packages)
    - [Mongoose](#typo3-extension-repository)
      - Mongoose provides a straight-forward, schema-based solution to model your application data. It includes built-in type casting, validation, query building, business logic hooks and more, out of the box.
      
    - [Axios](#typo3-extension-repository)
      - Axios is a Javascript library used to make HTTP requests from node.js or XMLHttpRequests from the browser that also supports the ES6 Promise API.By using axios we remove the need to pass the results of the HTTP request to the .json() method. Axios simply returns the data object you expect straight away. Additionally, any kind of error with an HTTP request will successfully execute the .catch() block right out of the box. 