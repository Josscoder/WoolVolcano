# WoolVolcano

Victory effect for your Minecraft BE server, inspired by Cubecraft, for Pocketmine 4.0.0

If you encounter any bugs, have suggestions or questions, [create an issue](https://github.com/Josscoder/WoolVolcano/issues/new).

## How can I preview?

Only operator players can write "volcano" without quotes in the server chat.
[Here](https://twitter.com/Josscoder/status/1397231329180364801) is an example video

## For developers

With the following code you can give the win effect to the player:
````php
\jossc\volcano\Main::getInstance()->giveTo($player);
````
