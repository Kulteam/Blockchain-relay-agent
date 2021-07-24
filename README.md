# MONCoin®: Blockchain Relay Agent

> RabbitMQ agent that relays information to/from MONCoind to interact with the MONCoin® network.

## Prerequisites

- node >=6
- RabbitMQ >= 3.7.9

## Install

```sh
npm install
```

## Usage

1) Use your favorite text editor to change the values as necessary in `config.json`

```javascript
{
  "daemon": {
    "host": "127.0.0.1",
    "port": 12898
  },
  "queues": {
    "relayAgent": "request.network"
  }
}
```

2) Set your environment variables and start the service up

```sh
export RABBIT_PUBLIC_SERVER=127.0.0.1
export RABBIT_PUBLIC_USERNAME=yourrabbitmqusername
export RABBIT_PUBLIC_PASSWORD=yourrabbitmqpassword
npm start
```

## Run tests

```sh
npm test
```

## Author

👤 **TurtlePay® Development Team**

* Twitter: [@TurtlePay](https://twitter.com/TurtlePay)

## 🤝 Contributing

Contributions, issues and feature requests are welcome!

Feel free to check [issues page](https://github.com/Kulteam/Blockchain-relay-agent/issues).

## Show your support

Give a ⭐️ if this project helped you!


## 📝 License

Copyright © 2018-2019 [TurtlePay® Development Team](https://github.com/TurtlePay).

This project is [AGPL-3.0](https://github.com/Kulteam/Blockchain-relay-agent/blob/master/LICENSE) licensed.
