# surf - simple webkit-based browser

`surf` is a simple Web browser based on `WebKit/GTK+`.


# Features & Patches

- [homepage](https://surf.suckless.org/patches/homepage/): Allows you to set a homepage to be loaded when you have not set a `uri`.

## Requirements

In order to build surf you need `GTK+` and `Webkit/GTK+` header files.
In order to use the functionality of the `url-bar`, also install [dmenu](http://tools.suckless.org/dmenu).


## Installation

Edit `config.mk` to match your local setup (surf is installed into the `/usr/local` namespace by default).

Afterwards enter the following command to build and install surf:

```bash
sudo make clean install
```

## Running

```bash
surf [URI]
```

See the `manpage` for further options.

## Running surf in tabbed

For running surf in [tabbed](http://tools.suckless.org/tabbed) there is a script included in the distribution,
which is run like this:

```bash
surf-open.sh [URI]
```
