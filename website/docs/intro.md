<!-- ![image](https://user-images.githubusercontent.com/15864336/101827170-f5ce3180-3afd-11eb-9a60-5933a15f337b.png) -->

<p align="center">
  <a href="https://pub.dev/packages/flutter_facebook_auth"><img alt="pub version" src="https://img.shields.io/pub/v/flutter_facebook_auth?color=%2300b0ff&label=flutter_facebook_auth&style=flat-square"/></a>

  <img alt="last commit" src="https://img.shields.io/github/last-commit/the-meedu-app/flutter-facebook-auth?color=%23ffa000&style=flat-square"/>
  <a href="https://codecov.io/gh/darwin-morocho/flutter-facebook-auth">
  <img src="https://codecov.io/gh/darwin-morocho/flutter-facebook-auth/branch/master/graph/badge.svg?token=XEXUNVP0UK"/>
  </a>
  <img alt="license" src="https://img.shields.io/github/license/the-meedu-app/flutter-facebook-auth?style=flat-square"/>
  <img alt="stars" src="https://img.shields.io/github/stars/the-meedu-app/flutter-facebook-auth?style=social"/>
</p>

<p>The easiest way to add facebook login to your flutter app, get user information, profile picture and more. Web support included.</p>

## Features
- Login on iOS, Android and Web.
- Express login on Android.
- Granted and declined permissions.
- User information, picture profile and more.
- Provide an access token to make request to the Graph API.

## Install

Add the following to your `pubspec.yaml`


```yaml
dependencies:
  flutter_facebook_auth: ^4.3.4+2
```


:::danger IMPORTANT
When you install this plugin you need to configure the plugin on Android before run the project again . If you don't do it you will have a **No implementation found** error because the facebook SDK on Android throws an Exception when the configuration is not defined yet and this locks the other plugins in your project. If you don't need the plugin yet please remove or comment it.
:::
