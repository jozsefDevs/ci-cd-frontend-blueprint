# ci-cd-frontend-blueprint

This project was bootstrapped with [Create React App](https://github.com/facebook/create-react-app). Thus you can use 
the usual scripts. However this repo rather focuses on the CI/CD set up, having a changelog generated, etc.

## Features 🚀:
- A [Create React App](https://github.com/facebook/create-react-app) project is inside the src/ but that should be 
replaced by any type of FE project. So this is optional, just there to be able to build the project.
- [Commitlint](https://commitlint.js.org/#/) is ensuring that every commit msg. follows the same conventions
- [Semantic release](https://www.npmjs.com/package/semantic-release) is ensuring every time a `develop -> master` merge
happens we auto-generate a `CHANGELOG.md` and also updating the `package.json` with the correct version number. 
- [Github Actions](https://github.com/features/actions) used for simplified install + build + test stages on `develop`
and `master` branches.
- [Surge.sh](https://surge.sh) used for quick and hassle-free deployment for the frontend project