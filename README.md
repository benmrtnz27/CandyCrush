# Candy Crush App Made with React

Check out the project here: https://benmrtnzcandycrush.netlify.app

## What it is

Currently this is a clone of the App game Candy Crush for the browser.

### Setup

Run the `npm start` command in the terminal while in the root directory. This should load up a local version of the game on your pc. This way you can test and preview all of your contribution locally before making a pr.

### How it works

The app is essentially, ran with just a few functions. the `checkFor...` functions allow the game to check for matches of 3 or 4 either vertically or horizontally. `moveIntoSquareBelow` allows the candies to fall down if there is no candy underneath it. Creating a cascading effect to the game and making it never-ending. a few `useState`s control the score, and position of the candies. With that being said, hopefully that is enough to get started on the project and understand what each function does. Additionally there is a React component called ScoreBoard which just displays the score. If there are any questions feel free to ask them here or on Discord.

### contributing

Please follow the standard JavaScript and JSX styling guidelines. Keep all components in the components directory. Add documentation to any new features/components/functions when contributing.
