# desafiobossa

[![desafiobossa Documentation](https://img.shields.io/badge/desafiobossa-Documented-blue.svg)](https://desafiobossa.docs.apiary.io/) [![Heroku App Status](http://heroku-shields.herokuapp.com/bossachallengebackend)](https://bossachallengebackend.herokuapp.com) <img src="https://img.shields.io/github/last-commit/AllanRolli/desafiobossa"/> <img src="https://img.shields.io/github/languages/top/AllanRolli/desafiobossa?style=plastic"/> <img src="https://img.shields.io/github/repo-size/AllanRolli/desafiobossa?style=plastic"/> <img src="https://img.shields.io/github/license/AllanRolli/desafiobossa?style=plastic"/>

This project has the purpose of documentation to be inserted in my portfolio

## 👨🏾‍🏫 Documentation

Inside the src/docs has the index.html maked with aglio or you can access in [![desafiobossa Documentation](https://img.shields.io/badge/desafiobossa-APIBluePrint-blue.svg)](https://desafiobossa.docs.apiary.io/)

## :rocket: Technologies

- [NodeJs](https://nodejs.org/en/)


  <img src="https://i0.wp.com/codigosimples.net/wp-content/uploads/2017/03/nodejs.png?fit=500%2C500&ssl=1" width="100" height="100">

## :information_source: How To Use

To clone and run this application, you'll need [Git](https://git-scm.com), [Node.js v12.17][nodejs] or higher + [Npm v6.10.2](https://www.npmjs.com/get-npm) or higher installed on your computer. From your command line:

```bash
# Clone this repository
$ git clone https://github.com/AllanRolli/desafiobossa.git

# Go into the repository
$ cd desafiobossa

# Install dependencies
$ npm install

# Run the app in Development Environment
$ npm run dev

# Run the app in Production Environment
$ npm start
```

## Deploying

### Deploying on Heroku

Click the button below to automatically set up the Polls API in an app
running on your Heroku account.

[![Deploy to Heroku](https://www.herokucdn.com/deploy/button.png)](https://heroku.com/deploy?template=https://github.com/AllanRolli/desafiobossa)

Once you've deployed, you can easily clone the application and alter the
configuration to disable features:

```bash
$ heroku clone -a new-app-name
$ heroku config:set POLLS_CAN_VOTE_QUESTION=false
$ heroku config:set POLLS_CAN_CREATE_QUESTION=false
$ heroku config:set POLLS_CAN_DELETE_QUESTION=false
```

### Deploying on Heroku using Docker

<img src="https://www.mundodocker.com.br/wp-content/uploads/2015/06/docker_facebook_share.png" width="100" height="100">

If you'd like to, you may use Docker on Heroku instead. I created a Dockerfile to build an image in the root of the repository.Refer to the [Heroku
Container Registry and Runtime
Guide](https://devcenter.heroku.com/articles/container-registry-and-runtime#getting-started)
for detailed instructions. Providing you have Docker installed you can follow
the following steps:

```bash
$ heroku container:login
$ heroku container:push web
$ heroku container:release web
```

## :memo: License

This project is under the MIT license. See the [LICENSE](https://github.com/AllanRolli/desafiobossa/blob/master/LICENSE) for more information.

---

## Author

👤 **Allan Rolli**

- Github: [@AllanRolli](https://github.com/AllanRolli)
- LinkedIn: [@AllanRolli](https://www.linkedin.com/in/allan-rolli-a66198106/)
