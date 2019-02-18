[![Build Status](https://travis-ci.org/IBM/watson-banking-chatbot.svg?branch=master)](https://travis-ci.org/IBM/watson-banking-chatbot)

# Watson Machine Learning Node Starter App

In this Code Pattern, we will build a nodejs app using yeoman and [Watson Machine Learning](https://cloud.ibm.com/catalog/services/machine-learning). We start with a basic nodejs web app that is scaffolded using [Yeoman](https://yeoman.io/), and then add an example of a machine learning scoring app. The user can use this, or other examples provided, to create a web server app that connects to the Watson Machine Learning service to score a machine learning model.

When the reader has completed this Code Pattern, they will understand how to:

* Create a scaffolded application using Yeoman
* Modify the code to create an app that can score a machine learning model
* Deploy and use the nodejs app as a web front end

![](doc/source/images/architecture.png)

## Flow

1. Step 1.
2. Step 2.
3. Step 3.
4. Step 4.
5. Step 5.

# Watch the Video

[![](http://img.youtube.com/vi/Jxi7U7VOMYg/0.jpg)](https://www.youtube.com/watch?v=Jxi7U7VOMYg)

# Prerequisites

You will need to create your machine learning model separately using [Watson Machine Learning](https://cloud.ibm.com/catalog/services/machine-learning)

The example frontend apps use the following code patterns to create the models:

* foo
* bar
* toast

# Steps

Use the ``Deploy to IBM Cloud`` button **OR** create the services and run locally.


## Deploy to IBM Cloud

[![Deploy to IBM Cloud](https://bluemix.net/deploy/button.png)](https://bluemix.net/deploy?repository=https://github.com/IBM/watson-banking-chatbot.git)

1. Press the above ``Deploy to IBM Cloud`` button and then click on ``Deploy``.

2. In Toolchains, click on Delivery Pipeline to watch while the app is deployed. Once deployed, the app can be viewed by clicking 'View app'.
![](doc/source/images/toolchain-pipeline.png)

3. To see the app and services created and configured for this Code Pattern, use the IBM Cloud dashboard.
## Run locally

> NOTE: These steps are only needed when running locally instead of using the ``Deploy to IBM Cloud`` button.

1. [Clone the repo](#1-clone-the-repo)
2. [Configure credentials](#2-configure-credentials)
3. [Run the application](#3-run-the-application)

### 1. Clone the repo
Watson Machine Learning Node Starter App

Clone the `watson-machine-learning-node-starter-app` locally. In a terminal, run:

```bash
git clone https://github.com/IBM/watson-machine-learning-node-starter-app
cd watson-machine-learning-node-starter-app
```

### 2. Configure credentials

Copy the [`env.sample`](env.sample) to `.env`.

```bash
cp env.sample .env
```
Edit the `.env` file with the necessary settings.

#### `env.sample:`

```
# Replace the credentials here with your own.
# Rename this file to .env before starting the app.

```

### 3. Run the application

1. Install [Node.js](https://nodejs.org/en/) runtime or NPM.
1. Start the app by running `npm install`, followed by `npm start`.
# Sample output

![](doc/source/images/sample_output.png)

# Troubleshooting

## License

This code pattern is licensed under the Apache License, Version 2. Separate third-party code objects invoked within this code pattern are licensed by their respective providers pursuant to their own separate licenses. Contributions are subject to the [Developer Certificate of Origin, Version 1.1](https://developercertificate.org/) and the [Apache License, Version 2](https://www.apache.org/licenses/LICENSE-2.0.txt).

[Apache License FAQ](https://www.apache.org/foundation/license-faq.html#WhatDoesItMEAN)
