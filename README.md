# Angular Auth0 ZENVIA SMS


Application example using [Angular](https://angular.io/) where a simple WEB application will be implemented using the [Auth0](https://auth0.com/) platform to authenticate and authorize the user and the [ZENVIA](https://www.zenvia.com/) platform to integrate with SMS channel in order to validate the user phone.

This tutorial was posted on my [blog](https://rodrigo.kamada.com.br/blog/validando-o-telefone-do-usuario-por-sms-no-auth0-usando-a-zenvia) in portuguese and on the [DEV Community]() in english.



[![Website](https://shields.braskam.com/v1/shields?name=website&format=rectangle&size=small&radius=5)](https://rodrigo.kamada.com.br)
[![LinkedIn](https://shields.braskam.com/v1/shields?name=linkedin&format=rectangle&size=small&radius=5)](https://www.linkedin.com/in/rodrigokamada)
[![Twitter](https://shields.braskam.com/v1/shields?name=twitter&format=rectangle&size=small&radius=5&socialAccount=rodrigokamada)](https://twitter.com/rodrigokamada)
[![Instagram](https://shields.braskam.com/v1/shields?name=instagram&format=rectangle&size=small&radius=5)](https://www.instagram.com/rodrigokamada/)



## Prerequisites


Before you start, you need to install and configure the tools:

* [git](https://git-scm.com/)
* [Node.js and npm](https://nodejs.org/)
* [Angular CLI](https://angular.io/cli)
* IDE (e.g. [Visual Studio Code](https://code.visualstudio.com/) or [WebStorm](https://www.jetbrains.com/webstorm/))



## Cloning the application


**1.** Clone the repository.

```shell
git clone git@github.com:rodrigokamada/angular-auth0-zenvia-sms.git
```

**2.** Install the dependencies.

```shell
npm ci
```

**3.** Change the `src/environments/environment.ts` file and add the [Auth0](https://app.zenvia.com/home/api) applications settings. 

**4.** Run the application.

```shell
npm start
```
