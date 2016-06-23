# Vacuum cleaner battle

The vacuum cleaner battle! An example of how to use the op-en platform.

For details, see https://op-en.se/vacuum-cleaner-battle/

## Running

For info on running Open Energy on Raspberry Pi, see https://op-en.se/on-rpi

```
docker-compose up -d
```

If you are starting it for the first time, import the contents of vacuum-battle-flow.json into node-RED.

Do this by:

1. Open the file `vacuum-battle-flow.json` and copy the contents
1. Go to http://[raspberry pi ip]:1880 and Go to hamburger menu (upper right corner) -> import -> clipboard
1. Paste the contents of `vacuum-battle-flow.json`
1. Place it somewhere on the board
1. Hit deploy in upper right corner

## TODO

- Add missing plugwise configuration
- Add missing particle.io code for LED strip
