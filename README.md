# Postman-newman
This repo contains [clickup](https://app.clickup.com/?fromLanding=true) postman collections with environment and newman

## How to run the tests on windows
Go to the terminal and install newman execute **npm install -g newman** command  
The newman run command allows you to specify a collection to be run.  
You can easily export your Postman Collection as a json file from the Postman App and run it using Newman.
### Run test colllection:
```
newman run HW4.postman_collection.json -e ClickUpHW.postman_environment.json
```
Newman also supports reporters.  
For instance, to use the Newman HTMLExtra Reporter go to the terminal execute **npm install -g newman-reporter-htmlextra**
```
newman run HW4.postman_collection.json -e ClickUpHW.postman_environment.json -r htmlextra
```
To see reports without installation  
Go to this link to see [newman report](https://leraroy.github.io/postman-newman/) for collection
