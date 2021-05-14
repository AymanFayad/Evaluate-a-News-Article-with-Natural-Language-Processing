# Project Instructions

This repo is NPL  starter Project. 
Install and configure Webpack just as we did in the course. Feel free to refer to the course repo as you build this one, and remember to make frequent commits and to create and merge branches as necessary!

we have done below configurations .
- Sass styles
- Webpack Loaders and Plugins
- Creating layouts and page design
- Service workers
- Using APIs and creating requests to external urls



## Getting started

Remember that once you clone, you will still need to install everything:

`cd` into your new folder and run:
- `npm install`

## Setting up the API

we used For the MeaningCloud API to get aPI KEY TO HELP QUICK NPL PROCESS .

### Step 4: Environment Variables
Next we need to declare our API keys, which will look something like this:
WE CREATED .ENV FILE FOR MeaningCloud
  application_key: "your-key"

  this will be required to use envriment process.
  
const dotenv = require('dotenv');
dotenv.config();
```
- [ ] Reference variables you created in the .env file by putting ```process.env``` in front of it, an example might look like this:
```
console.log(`Your API key is ${process.env.API_KEY}`);

```
wish you enjoy using our App.

