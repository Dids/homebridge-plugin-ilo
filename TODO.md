# Things To Do

## Primary Features

- [x] Publish initial version to npm
- [ ] Migrate to TypeScript
- [x] Add ESLint support
- [x] Add basic GitHub Actions CI builds
- [ ] Refactor configuration options and include configuration schema
- [ ] Setup GitHub Actions for automated publishing on new tags (eg. `npm version patch && git push && git push --tags`)
- [ ] Add initial support for as many iLO versions as possible (power button as a switch accessory)
  - [x] Add initial support for iLO 3 (DL380 G7, worked out of the box)
  - [ ] Add initial support for iLO 4 (DL360e Gen8, did not work out of the box)
  - [ ] Add initial support for iLO 5 (_no hardware to test with_)

## Secondary Features

- [ ] Research and implement additional iLO features
  - [ ] Expose temperature(s) through a temperature sensor accessory

## Resources

- [Accessory Example](https://github.com/homebridge/homebridge-examples/tree/master/accessory-example-typescript)
- [Platform Example](https://github.com/homebridge/homebridge-plugin-template)
