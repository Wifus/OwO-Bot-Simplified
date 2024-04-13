# OwO Bot Simplified

A stripped down version of Discord-OwO-Bot for ease of self-hosting! This is a more of a faithful recreation than a 1:1 recreation since, although I think I have a better grasp on the codebase than most, I can't be bothered to try to understand the thoughts behind every line in the mostly undocumented project that is OwO Bot. 

## Self hosting

__***This project is still a work in progress!!! This is not ready for use!!!***__

1. Clone this repository
2. Input imporant configurations in `config/config.json`
3. Profit?!?!

## Limitations

* Most image generation features have been redone to have text output
* Removed extraneous features specific to the main bot's environment
    - Snail and stream websockets
    - Logging features
    - Connection to voting api
    - Macro detection features (they weren't public anyway)
* Most emojis have been replaced by the default emojis. This can be changed in the emoji config file in `config/emoji.json`.
* For ease of self-hosting a simple file based/in memory database is used

## Plans

1. Make the project work.
2. Implement simple QoL features that should be in the bot
3. Implement a version of the legacy battle.

## License

OwO Bot is licensed under the terms of [Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International](https://github.com/ChristopherBThai/Discord-OwO-Bot/blob/master/LICENSE) ("CC-BY-NC-SA-4.0"). Commercial use is not allowed under this license. This includes any kind of revenue made with or based upon the software, even donations.

The CC-BY-NC-SA-4.0 allows you to:

- [x] **Share** -- copy and redistribute the material in any medium or format
- [x] **Adapt** -- remix, transform, and build upon the material

Under the following terms:

- **Attribution** — You must give appropriate credit, provide a link to the license, and indicate if changes were made. You may do so in any reasonable manner, but not in any way that suggests the licensor endorses you or your use.
- **NonCommercial** — You may not use the material for commercial purposes.
- **ShareAlike** — If you remix, transform, or build upon the material, you must distribute your contributions under the same license as the original.

More information can be found [here](https://creativecommons.org/licenses/by-nc-sa/4.0/).
