# Udagram-App

## Getting Started

1. Clone repo [tawfeek-udagram](https://github.com/tawfik-s/deploy-fullstack-web-app) in your machine
2. Open a terminal and navigate to the root of the repo
3. follow the instructions in the installation steps.
4. project link hosted[udagram-frontend](http://udagram-angular.s3-website-us-east-1.amazonaws.com)
5. API link hosted[API](http://udagram-api-dev.eba-2svdf2dh.us-east-1.elasticbeanstalk.com/)

## App Dependencies

```
- AWS CLI v2.
- Node v14.15.0.
- npm 6.14.8
- A RDS database running Postgres v14.
- A S3 bucket for hosting uploaded pictures.
- A elasticbean stack environment for deploying api

```

### Installation

Provision the necessary AWS services needed for running the application:

- In AWS, provision a publicly available RDS database running Postgres.
- In AWS, provision a s3 bucket for hosting the uploaded files.
- From the root of the repo, navigate udagram-api folder `cd udagram/udagram-api` to install the node_modules `npm install`. After installation is done start the api in dev mode with `npm run dev`.
- Without closing the terminal in step 1, navigate to the udagram-frontend `cd udagram/udagram-frontend` to intall the node_modules `npm install`. After installation is done start the api in dev mode with `npm run start`.

## Testing

we have two different test suite: unit tests and End-To-End tests(e2e).
to run this tests

- `cd udagram/udagram-frontend`
- `npm run test`
- `npm run e2e`

### Unit Tests:

Unit tests are using the Jasmine Framework.

### End to End Tests:

The e2e tests are using Protractor and Jasmine.

## resources:

- udacity classroom.
- AWS tutorials

## Built With

- [Angular](https://angular.io/) - Single Page Application Framework
- [Node](https://nodejs.org) - Javascript Runtime
- [Express](https://expressjs.com/) - Javascript API Framework

## License

[License](LICENSE.txt)
