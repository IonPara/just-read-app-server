# [Just Read]( https://just-read.onrender.com/) - Server Side

📃 **Content:**
- [General Information ](#General-Information)
- [Language used](#languages)
- [Setup](#setup)
- [Contact](#contact)

 ## 📑 General Information:
 
This repository is the backend of a full stack MERN application.
Just Read is a book store application that provides users with the ability to create an account, search for their favorite books, purchase them, and leave reviews. The app supports both standard end-user access and admin access. Administrators have the ability to monitor user behavior and make any necessary changes.

The books data is pulled from [google books api](https://developers.google.com/books).


The app is built using MongoDB, Express, React, and Node.js (the MERN stack).<br>
<pre>● It creates, reads, updates, and deletes (CRUD) information from MongoDB.</pre>

<b>Here are some of the measures taken to ensure the security of this app:</b> <br>
<pre>● The app authenticates users using JWT to safely transmit the information between client and server.
● The API keys are saved as environment variables.</pre> 

:floppy_disk: The front-end of the app was deployed on [Netlify.com](https://netlify.com/)<br>
:floppy_disk: The back-end of the app was deployed on [Heroku.com](https://heroku.com/)
 <pre>  Back-end and front-end separately to make the app safer and easier to debug.</pre>

The goal of this project is to showcase the ability to build and deploy a full stack application. 

### 🔣 <a id="languages">Technoloogies used </a>:

<p align="left">
<img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/mongodb/mongodb-original-wordmark.svg" alt="mongodb" width="50" height="50"/>
<img src="https://skillicons.dev/icons?i=express&theme=light"/>
<img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/react/react-original-wordmark.svg" alt="react" width="50" height="50"/>
<img src="https://skillicons.dev/icons?i=nodejs&theme=light"/>
<img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/javascript/javascript-original.svg" alt="javascript" width="50" height="50"/>
<img src="https://skillicons.dev/icons?i=redux&theme=light"/>
<img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/bootstrap/bootstrap-plain-wordmark.svg" alt="bootstrap" width="50" height="50"/>
<img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/css3/css3-original-wordmark.svg" alt="css3" width="50" height="50"/> 
<img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/html5/html5-original-wordmark.svg" alt="html5" width="50" height="50"/>
<img src="https://skillicons.dev/icons?i=tailwind&theme=light"/>
<img src="https://skillicons.dev/icons?i=vscode&theme=light"/>
<img src="https://img.icons8.com/color/48/null/java-web-token.png"/>
<img src="https://skillicons.dev/icons?i=git&theme=light"/>
<img src="https://skillicons.dev/icons?i=github&theme=light"/>
</p>


## 📘 <a id="setup">Setup</a>:

### You can visualise it by clicking on the link [here](https://just-read.netlify.app/)

### Or by following these steps :point_down:

1. [Download client side zip file](https://github.com/IonPara/just-read-app-client/archive/refs/heads/main.zip)
2. [Download server zip file](https://github.com/IonPara/just-read-app-server/archive/refs/heads/main.zip)
3. [Download **Node.js**](https://nodejs.org/dist/v18.13.0/node-v18.13.0-x64.msi)
4. Navigate to project's just-read-app-server directory, create an environment variable called API_KEY and add your MongoDB api key, create an environment variable called ACCESS_TOKEN and create a JWT a secret key.
5. Run: 
<pre> npm install 
 npm start 
</pre>
6. Navigate to project's just-read-app-client directory, create an environment variable called REACT_APP_API_KEY and add your GOOGLE BOOKS api key.
7. Run: 
<pre> npm install 
 npm start 
</pre>


Runs the app in the development mode.

Open http://localhost:3000 to view it in your browser.

![just-read](https://user-images.githubusercontent.com/84988051/222515015-f555971a-1c79-47d5-9c65-b95def1ca825.png)

## ✉️ <a id="contact">Contact</a>:

Created by [IonPara](https://github.com/IonPara).

Feel free to leave your feedback.
