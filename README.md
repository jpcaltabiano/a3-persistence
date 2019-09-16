## WPI Outing Club Trip Signup

http://a3-charlieroberts.glitch.me

The website I made is a model of what a trip sign up page may look and act like for WPI Outing Clubs website. Users log in using a local strategy with passport.js. Entering a brand new username and password will create a new log in, but trying to use a different password with an existing username returns an error. They are presented with a table of trip information including the trip name, the dates, a selection of whether they need any gear, a check input for whether the trip has been paid for yet, and a sign up button. I am using basic lowdb for my database in a file called db.json. I chose this because it was the easiest to implement in this scenario. Signing up for a trip adds all the info from the form to that users record in the database. Once a trip has been added, changing the gear selection or the paid check wies in the database, and clicking the remove button deletes the trip from the database. I built my website using two CSS frameworks, tailwind and milligram. I liked the look of tailwind and the ease of cusotmization using their classes. Milligram was very helpful in making a clean looking and properly designed table and header. Modifcations to CSS are included in design achievements. 

Express middleware:
1) Passport: used for user login authentication and sessions
2) body-parser: parsing json from request bodies
3) serve-static: for serving static files from a directory
4) serve-favicon: serves a favicon image upon request
5) express-lowercase-paths: replaces express-uncapitalize, used for converting request paths to all lowercase to avoid errors

## Technical Achievements
- **Tech Achievement**: I wrote a function that runs on a load of index.html providing 'memory' to the UI. When a user has signed up for trips and logs out, when they next sign in the UI will update to represent the trips they've signed up for, hilighting the table row like when the users presses the sign up button.

## Design/Evaluation Achievements
- **Design Achievements**: I added a responsive UI design that gives users feedback based on their choices. When a user signs up for a trip, the table row highlights in green and the button design is cahnged to show a new functionality. I also keep a very consistent theme through the application, using the same colors and white card styles on both the login and index pages. Buttons are set to the color of the underlying background to give a grounded feel. I also added some CSS from two examples (urls in CSS files) and tweaked them to work with my site. I did not change the custom checkboxes much except to fir them with my theme, but I made a good amount of changes to CSS taken from a website to make sure my header was properly oriented and that my SVG logo showed up as intended. 

