# A working example of Auth0 authentication service in Angular2.

0. Backend: **NodeJS, express, express-jwt**
0. Frontend: **Angular2, Typescript, Bootstrap**

# Instalation

0. Clone repository
0. Run npm install
0. Register in auth0.com
0. Create an app and a few test users
0. In app->settings add http://localhost:3001 in Allowed Callback URLs, Allowed Logout URLs, Allowed Origins (CORS)
0. Edit variable authenticate in server/app.js with your keys
0. Edit variable lock in client/src/app.ts with your keys
0. Run gulp play
0. Visit http://www.localhost:3001
0. Enjoy!

