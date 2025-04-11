# Wander World

![Image 1](https://github.com/Asthasachan/Wander-World/blob/master/screenshots/main.png)  
![Image 2](https://github.com/Asthasachan/Wander-World/blob/master/screenshots/blog.png)  
![Image 3](https://github.com/Asthasachan/Wander-World/blob/master/screenshots/profile.png)  

Wander World is a web site where users can share their travelling experiences which will help other users to choose their next holiday destination. To get started, simply sign up.

Wander world is a web dev project created using Node.js, Express, MongoDB, and Bootstrap. Passport.js is used to handle authentication. 

## Features
* Users can create, edit, and remove thier blogs
* Users can review blogs once, and can edit or remove their review
* User profiles have information on the user, such as their name, email, join date, blogs, and the option to edit or delete their profile
* Search places by name or location
* Sort places by highest rating, most reviewed, lowest price, or highest price

## Run it locally
1. Install [mongodb](https://www.mongodb.com/)
2. Create a cloudinary account to get an API key and secret code

```
git clone https://github.com/Asthasachan/Wander-World.git
cd Wander-World
npm install
```

Create a .env file (or just export manually in the terminal) in the root of the project and add the following:  

```
DATABASEURL='<url>'
API_KEY=''<key>
API_SECRET='<secret>'
```

Run ```mongod``` in another terminal and ```node app.js``` in the terminal with the project.  

Then go to [localhost:3000](http://localhost:3000/).


