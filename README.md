# Full Stack chat application

Full-stack chat application once created as coding task.

## Description

The task was to create a client and server chat application. I decided to use a custom react setup (not using create-react-app) including TypeScript and Sass which is also available on my GitHub profile.

The requirements were to use: React, Redux, TypeScript, unit tests and e2e tests. I was free to implement any UI/UX to my preference and had a bullet list of tasks that needed to be implemented into the system from the owner.

**Personal difficult parts...**

- ...create socket.io chat application without any server crashes on live production;
- ...using TypeScript for the first time in a project, both client and server side;
- ...using Redux for the first time in a project;
- ...implementing unit and e2e tests, not my most confident area of expertise;
- ...deploying the complete application to Heroku.

### Technical implementations

Frontend

- React
- React-router-dom
- Redux
- Socket.io-client
- TypeScript
- Axios
- Lodash
- Sass
- Classnames
- Custom webpack config
- ESlint
- Cypress

Backend

- Express
- Socket.io
- Typescript
- Cors
- TSlint
- Winston
- Mocha/chai

Styling

Mobile first responsive design using Sass with flexbox and BEM.

**Positive takeaways...**

- ...improved knowledge on using socket.io, TypeScript and new technologie as Winston;
- ...used 'any' as little as possible in TypeScript;
- ...express and socket.io unit testing on server side;
- ...Frontend and backend testing implemented, Cypress was good.

**Improvement areas...**

- ...learn how to properly use mocha/chai with TypeScript files and socket.io overall, had some difficulties here;
- ...get deeper knowledge on SIGINT/SIGTERM and logging;
- ...didn't understand how to implement Redux in this application using socket.io, only used as userReducer.

##### Homepage

![Homepage](/readme_screenshots/homepage.png)

###### Chatroom

![Menuroom](/readme_screenshots/chatroom.png)

###### Chatroom responsive

![Chatroom](/readme_screenshots/chatroom-responsive.png)
