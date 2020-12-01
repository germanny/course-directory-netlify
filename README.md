# course-directory-netlify
Treehouse - Deploy React App with Netlify

## Info
```
GitHub repo:       https://github.com/germanny/course-directory-netlify
Logs:              https://app.netlify.com/sites/course-directory-netlify/deploys/5fc66421c740be0098b6e33f
Website Draft URL: https://5fc66421c740be0098b6e33f--course-directory-netlify.netlify.app
```

## Local Dev

```
nvm use v10.16.0
npm run start
```

## Deploy with Netlify:

```
// netlify commands need ^14.15.x to work properly
nvm use --lts
npm install netlify-cli -g

netlify init
npm run build

netlify deploy
netlify deploy --prod
```
