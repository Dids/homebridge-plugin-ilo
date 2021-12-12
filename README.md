# Homebridge HPE iLO plugin for HomeKit

**NOTE:** _This is a fork of [homebridge-plugin-ilo](https://github.com/pawelwiecaszek/homebridge-plugin-ilo) by [pawelwiecaszek](https://github.com/pawelwiecaszek)._

Homebridge plugin for controlling HPE servers through iLO.

# Installation

```sh
npm install @didstopia/homebridge-plugin-ilo
```

# Usage

```json
{
  "accessory": "IloSwitch",
  "name": "IloSwitch",
  "user": "YourUsernameGoesHere",
  "password": "YourPassGoesHere",
  "server": "Your IP/FQDN Goes Here"
}
```

## License

This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details
