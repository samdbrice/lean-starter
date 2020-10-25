# L(inux)E(xpress)A(*)N(est)
## LEAN Stack - TypeScript Starter

Implementation of [LEAN Stack (v2)](https://medium.com/@samdbrice) using the [Nest](https://github.com/nestjs/typescript-starter) starter pack and the [create-react-app](https://github.com/facebook/create-react-app) TypeScript template. Ready for Heroku deployment.

## Install
```bash
npm run install
```

## Develop
```bash
npm run start:dev
```

### Deploy
```
heroku create
heroku config:set NPM_CONFIG_PRODUCTION=false
git push heroku master
heroku open
```

enjoy - [samdbrice](https://medium.com/@samdbrice)