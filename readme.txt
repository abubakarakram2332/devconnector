
EDITOR SETUP:
First of all go to https://nodejs.org/en/   click on recomended for most users button to download for windows .
Now go to https://git-scm.com/download/win and click on download for windows in right side of page.

 Secondly we will need a editor.

 Download visual studio code..
Also create project folder in which all dependencies will be installed. 

  Then after installing visual studio code go to file->preferences-> settings  Then go to overwrite the default settings section then copy this whole body 
covered with curly brackets and paste it into that section then press ctrl+s to save that and restart the visual studio code  .
   
{
  "git.ignoreMissingGitWarning": true,

  "editor.fontSize": 26,
  "terminal.integrated.fontSize": 26,
  "emmet.includeLanguages": {
    "javascript": "javascriptreact"
  },
  "emmet.syntaxProfiles": {
    "javascript": "jsx"
  },

  "terminal.integrated.shell.windows": "C:\\Program Files\\Git\\bin\\bash.exe",
  "editor.wordWrap": "on",
  "editor.formatOnSave": true,
  "editor.tabSize": 2,
  "window.zoomLevel": -2
}
 
now to check git bash is working or not we simply go to view->integrated terminal a cmd sort of gitbash will open 

Now after restarting press ctrl+shift+x to open extension this will open some sort of search bar on the left of editor  then on search bar 
    type ES7 React/Redux/Graphql/React-Native snippets then press intall to install that extension ..

Then after installing above extension again type on that search bar which is Node.js Modules Intellisense Then press install to it.. 

 Mongo db setup:
   Now open that project folder with visual studio code .
   
   now go to view ->integrated terninal make sure you are in that prject folder you created above in that directory write these below line to install express.
   
   only write between in single commas  'npm init' commas must not be included for package name press enter to go next option until you find entry point.
   
   Type server.js in against entry point this will change destiny from (index.js) to server.js set author to a ny name and the reply yes .
    
   now make sur you are int the project folder director by keeping this .
   
    Type npm i express mongoose passport passport-jwt jsonwebtoken body-parser bcryptjs validator.
    
    Then after downloading 
    
    all these intruction should in yor project current directory 
    
    npm i -D nodemon

then on project dir type only node server pres enter ..

Again this is important all intruction start with npm should be write in project folder for e.g USER@DESKTOP-U7VM6TA MINGW64 ~/Desktop/devconnector

   where devconnector is project folder name..
   
   Now npm run server 
   
   npm i gravatar press enter
   
   now npm run server to again run the backen server

   we dealt with the backend server ..

   now the turn is to frontend react
 
   now again in your project folder 

   npm i -g create-react-app press enter.

   now again in you pro folder type create-react-app client

   now again in you pro folder type 'cd client' make sure you write only  captured in single brackets which is cd client
   
   now type npm start    //this will start front end server
   
    now cd ..    //this will change directory to our in current project folder
    
    npm i concurrently
    
    npm run dev    // this instruction will run backend and front end server together..
   
   React router setup:

  make sure you are in you project folder  then :

  Type cd client                                      //this will change directory to client

   npm i react -router -dom 
  cd ..
  npm run dev
  cd client 
  npm i axios 
  npm i classnames


  now instalinng redux dependecies

  npm i redux react-redux redux-thunk 
  npm i jwt-decode 

  Now all depencies are completely installed.

  
  At last replace the client folder of project that i submit on github with your client folder in your prject folder installed in your local disk..


 







	


         
  

