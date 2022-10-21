# How To Run

Make sure you have already registered the api from [FavQs](https://favqs.com/api_keys)
In the terminal you can run

    flutter run --dart-define=fav-qs-app-token=YOUR_KEY

Replace with your own key generated from [FavQs](https://favqs.com/api_keys)

If you don't want to use the Terminal, let's set up our IDEs
head to Android Studio at the top click on "main.dart" then edit configuration, in the **Additional run args** field, add this command into it

    --dart-define=fav-qs-app-token=YOUR_API_KEY

Meanwhile for VSCode you have to edit launch.json in the ".vscode" directory, which is usually a hidden folder, modify the file like so

    "configurations": [

    {

    "name": "wonderwords",

    "request": "launch",

    "type": "dart",

    "program": "lib/main.dart",

    "args": ["--dart-define",
    		 "fav-qs-app-token=YOUR_API_KEY"]

    },

Replace it with your api key

Then Register your app with Firebase as usual, no more step, I assume you know what you're doing.
