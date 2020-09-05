# home-assistant

Configuration for [Home Assistant](https://www.home-assistant.io/).


## Usage

### Icons

Built-in icons are available on [Material Design
Icons](https://materialdesignicons.com/) and can be specified like
`mdi:account`.


## Development

Run a docker container locally.

    $ docker run --rm -v $(pwd)/config:/config --net=host --device /dev/ttyUSB0 --device /dev/ttyUSB1 homeassistant/home-assistant:stable

Run the tests.

    $ pipenv run test
