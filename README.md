# horizon-extended.kitty

Bringing the Horizon Extended theme over to kitty

## Usage

Copy `horizon-extended.conf` to your kitty configuration directory.

```sh
cp horizon-extended.conf ~/.config/kitty/kitty-themes/
```

Then create a link to the configuration file in your kitty configuration directory.

```sh
ln -s ~/.config/kitty/kitty-themes/horizon-extended.conf ~/.config/kitty/theme.conf
```

Lastly add the following line to the top of your kitty configuration file.

```sh
include ./theme.conf
```

Reload your configuration file and it should work!
