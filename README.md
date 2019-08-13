The client had a website that was built over five years ago. The client came to us with the desire to create a website that would look modern and employ state-of-the-art functionality. In response, we designed and coded a website that incorporated a variety of updated features including: APIs, functional chatbox, and a database.

Website is hosted here: [ACEDetailing.com](https://johnharlepas.github.io/Project1_API/index.html)

Instructions for Local Hosting:

# Step 1: Get Firebase CLI onto local computer

In order to create a local server using Firebase, you needed to install Firebase CLI. Follow the instructions provided here: https://firebase.google.com/docs/cli/. The part of the instructions concerning the installation of the nvm (Node Version Manager) utilized these instructions provided here: https://nodesource.com/blog/installing-node-js-tutorial-using-nvm-on-mac-os-x-and-ubuntu/.  

# Step 2: Initialize the project directory so hosting could happn

Once you got the Firebase CLI, login to Firebase from terminal Bash. Next, initialize the project you plan to use. Make our way to the location of project files. Complete the steps under "Initialize a Firebase project" found at this address: https://firebase.google.com/docs/cli/. It is important to note that you must chose "hosting" in order for local server to work.

# Step 3: File Structure

In order for local server to work, you needed to place all .html files and assets in a "public" folder. The public folder exists at the same level as the .json files created when initialize the project. These .json files may include database.rules.json, firebase.json, and storage.rules. It really depends on what services you chose to use during initialization. In addition, initialization creates a public folder and places the "index.html" inside of it. This index.html has import script in it that will make the local server work. Take that code and placed it inside a javascript file called website.js. 

# Step 4: Starting Local Server

Return to the terminal Bash and type in "Firebase serve." This should bring up to lines that tell you: "hosting: Serving hosting files from: public (line 1), hosting: Local server: http://localhost:5000 (line 2)." These lines told us that the local server is working and its hosting files from folder "public." 

# Step 5: Viewing files on web browser using local server

In order to view files, in the address bar: "localhost:5000/loginPage.html". Change the part after the slash and make it mirror the name of the file you want to see. 








