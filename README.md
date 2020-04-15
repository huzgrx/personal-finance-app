# My personal finance

Create your monthly budget.

## Getting Started

Create a firebase account:
[Firebase](https://firebase.google.com/)

### Prerequisites

- Node 8.11.0+
  - [Node](https://nodejs.org/en/)
- Vue cli

  - [Vue cli](https://cli.vuejs.org/guide/installation.html)

- Create .firebaserc file inside client folder

```
{
  "projects": {
    "default": "your_firebase_app"
  }
}
```

- In the client folder create a .env file for firebase project information

```
VUE_APP_FIREBASE_API_KEY=
VUE_APP_FIREBASE_AUTH_DOMAIN=
VUE_APP_FIREBASE_DATABASE_URL=
VUE_APP_FIREBASE_PROJECT_ID=
VUE_APP_FIREBASE_STORAGE_BUCKET=
VUE_APP_FIREBASE_MESSAGING_SENDER_ID=
VUE_APP_FIREBASE_APP_ID=
```

### Installing

# At client folder

## Project setup

```
npm install
```

### Compiles and hot-reloads for development

```
npm run serve
```

### Compiles and minifies for production

```
npm run build
```

### Lints and fixes files

```
npm run lint
```

### Customize configuration

See [Configuration Reference](https://cli.vuejs.org/config/).

## Deployment

```
cd client
npm run build
firebase deploy
```

## Built With

- [Vue.js](https://vuejs.org/) - The javascript framework
- [Firebase](https://firebase.google.com/) - Authentication and real time database
- [Vuetify](https://vuetifyjs.com) - Vue UI Library with beautifully handcrafted Material Components

## Contributing

Please send me an email [Felipe Chiapini](fchiapini@gmail.com) I will be happy to help

## Author

- **Felipe Chiapini** - Project owner - [Felipe Chiapini](https://github.com/fchiapini)

## Acknowledgments

- A special thanks to my wife for supporting me
