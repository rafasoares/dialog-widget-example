# UE4 Dialog Widget example

This project contains a `Dialog` widget which takes an array of Lines and displays each line as one dialog box, using a "typewriter" effect (one character at a time). You can press space bar or enter to skip to the end of the current line.

After a line has been "typed", an animated prompt appear, either an ellipsis if there are more lines or a check mark (UTF-8 character ✔️, which might not work with all fonts) if it's the final one.

The project also includes a `DialogTrigger` blueprint, with an example of how to setup and use the widget programmatically, and a level with one instance of that blueprint to show the interaction.

## How to use

Place the DialogTrigger blueprint on a level and set up the `Dialog Lines` array.

## Built With

* [Unreal Engine 4](https://www.unrealengine.com) - [v4.20.2](https://github.com/EpicGames/UnrealEngine/releases/tag/4.20.2-release)

## Authors

* **Rafael Soares** -[rafasoares](https://github.com/rafasoares)

## License

This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details
