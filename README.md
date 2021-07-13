# grassHeap 🦗


A lot of task/to-do apps work on a timeframe of days or hours. On the other hand, gardening works in the timeframe of months. grassHeap helps you keep track of garden tasks for the month and for the specific plants in your garden. Powered by the <a href="https://github.com/Growstuff/growstuff/wiki/API-Version-0"> GrowStuff API</a>.

You can view the app at https://grassheapclient.herokuapp.com/

<span>
<img src="https://user-images.githubusercontent.com/78416008/125106980-2ac45600-e0d8-11eb-8e54-1998f7336a6d.png" width=15% border=2px solid black>

<img src="https://user-images.githubusercontent.com/78416008/125107221-6f4ff180-e0d8-11eb-8fd2-3a84b2df0631.png" width=15%>

<img src="https://user-images.githubusercontent.com/78416008/125108709-51838c00-e0da-11eb-9197-0303a51a8aeb.png" width=15%>
</span>

  
## Features 

- Displays a random gif based on results of weather API.
- Populates default tasks from database by relevant month and for your garden's plants. These tasks cannot be deleted.
- Pulls a list of plants and further details from the GrowStuff API (https://github.com/Growstuff/growstuff/wiki/API-Version-0).
- Allows you to save custom tasks to database and delete them.
- Works on desktop and mobile.

## ROADMAP
- [ ] User Auth.
- [ ] Styling.
- [ ] More detailed weather report.

## Running the App Locally

- You will need a running instance of mongoDB
- Add a .env file according to .env-example format (you will need a free API key from https://openweathermap.org/api) and from GIPHY (https://developers.giphy.com/docs/api#quick-start-guide)
- Run _npm i_ in the server and client folders.
- Run _npm start_ in client/src.
- Run _npm start_ in server.

  ( To see the full app, import some default tasks into your mongoDB grassHeap database, tasks collection using https://docs.google.com/spreadsheets/d/1XVkuqPTibBkkK4_KE3KlAV9ufz_iZ7O8Ly-iar14ybE/edit?usp=sharing )

## Deployment

- For deployment purposes, there are two additional git repos within this one (one in server and one in client) each with their own remotes.

## Contributors 
Testing, TypeScript implementation and bug fixes by <a href="https://github.com/CalimeRon">@CalimeRon</a> and <a href="https://github.com/juan-calle/">@juan-calle</a> 🐛
