*This repository is a mirror of the [component](http://component.io) module [bencevans/canvas-battery](http://github.com/bencevans/canvas-battery). It has been modified to work with NPM+Browserify. You can install it using the command `npm install npmcomponent/bencevans-canvas-battery`. Please do not open issues or send pull requests against this repo. If you have issues with this repo, report it to [npmcomponent](https://github.com/airportyh/npmcomponent).*
# canvas-battery

  Canvas Battery Status

## Installation

    $ component install bencevans/canvas-battery

## API

### new Battery(canvasDOMElement, [chargePercent=0])

  * draws walls
  * draws charge
  * returns a Battery Instance

### battery.update(chargePercent)

  * sets new charge value
  * redraws charge

### battery.charge

  * current charge percentage

## License

  MIT
