# smolDeck

smolDeck is a tiny [cyberDeck](https://www.reddit.com/r/cyberDeck/) based on the Keyboard FeatherWing by [arturo182](https://github.com/arturo182) (available from [Tindie](https://www.tindie.com/products/arturo182/keyboard-featherwing-qwerty-keyboard-26-lcd/)). The keyboard may be familiar because it was previously used in [Blackberry](https://github.com/arturo182/BBQ10KBD) devices.

![smolDeck front](images/smolDeck-front.jpg)

The Keyboard FeatherWing is a computer peripheral.  It needs a [feather](https://www.adafruit.com/feather) device with a CPU, RAM, etc. plugged into the back to make it work. The feather could be running [CircuitPython](https://circuitpython.org/) or Arduino or even Linux.

![smolDeck back](images/smolDeck-back.jpg)

The Keyboard FeatherWing includes a [Stemma-QT](https://learn.adafruit.com/introducing-adafruit-stemma-qt/what-is-stemma-qt) jack which can be used for enhanced cyber-ing, if you have a standard Stemma-QT brain stem implant. Or it can be used with external [Stemma-QT](https://www.adafruit.com/category/1005) and [Qwiic](https://www.sparkfun.com/qwiic) I2C devices.

## CircuitPython (or Arduino)

* boards: [M4 Express](https://www.adafruit.com/product/3857), [nRF52840 Express](https://www.adafruit.com/product/4062)
* get [libraries](https://github.com/arturo182/keyboard_featherwing_sw/tree/master/circuitpython) for hardware support
* code [examples](https://www.solder.party/docs/keyboard-featherwing/examples/) for display, keyboard, etc.

## Linux

The [Giant Board](https://groboards.com/giant-board) available from [Crowd Supply](https://www.crowdsupply.com/groboards/giant-board) is a feather form-factor board that runs Debian. There is [documentation](https://groboards.com/docs) and a 'blackberry' image in the [downloads](http://downloads.groboards.com) which connected the screen (got a login prompt), but not the keyboard (couldn't type and login) when I tried it.

Update: Someone found a [bodge](https://twitter.com/groguard/status/1304881264185339904) to fix the keyboard issue.

