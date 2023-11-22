Monkey Jump App 

 

## Installation

**1.** Fork and Clone this repository.

**2.** Navigate to the backend directory and run bundle install to install necessary gems:
```bash
$ bundle install
```
**3.** Migrate the database:
```bash
$ rails db:migrate
```
**4.** Start the rails server:
```bash
$ rails s
```
**5.** You're now all set! To run the app, navigate to the frontend directory and open the html file: 
```bash
$ open index.html
```
## Usage
You should now be brought to the login screen. Enter your desired username and login! 

After logging in you will see the game screen and user panel which will show your top 5 scores. Press 'START' to begin the game and use the arrow keys to move the monkey left, right, or straight ahead.

The game is over when the monkey falls. Your score is based on how many platforms you pass, and will be displayed to you after the game is over. 

Feel free to play the game as many times as you like. If you get into the top 10 scores on your database your name will be displayed on the homepage!

We hope you enjoy playing Monkey Jump! 😊
