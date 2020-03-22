# rainydaemon

Play rain in the background.

Made for use as a button in bars such as [polybar](https://github.com/polybar/polybar). See the [examples directory](examples/).

## Requirements

- bash
- mpg321

## Installation

First, ensure you have `mpg321` installed. On debian-based distros, you can run `sudo apt install mpg321`.

```bash
git clone https://github.com/auderer/rainydaemon
cd rainydaemon
chmod +x install.sh
./install.sh
```

## Usage

Run `rainyd` to toggle the player on/off. This command can be used as a click event in [polybar](https://github.com/polybar/polybar), for example.

## Configuration

There is no config file yet, but you can replace the `rain.mp3` file in `~/.config/rainyd/sounds/rain.mp3` if you wish.

## Attribution

Rain sounds from: [orangefreesounds.com/rain-ambience](http://www.orangefreesounds.com/rain-ambience/)