# Project Title

Flutter Firebase Todo app

# Project Description

This is a simple todo app build with flutter and firebase, please check the commits if you want to see the app without firebase added(firebase may not work as its configured to work on my private account)

## Features
```
Create Todo
Remove Todo
```

## Sreenshots
| home  | add todo |
| -------------- | ------------- |
| <img src="https://github.com/vankatwijk/Todo-Flutter-Firebase/blob/main/docs/Screenshot_2020-10-06-14-05-00-746_com.example.Todo.jpg"> | <img src="https://github.com/vankatwijk/Todo-Flutter-Firebase/blob/main/docs/Screenshot_2020-10-06-14-05-22-052_com.example.Todo.jpg"> |



## Getting Started

The instructions below will help you setup the copy of the flutter app on your development machine.

### Prerequisites

Make sure to have andrid studio with Sdk 10+ api level 29 and greater and flutter and dart installed

### Installing


After you clone this project, do the following:

```bash
# go into the project
cd <your project folder>

# install dependencies
flutter pub get

# install composer dependencies
composer install

#connect your firebase account with an active firestore
update the file ~Todo/android/app/google-services.json

```

## Debuging
```bash
#the firebase plugin has changed and alot of tutorial on youtube do not include the firebase.initialize() on app start please check this stackoverflow for the solution used in this project
https://stackoverflow.com/questions/63492211/no-firebase-app-default-has-been-created-call-firebase-initializeapp-in 
```

## Running the tests
```bash
# flutter app
flutter run
```


## Based on 

* [Youtube](https://www.youtube.com/watch?v=KfhBsahIk7w&ab_channel=AbdulAzizAhwan) - Create a Simple Flutter Firebase CRUD TodoList App from Scratch (note: video is now outdated)

## Authors

* **Hendrikus van Katwijk** - [Github](https://github.com/vankatwijk) - [Personal website](https://hpvk.com)

## License

This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details
PHP framework