# Chat-Room
Technical exercise


## TODO: 
1. Build a single chat room with some kind of authentication
     - Frontend: VueJs => does not need to be styled
     - Backend: Nestjs => needs to be in memory and does not need to persist to a DB
2. Deploy this application to a server provided by the Jimber Team
3. Provide a CI/CD for this application to the server
     - (on push => build => deploy)

## USER Stories
1. As a User, I want to be able to create a User 
     - Fill out a chat name
2. As a not logged-in User, I should not be able to see any messages
3. As a User, I want to be able to log in
     - It can be any kind of login (it should be decently secure)
4. As a logged-in user, I want to be able to log out
5. As a logged-in user, I want to be able to send messages in a chat room
     - The message should be a maximum of 255 characters
7. As a logged-in user, I want to receive and see messages in real-time.
