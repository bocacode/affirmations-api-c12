# Affirmation API on GCloud

To get this running locally
1) Fork this repo to have it in your git repositories
2) Clone that new project to your computer.
3) Go to Firebase and create a new project (or use an exising one) and download your credentials from there and save it as "credentials.json" where the index.js file is (the "root" of your project)
4) now run ```gcloud config set project Your-Project-Name-Here``` obviously with "Your-Project-Name-Here" with a project name in your firebase or google cloud list to connect this project with your google cloud
5) run ```gcloud app deploy``` to push it live as a "google app engine app"
6) Celebrate 🎉 as you now have an app in google app engine like all the big girls and boys