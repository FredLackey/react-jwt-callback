# React Callback Example  (`react-jwt-callback`)  

Continued from the [`react-auth-context-reload`](https://github.com/FredLackey/react-auth-context-reload) example, this example adds a callback page to handle the redirect from the authorization server.  The token is pushed into the AuthContext, using the `useAuthContext` hook, and then the user is redirected to the home page.

React Router (`react-router-dom`) is used to handle the routing where the JWT is part of the URL.  In this example the JWT is pushed directly into AuthContext however, in the real world, the token should be validated first.  

## Contact Info  

As always, shoot me an email if you have any questions.  I'm happy to help!  

**Fred Lackey**  
[fred.lackey@gmail.com](mailto:fred.lackey@gmail.com)  
[https://www.fredlackey.com](https://www.fredlackey.com)  
