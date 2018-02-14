# Polymer and Firebase app

I'd like to share my article about [Polymer vs Angular vs React: Which is leading the future of web apps?](https://mentormate.com/blog/polymer-vs-angular-future-web-apps/)

The blog app I created is built using the toolbox and served using the PRPL pattern and multi-view progressive web app.

[Live demo](https://mentormate-polymer.firebaseapp.com)

### Polymer build CLI

```bash
polymer build --entrypoint index.html
```

### Firebase commands

> You should now have a globally available firebase command available from any terminal window on your machine. Once you've installed the Firebase CLI, sign in using your Google account:

```bash
firebase login
```

> To initialize a new project directory, change directories in the terminal to your desired project directory and run:

```bash
firebase init
```

> When you select a project during firebase init, an alias called default is created for you. To create a new alias, run:

```bash
firebase use --add
```

> Deploy the application to firebase

```bash
polymer deploy
```
