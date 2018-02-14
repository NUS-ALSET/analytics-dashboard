# Installation 

1. Install `npm` or `yarn` if you don't have it already. Follow <a href = "https://yarnpkg.com/lang/en/docs/install/">Yarn installation guide </a>.
2. Clone github repository into local folder
3. Navigate to `src/containers/Full/Full.js` and change the configuration to reflect your own firebase project. 
```javascript
// Initialize Firebase
// TODO: Replace with your project's customized code snippet
var config = {    
    apiKey: "AIzaSyBPweAHcP4em0PYh8XWzEqjNhTk3OBNS5I",<br>
   authDomain: "dashboard-dev-8b843.firebaseapp.com",  <br>
   databaseURL: "https://dashboard-dev-8b843.firebaseio.com", <br>
   projectId: "dashboard-dev-8b843",  
   storageBucket: "dashboard-dev-8b843.appspot.com",  
   messagingSenderId: "264557605189" 
};
```
4. Import `public/local_data.json` into your firebase database and store it directly in the root node. 
5. To host locally run `npm install` to build the dependencies then `npm start` to start hosting locally. Alternatively, for those using yarn the corresponding commands are `yarn` and `yarn start`. 
6. To deploy to Firebase, navigate to root of the app and execute `npm run build`. Thereafter use `firebase deploy` to deploy to your firebase project. (For `yarn` users the build command is `yarn build`). 


