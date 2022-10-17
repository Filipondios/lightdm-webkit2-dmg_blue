# lightdm-webkit2 - 'Filipondios Theme'

Simple LightDM Webkit2 theme, based in the original <a href="https://github.com/davidmogar/lightdm-webkit2-dmg_blue">lightdm-webkit2-dmg_blue</a> theme from <a href="https://github.com/davidmogar">@davidmogar</a>.

![imagen](https://user-images.githubusercontent.com/91225771/196256918-8bb6af7e-d4f7-402f-b116-e2929c0aac2d.png)

## Features

This theme is designed to be simple, so it provides the bare minimum to be usable:
* Selection of user, remembering the last user who loged into the system.
* Selection of session (fetching the list of installed desktop environments).
* Session cache for each user, remembering the last session used.
* Shutdown and restart buttons.

## Installation instructions

The theme depends on the `lightdm-webkit2-greeter` package. Once you have it installed:

* Git clone this repository into `/usr/share/lightdm-webkit/themes/`
* Edit `/etc/lightdm/lightdm-webkit2-greeter.conf` and set `webkit_theme` to `lightdm-webkit2-dmg_filipondios`.


## License

This project is under the GNU General Public License v3.0. Check [LICENSE](https://github.com/davidmogar/lightdm-webkit2-dmg_blue/blob/master/LICENSE) file to see the full text full text.
