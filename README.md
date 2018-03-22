# InputGurd.js
**version 2.1**
[![HitCount](http://hits.dwyl.io/gobzateloon/InputGurd.js.svg)](http://hits.dwyl.io/gobzateloon/InputGurd.js)
[![contributions welcome](https://img.shields.io/badge/contributions-welcome-brightgreen.svg?style=flat)](https://github.com/dwyl/esta/issues)


This Will Keep Your Input Elements Safe.

[v2.1](https://github.com/gobzateloon/InputGurd.js/archive/v2.1.zip)

[v2.0](https://github.com/gobzateloon/InputGurd.js/archive/v2.0.zip)

[v1.0](https://github.com/gobzateloon/InputGurd.js/archive/v1.0.zip)

[Try Demo](https://gobzateloon.github.io/examples/InputGurd.html)

## Requires
* jQuery 3.2.1+

## Installation
* First, make sure you are using valid DOCTYPE
* Include nessesary JS files

```
  <script type="text/javascript" src="http://ajax.googleapis.com/ajax/libs/jquery/3.2.1/jquery.min.js"></script>
  <script src="js/InputGurd.js" ></script>
```

## Rules
* If You Delete A Protected Input Element, Page Will Refresh
* Non Unique Id's Are Not Allowed
* I Removed Attribute_Lock From These Attributes
  * Class
  * Style

## Usage

#### If You Need To Apply InputGurd To Specific Area You Must Try This.
```
    $('#login').InputGurd();
```

#### Add 'NoGurd' Attribute to prevent InputGurd.
```
    <input NoGurd ... >
```

#### Add 'nt-' Prefixes to Attribute for prevent Attribute_Lock.
```
    <input nt-placeholder="Password" ... >
```

#### Add 'unique-' Prefixes To Set Unique Attribute
* 'unique-' Attribute Will Be Hide After First Run

```
    <input unique-ng-model ng-model="test" ... >
```

#### If You Need To Apply InputGurd To Specific Element.
```
    <input InputGurd ... >
```

## Author Information
InputGurd.js was created by Thanura Nadun.
