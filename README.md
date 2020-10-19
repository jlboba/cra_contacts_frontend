# Contacts Frontend with Create React App 

## Description 

This is a frontend *only* react app consuming a third-party API. In particular, this react app is consuming the Django REST API created [here](https://github.com/jlboba/django_rest_api), but this format will work for any seperate server API regardless of what language you built it in. 

---

## Get Set Up Locally 

### On your Browser 

1. Fork this repository to your account 

### In your Terminal 

1. Clone **your fork** of the repo onto your computer anywhere that is not a git repo
1. `cd` into the repo 
1. Touch a `.env` into the root of your project and add a REACT_APP_API_URL value wih the URL to your API. See the .env.sample file for an example of how to set it up
  - Your URL can either be local if you're testing your local API or the deployed url if you're testing the deployed API 
1.Install all the required packages by running: `yarn install` 
1. Run the app by running `yarn start` and you should now be able to see the app on localhost:3000 

--- 

## Deployment

Deployment with create-react-app is fairly straightforward. You can see the full deployment docs from CRA here and take your choice of where you want to deploy it, then follow their instructions: https://create-react-app.dev/docs/deployment

My suggestions for deployment, use either of these two: 

- [Netlify](https://create-react-app.dev/docs/deployment/#netlify)
- [Heroku](https://create-react-app.dev/docs/deployment/#heroku)
