<h1 align="center">Welcome to mavlink-browser 👋</h1>
<p>
  <a href="https://www.npmjs.com/package/mavlink-browser" target="_blank">
    <img alt="Version" src="https://img.shields.io/npm/v/mavlink-browser.svg">
  </a>
  <a href="https://github.com/neelsani/mavlink-browser#readme" target="_blank">
    <img alt="Documentation" src="https://img.shields.io/badge/documentation-yes-brightgreen.svg" />
  </a>
  <a href="https://github.com/neelsani/mavlink-browser/graphs/commit-activity" target="_blank">
    <img alt="Maintenance" src="https://img.shields.io/badge/Maintained%3F-yes-green.svg" />
  </a>
  <a href="https://github.com/neelsani/mavlink-browser/blob/main/LICENSE" target="_blank">
    <img alt="License: MIT" src="https://img.shields.io/github/license/neelsani/mavlink-browser" />
  </a>
</p>

> Allows the parsing and generation of mavlink v1 and v2 packets within a browser environment.

### 🏠 [Homepage](https://github.com/neelsani/mavlink-browser#readme)

## Install

```sh
npm i mavlink-browser
```

## Run tests

```sh
npm run test
```

## Usage

```javascript
import { mavlink20, MAVLink20Processor } from 'mavlink-browser';
const mavlinkParser = new MAVLink20Processor(null, 42, 150);
```
## Author

👤 **Neel Sani**

* Website: neels.dev/
* Github: [@neelsani](https://github.com/neelsani)
* Email: neel@neels.dev

## 🤝 Contributing

Contributions, issues and feature requests are welcome!<br />Feel free to check [issues page](https://github.com/neelsani/mavlink-browser/issues). You can also take a look at the [contributing guide](https://github.com/neelsani/mavlink-browser/blob/master/CONTRIBUTING.md). Or just shoot me an email at neel@neels.dev

## Show your support

Give a ⭐️ if this project helped you!

## 📝 License

Copyright © 2024 [Neel Sani](https://github.com/neelsani).<br />
This project is [MIT](https://github.com/neelsani/mavlink-browser/blob/main/LICENSE) licensed.

