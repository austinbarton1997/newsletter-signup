# Newsletter Signup
 
 You can see the live version located at: https://arcane-bastion-98590.herokuapp.com/
 
 ![alt text](https://github.com/austinbarton1997/newsletter-signup/blob/master/website.png)
 
 You will need to run app.js with node

The newsletter sends the user information to mailchimp using their api. To use this system you will need to change the url variable and auth inside the options object:

```
const url = `https://us17.api.mailchimp.com/3.0/lists/YOURLISTID`;

const options = {
    method: "POST",
    auth: "austin:YOURAPIKEY",
  };
```
