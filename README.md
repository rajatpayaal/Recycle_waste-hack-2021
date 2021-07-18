<<<<<<< HEAD


* when you clone .. inside the react folder..
### `npm install`
### `npm install -g serve` 
### `npm run build `
### `npm install --save react-router-dom`

=======
* when you clone ..
### `npm install`
### `npm install -g serve` 
### `npm run build `
### `npm start`
### `npm install --save react-router-dom`



>>>>>>> 606b5f42b44e89aa340ef5e5f4954c86463aac2b
* Create app with react.js ui

### `npx create-react-app recycle_waste`
### `cd recycle_waste`
### `npm start` 


 * For nodemon

### `npm install nodemon`


In the project directory, you can run:

### `npm start`
 * in react folder 
### `npm install bootstrap --save`
  * router 
### `npm install --save react-router-dom`

* new user want access token :-
### `* password :- EyryxarhvcnNjb15Syyt`

Runs the app in the development mode.\
Open [http://localhost:3000](http://localhost:3000) to view it in the browser.

The page will reload if you make edits.\
You will also see any lint errors in the console.

### `npm test`

Launches the test runner in the interactive watch mode.\
See the section about [running tests](https://facebook.github.io/create-react-app/docs/running-tests) for more information.

### `npm run build`

Builds the app for production to the `build` folder.\
It correctly bundles React in production mode and optimizes the build for the best performance.

The build is minified and the filenames include the hashes.\
Your app is ready to be deployed!

See the section about [deployment](https://facebook.github.io/create-react-app/docs/deployment) for more information.

### `npm run eject`

**Note: this is a one-way operation. Once you `eject`, you can’t go back!**




<p align="center">
    <a href="https://cloud.ibm.com">
        <img src="https://cloud.ibm.com/media/docs/developer-appservice/resources/ibm-cloud.svg" height="100" alt="IBM Cloud">
    </a>
</p>

<p align="center">
    <a href="https://cloud.ibm.com">
    <img src="https://img.shields.io/badge/IBM%20Cloud-powered-blue.svg" alt="IBM Cloud">
    </a>
    <img src="https://img.shields.io/badge/platform-node-lightgrey.svg?style=flat" alt="platform">
    <img src="https://img.shields.io/badge/license-Apache2-blue.svg?style=flat" alt="Apache 2">
</p>


# Create and deploy a Node.js + Cloudant application

In this sample application, you will create a basic web application using Express to serve web pages in Node.js integrated complete with standard best practices, including a health check and application metric monitoring. In addition, this sample includes integration with Cloudant, a fully managed JSON document database.

You can access the cloud native microservice capabilities at the following endpoints:
- Health endpoint: `/health`

## Steps

You can [deploy this application to IBM Cloud](https://cloud.ibm.com/developer/appservice/starter-kits/nodejs-+-cloudant) or [build it locally](#building-locally) by cloning this repo first. Once your app is live, you can access the `/health` endpoint to build out your cloud native application.

### Deploying to IBM Cloud

<p align="center">
    <a href="https://cloud.ibm.com/developer/appservice/starter-kits/nodejs-+-cloudant">
    <img src="https://cloud.ibm.com/devops/setup/deploy/button_x2.png" alt="Deploy to IBM Cloud">
    </a>
</p>

Click **Deploy to IBM Cloud** to deploy this same application to IBM Cloud. This option creates a deployment pipeline, complete with a hosted GitLab project and a DevOps toolchain. You can deploy your app to Cloud Foundry, a Kubernetes cluster, or a Red Hat OpenShift cluster. OpenShift is available only through a standard cluster, which requires you to have a billable account.

[IBM Cloud DevOps](https://www.ibm.com/cloud/devops) services provides toolchains as a set of tool integrations that support development, deployment, and operations tasks inside IBM Cloud.

### Building locally

To get started building this application locally, you can either run the application natively or use the [IBM Cloud Developer Tools](https://cloud.ibm.com/docs/cli?topic=cloud-cli-getting-started) for containerization and easy deployment to IBM Cloud.

#### Native application development

- Install the latest [Node.js](https://nodejs.org/en/download/) 14+ LTS version.

Once the Node toolchain has been installed, you can download the project dependencies with:

```bash
npm install
```

To run your application locally:

```bash
npm run start
```

Your application will be running at `http://localhost:3000`.  You can access the `/health` endpoint at the host. You can also verify the state of your locally running application using the Selenium UI test script included in the `scripts` directory.

#### IBM Cloud Developer Tools

Install [IBM Cloud Developer Tools](https://cloud.ibm.com/docs/cli?topic=cloud-cli-getting-started) on your machine by running the following command:
```
curl -sL https://ibm.biz/idt-installer | bash
```

Create an application on IBM Cloud by running:

```bash
ibmcloud dev create
```

This will create and download a starter application with the necessary files needed for local development and deployment.

Your application will be compiled with Docker containers. To compile and run your app, run:

```bash
ibmcloud dev build
ibmcloud dev run
```

This will launch your application locally. When you are ready to deploy to IBM Cloud on Cloud Foundry or Kubernetes, run one of the following commands:

```bash
ibmcloud dev deploy -t buildpack // to Cloud Foundry
ibmcloud dev deploy -t container // to K8s cluster
```

You can build and debug your app locally with:

```bash
ibmcloud dev build --debug
ibmcloud dev debug
```

## Testing, linting, and code coverage

### Running tests and code coverage

To run tests and code coverage, run `npm run test`. A `coverage` folder will be created with code coverage results that can be reviewed for gaps. The code coverage thresholds are also defined in `package.json` under `nyc` and can be adjusted if needed. Also, you can use the script `npm run fix` to automatically fix linting problems.

### Pre-commit hooks

By default, a [Husky](https://github.com/typicode/husky) pre-commit hook is defined in `package.json`, which runs linting, testing, and code coverage before the commit is made. If either the linting, testing, or code coverage fails, the pre-commit hook prevents the changes from being committed. Review the results and fix the problems, or modify the thresholds to allow the commit to succeed.

## Next steps
* Learn more about augmenting your Node.js applications on IBM Cloud with the [Node Programming Guide](https://cloud.ibm.com/docs/node?topic=nodejs-getting-started).
* Explore other [sample applications](https://cloud.ibm.com/developer/appservice/starter-kits) on IBM Cloud.

## License

This sample application is licensed under the Apache License, Version 2. Separate third-party code objects invoked within this code pattern are licensed by their respective providers pursuant to their own separate licenses. Contributions are subject to the [Developer Certificate of Origin, Version 1.1](https://developercertificate.org/) and the [Apache License, Version 2](https://www.apache.org/licenses/LICENSE-2.0.txt).

[Apache License FAQ](https://www.apache.org/foundation/license-faq.html#WhatDoesItMEAN)
