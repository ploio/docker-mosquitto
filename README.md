# Portefaix Mosquitto

* Master :
[![Circle CI](https://circleci.com/gh/portefaix/docker-mosquitto/tree/master.svg?style=svg)](https://circleci.com/gh/portefaix/docker-mosquitto/tree/master)

* Develop :
[![Circle CI](https://circleci.com/gh/portefaix/docker-mosquitto/tree/develop.svg?style=svg)](https://circleci.com/gh/portefaix/docker-mosquitto/tree/develop)


![logo](http://pkgs.alpinelinux.org/assets/alpinelinux-logo.svg)

[Alpine Linux][] is a Linux distribution built around musl libc and BusyBox.
This image is based on the official Alpine Linux.

[Mosquitto][] is an open source MQTT broker.

Port exported are : `1883` (MQTT) and `9001` (Websocket MQTT).

## Usage

    $ docker run --rm=true -it -p 1883:1883 -p 9001:9001 portefaix/mosquitto

## Supported tags

- `1.4.8.r2` [![](https://badge.imagelayers.io/portefaix/mosquitto:1.4.8.r2.svg)](https://imagelayers.io/?images=portefaix/mosquitto:1.4.8.r2 'imagelayers.io')


## License

See [LICENSE](LICENSE) for the complete license.


## Changelog

A [ChangeLog.md](ChangeLog.md) is available.


## Contact

Nicolas Lamirault <nicolas.lamirault@gmail.com>


[Alpine Linux]: http://www.alpinelinux.org

[Mosquitto]: http://mosquitto.org/
