# 3rd Episode of Rainbow APIs HUB <Talk to the Experts> Webinar - oauth2 samples

This repository contains the client and server part that have been used during the 3rd episode of Rainbow APIs HUB.
This sample presents a typical integration of the Rainbow users authentication with oauth2.0 integration in Rainbow CPaaS context with a backend see [Users authentication](https://hub.openrainbow.com/#/documentation/doc/hub/users-authentication) for details.

## Preample

You need a Rainbow account. Connect to the [Rainbow HUB](https://hub.openrainbow.com/) to get your developer account.

You need a Rainbow application ID, see [Application Lifecycle](https://hub.openrainbow.com/#/documentation/doc/hub/application-lifecycle)

## Installation

Client:
```shell
$ cd webinar-client
$ npm install
```

Server:
```shell
$ cd webinar-server
$ npm install
```

## Setup

Replace under the file [./webinar-server/app/config/bot.json](./webinar-server/app/config/bot.json) the **bot login**, **bot password**, **app ID**, and **app secret**

```json
...
 "credentials": {
        "login": "<bot login>",
        "password": "<bot password>"
    },
    "application": {
        "appID": "<your app ID>",
        "appSecret": "<your app secret>"
    },
...
```

## Execution

Client:
```shell
$ cd webinar-client
$ npm start
```

Server:
```shell
$ cd webinar-server
$ npm start
```