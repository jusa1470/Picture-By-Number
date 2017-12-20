#WE MOVED REPOS: https://github.com/scealux/GridPicWeb












Team Name: Picture-By-Number
Team Members: Alex Fiel, Ryan Loi, Jordan Smart, Julia Sanford, John Apel

Description: 
Our project is an interactive, picture-taking app. It allows users to get outside and take pictures. Taking these pictures will also allow users to view objects in our world from new perspectives and different angles than we see them every day. This app includes putting together small, closeup pictures to make up a new image.
While using this app, you will have the option to choose a picture template that you want to create. This template will have a grid that splits the image into pieces. Each piece will have specific lines that will match up to the original image. The user’s job is to go out into the world and find some object or line that matches up to the line in the template. Once the user has done this for all the pieces, then all of the outside world pictures will come together to create the original image.

Vision Statement: Using [APP NAME] we want to provide a fun, interactive and social way for people to experience new locations.

Motivation: We all like taking photos outside but we want a way to make taking photos more fun. This app would allow to have more fun taking photos with friends and by yourself.

Risks: The biggest risks posed to our group regarding completing this project on time is the fact that not all of us have experience working in Android Studio or developing mobile apps. Although the learning curve for the basics of mobile app development is not too steep, learning something completely new while trying to accomplish set goals in a specific timeframe can pose a challenge. With that being said, some members of the group have developed mobile apps in the past, and they will be able to help the other members of the group get up to speed.
Another risk in this project is the fact that the members of our group all have busy schedules, and we aren’t always able to get together and meet at the same time. Often times one or two members of the group will be unable to attend a group meeting due to class, work, or other commitments. This can pose a challenge simply because communicating through text, even in a professional manner, is generally more difficult than communicating in person.
Aside from these risks, none of the challenges we anticipate running into are things that we have not seen before. This does not mean that a new, unexpected challenge won’t come up during the development of this application, but the primary risk we have with this project is the relative lack of experience our group has with developing mobile apps.
Risk Mitigation Plan: In order to combat the risks of not completing our project on time due to lack of experience with developing mobile apps and not being able to have all members meet at the same time, we have come up with a number of things that will help us work through these challenges.
First of all, with regards to lack of experience with Android Studio and mobile app development, there is one member of the group who has used these tools in the past and is comfortable using them. They will be able to help the others in the group gain a baseline understanding of how the tools work in order to get all members on the same page from the very start. Additionally, there are an incredible amount of resources online for learning Android app development that we will undoubtedly take advantage of. Google itself has tons of information for developers to utilize to learn how to implement whatever functionality they need into their app. We will be sure to make use of these resources to combat our lack of experience with mobile apps.
In order to combat the challenge of not all members of the group being able to meet at the same time, we have set up a number of online tools that allow us to keep in touch even if all members aren’t physically present. First of all, we will be using GitHub to manage all of our code so that we can all contribute without running the risk of losing any of our work. Secondly, we have been using Slack for communication. Slack is an excellent tool because it allows us to create separate threads within our project tab so that members of the group can have separate conversations about separate aspects of the app. This will prove invaluable in the future when several of us are working on one specific piece of functionality from home and need to get in touch with the other members of the group. Finally, we will be using Trello to track our progress on each milestone to ensure that all required elements are completed by the due date.
Despite the challenges we are facing for this project, we have thought about the potential issues that may come our way, and have taken steps to prepare for them. Not all risks can be known before the project begins, but the tools at our disposal combined with our work ethic will allow us to move past these challenges in order to successfully complete the vision we have for the app.

Version Control: For version control we will be using git with Github as our remote repository. Git is a version control method where everyone has local repositories on their computers and commit changes that can later be pushed up to the remote repository. 

Repository: https://github.com/jusa1470/Picture-By-Number 

Developmental Method: We will use the Agile/scrum method of development. Using Agile we will continuously be updating our plan and designing our app. We will be susceptible to changes. Our group will work in sprints, so focus on one key aspect at a time; once the sprint is complete, we will focus on the next key aspect and build upon our current project.

Collaboration Tool: We will be using Slack in order to communicate. On Slack we will also notify each other of updates we have made on our project. We will use Google Docs in order to all be working on one document at the same time. To keep track of our progress and what we need to do, we will use Trello.

Proposed Architecture: 
For the front end development of our application, we will be using Android Studio. Android Studio is a flexible tool that allows the developer to control every aspect of their mobile app to make it look and perform exactly the way they want. Android Studio primarily relies on XML for the design elements of the app, and the Java programming language for the functionality of the application.

For the back end of our application, we will have a database (firebase) of the users of our app which will track how many Picture-By-Number pictures they complete. There will be a leaderboard within the app that will display each user’s ranking by the total number of completed pictures. This introduces a competitive element to the app, making it more of a game and encouraging users to play more often in order to beat out their peers. In order to keep track of this information, we will need to interface with a backend server so that all users of the app will be able to access the leaderboard to have it displayed in their app.

The frontend and backend will communicate with each other through the Java code since it is able to interface with both the XML and the database.
